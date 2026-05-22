# WB OBC Document Bundle

This repository is intended to host the source files used by `obc_timeline.html`.
The website itself is deliberately not included here.

## Contents

- `obc_pdfs/` - locally bundled PDF source documents used by the timeline, corpus, reports, hearings, and inventory sections.
- `evidence_visual_pages/` - rendered page previews and sheet images used as visual evidence thumbnails.
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

Once this repository is pushed to GitHub, static file links in `obc_timeline.html` can point to raw GitHub URLs:

```text
https://raw.githubusercontent.com/<owner>/wb-obc-document-bundle/main/obc_pdfs/<file>.pdf
```

For GitHub Pages-style links, use:

```text
https://<owner>.github.io/wb-obc-document-bundle/obc_pdfs/<file>.pdf
```

