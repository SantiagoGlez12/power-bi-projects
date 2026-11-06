# Invoice Reports

`invoices.pbix` has two saved report pages:

| Page | Visuals | Fields referenced in the saved layout |
| --- | --- | --- |
| Page 1 | Two tables and a matrix | Client invoice count, amount and share; province/client; invoice count by concept and type |
| Graficos | 100% stacked bar, donut, card, slicer | Invoice count by concept and sector; total invoice count; province filter |

The projections reference `T_FACTURAS`. Excel and text sources are in `../../datasets/invoices/`. The report was inspected through its saved layout; refresh and chart rendering still require Power BI Desktop.
