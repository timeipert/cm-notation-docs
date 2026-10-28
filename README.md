# Finalised notation documentations

Read-only data for the documentation viewer of the neume editor (`cm-neumen-editor`).

- **What it is:** 19 manuscripts, each with a pattern table (neume codes) and snippets (crops of the IIIF page images). Format `neume-docs` version 1: `neume-docs.json` is the index, `data/<manuscript>.json` holds one manuscript each. Pictures are not stored here; they are IIIF addresses on the libraries' servers.
- **Where it comes from:** converted on 2026-10-28 from the editor's manuscript backups (`cm-manuscripts-*.json`, `cm-transkript-export-*.json`) with the editor's own publish code, so the result equals Workspace → Publish a documentation. Duplicate file "Kopie von cm-manuscripts-Aa-13" was skipped.
- **Open (state 2026-10-28):** authors, licence and DOI in `neume-docs.json` are empty. Snippets on folios that could not be matched to a IIIF page (Pa 1107: 145v, 146; Mü 5539: 69v; Nau I: 13v, 14v, 18v, 77v) have no picture. No manuscript metadata columns are included.
- **How to read it:** in the viewer, add the repository as an endpoint `gh:<owner>/<repo>` (the repository must be public).
