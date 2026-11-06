# Power BI Projects

A learning portfolio developed during my Santander Power BI training, with exercises in data import, tabular reporting, aggregation, and interactive visualization.

**Power BI · Excel · Text Data · Business Intelligence**

## Explore the work

| Exercise | Files | Contents verified in report layout |
| --- | --- | --- |
| [Course reports](reports/courses) | `courses.pbix` | Two pages; tables and a clustered bar chart |
| [Invoice reports](reports/invoices) | `invoices.pbix` | Two pages; tables, matrix, 100% stacked bar, donut, card, and slicer |
| [Import exercises](import-exercises) | Three PBIX files | People, course text, and invoice text exercises; report pages contain no visuals |
| [Source datasets](datasets) | Six Excel files and two text files | Original training inputs, organized by topic |

The import exercises are retained as learning artifacts and are not presented as finished dashboards.

## Open and refresh

1. Clone or download this repository.
2. Open a `.pbix` file in a compatible Power BI Desktop installation on Windows.
3. Review its source settings before refreshing. The PBIX files retain original source paths; point Excel and text queries to the matching file in `datasets/` as needed.
4. Inspect the imported data and report pages before using the results.

There are four course workbook stages; their numerical prefixes preserve their original sequence. A complete source-to-query dependency map has not been verified, so use the original filename mapping in the [manifest](docs/source-manifest.json) when selecting an input.

## What was checked

- All five PBIX containers were readable, and their saved report layouts were inspected.
- The [report inventory](docs/report-inventory.json) records page names, visual types, and field projections.
- Binary file hashes were checked after migration. The PBIX and dataset contents were not rewritten.

Power BI Desktop is not available in this environment. Refresh, DAX evaluation, model relationships, and visual appearance have not been revalidated. Screenshots will be added after a Desktop review; no dashboard images are fabricated from the layout metadata.

## Learning context and provenance

These are training exercises, not production business reports. The author confirmed the practice records are fictional or public sample data. Source files came from the `PowerBI Santander` folder in `Documentos GIT`; originals in Drive remain unchanged.

The personal course certificate is excluded from the code portfolio. See the [source manifest](docs/source-manifest.json) for filenames and integrity hashes.
