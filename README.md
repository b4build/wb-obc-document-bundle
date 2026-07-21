# WB OBC Document Bundle

This repository hosts a self-contained static research site and its source files. Open
`index.html` locally or publish the repository through GitHub Pages.

## Contents

- `obc_pdfs/` - locally bundled PDF source documents used by the timeline, corpus, reports, hearings, and inventory sections.
- `case_pdfs/` - locally bundled litigation records; see its README for provenance and verification notes.
- `case_manifest.json` - structured litigation-record index.
- `related_sources_catalog.json` - triage of additional local OBC-related material, including large court bundles deliberately not committed.
- `obc_documents.json` - extracted text and structured summaries for the document corpus.
- `obc_pdf_manifest.json` - PDF manifest for renamed local source files.
- `obc_hearing_pdf_manifest.json` - hearing/public notice PDF manifest.
- `evidence_file_inventory.csv` - local evidence file inventory.
- `QUICK_REFERENCE.txt` and `README_WB_OBC_SITE.md` - supporting notes from the local bundle.

## Important PRD Survey Addition

The bundle includes:

`obc_pdfs/2012-04-25_2572-PN-O-I-1S-5-2012_first_panchayat_survey_guideline.pdf`

This is the first statewide Panchayat & Rural Development Department guideline/order for determining Backward Class population for Panchayat election reservation. It supports the later 2012 survey trail documents already in the bundle.

## Intended Website Use

The site uses relative links, so downloaded copies work without a network connection. When served by GitHub Pages, the same links continue to work:

```text
https://raw.githubusercontent.com/<owner>/wb-obc-document-bundle/main/obc_pdfs/<file>.pdf
```

For GitHub Pages-style links, use:

```text
https://<owner>.github.io/wb-obc-document-bundle/obc_pdfs/<file>.pdf
```

## GitHub Pages

1. Push the `main` branch to GitHub.
2. In **Settings → Pages**, choose **Deploy from a branch**, then select `main` and `/(root)`.
3. Save. GitHub will publish the site at `https://b4build.github.io/wb-obc-document-bundle/`.

The repository root contains `index.html`, which GitHub Pages uses automatically. The larger litigation bundles listed in `related_sources_catalog.json` are intentionally not published; add concise primary orders or properly described extracts instead.
