# MOBIQ documentation

The product documentation of the fictional ERP vendor MOBIQ (Musterhaus Software GmbH), as it stood **before** release 26.4. It is therefore as outdated as it would be after the release without neuraldoc. The documents themselves are in German.

| Folder | Corresponds to | Contents |
|---|---|---|
| `confluence/` | Confluence Cloud REST v2 | 4 spaces, 33 pages in storage format; `storage/*.xml` readably formatted, `page_meta.json` with labels (document type) and attachments |
| `dokumente/` | SharePoint / Microsoft Graph | 7 files (Word, Excel, PDF) under `files/`, `driveItems.json` and the extracted text in `extracted.json` |

Part of the evaluation dataset: code in [`mobiq-code`](https://github.com/neuraldoc-ai/mobiq-code), database in [`mobiq-db`](https://github.com/neuraldoc-ai/mobiq-db), generator, tickets and solution in [`mobiq`](https://github.com/neuraldoc-ai/mobiq). Do not edit by hand; regenerate in the `mobiq` repository (`node generate.mjs && node publish.mjs`).

All companies, people and contents are fictional.

## License

MIT, see [LICENSE](LICENSE). It covers the whole MOBIQ dataset.
