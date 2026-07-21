# Public survey and source-reporting setup

`contribute.html` is deliberately static: it never exposes a database key and it does not collect or transmit a response until the contributor chooses to post a GitHub issue. This is the safest default for a GitHub Pages research archive.

## Recommended arrangement

Use two channels, not one:

1. **GitHub issues for sources, corrections, and missing records.** They are public, reviewable, versioned, and best for a documentary archive. The built-in report page prepares a structured issue.
2. **Google Forms for anonymous or aggregate survey feedback.** It is simpler than Supabase for a small public project, provides spam controls and CSV export, and keeps form administration out of the repository.

Do not use either public form for case papers, identity documents, contact details, or other sensitive personal information.

## Create the Google Form

Create a Google Form titled “West Bengal OBC research bundle: feedback and missing-source survey”. Suggested questions:

- What kind of feedback is this? (missing source, correction, broken link, usability, other)
- Which timeline event, notification, case, or page does it concern?
- What is the public source URL or citation?
- What should be added or corrected?
- How did you verify it? (official site, gazette, court record, public mirror, other)
- May the project publish your response after removing personal information? (yes/no)

For a ready-to-copy, sectioned form covering certificate-office issues, GPS-tagged notice photographs, court updates, government records, reputable press clippings, and general suggestions, use `GOOGLE_FORM_DRAFT.md`.

Keep email collection **off** unless there is a clear privacy notice and a reason to contact contributors. Do not allow file uploads: they require Google sign-in and invite sensitive material.

After publishing, replace the survey card/link in `contribute.html` with the public Google Form URL. Keep the GitHub issue route available for records that benefit from public source review.

## Why not a client-side Supabase form?

Supabase is useful only when you need a private moderation queue, authenticated roles, or a custom database workflow. It requires Row Level Security, anti-spam/rate limiting, a privacy policy, retention rules, and a server-side Edge Function or equivalent for safe writes. A public anonymous insert key in static HTML is not an adequate moderation or privacy solution for this project.
