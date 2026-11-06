# Power BI Projects

A learning portfolio developed during my Santander Power BI training, with exercises in data import, tabular reporting, aggregation, and interactive visualization.

**Power BI · Excel · Text Data · Business Intelligence**

## Publication status

The source files have been inspected, but the five PBIX files and eight datasets are **not yet published in this repository**. They remain in the original Drive folder pending explicit approval for public upload. This repository currently contains documentation and inspection metadata only.

## Source inventory — pending file upload

| Exercise | Files | Contents verified in report layout |
| --- | --- | --- |
| Course reports | `courses.pbix` | Two pages; tables and a clustered bar chart |
| Invoice reports | `invoices.pbix` | Two pages; tables, matrix, 100% stacked bar, donut, card, and slicer |
| Import exercises | Three PBIX files | People, course text, and invoice text exercises; report pages contain no visuals |
| Source datasets | Six Excel files and two text files | Original training inputs, organized by topic |

The import exercises are retained as learning artifacts and are not presented as finished dashboards.

## Open and refresh — after source files are published

1. After publication of the report files, clone or download this repository.
2. Open a `.pbix` file in a compatible Power BI Desktop installation on Windows.
3. Review its source settings before refreshing. The PBIX files retain original source paths; point Excel and text queries to the matching file in `datasets/` as needed.
4. Inspect the imported data and report pages before using the results.

There are four course workbook stages; their numerical prefixes preserve their original sequence. A complete source-to-query dependency map has not been verified, so use the original filename mapping in the [manifest](docs/source-manifest.json) when selecting an input.

## What was checked

- All five PBIX containers were readable, and their saved report layouts were inspected.
- The [report inventory](docs/report-inventory.json) records page names, visual types, and field projections.
- Original file hashes are recorded in the manifest. Binary upload verification is pending publication. The source PBIX and dataset contents have not been rewritten.

Power BI Desktop is not available in this environment. Refresh, DAX evaluation, model relationships, and visual appearance have not been revalidated. Screenshots will be added after a Desktop review; no dashboard images are fabricated from the layout metadata.

## Learning context and provenance

These are training exercises, not production business reports. The author confirmed the practice records are fictional or public sample data. Source files came from the `PowerBI Santander` folder in `Documentos GIT`; originals in Drive remain unchanged.

The personal course certificate is excluded from the code portfolio. See the [source manifest](docs/source-manifest.json) for filenames and integrity hashes.
