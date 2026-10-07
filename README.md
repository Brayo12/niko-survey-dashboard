# NIKO Phase Two: Caregiver and Child Survey Dashboard

A single-page dashboard for the NIKO caregiver and child questionnaire collected on UNICEF Inform.

## Use
1. Export submissions from Inform as CSV or XLSX (XML values and headers).
2. Open the page and click **Load Inform export**, or drag the file onto it.

The file is read in the browser only. Names, ID numbers and phone numbers are never read or shown.

## Data protection
Do not commit exports to this repository. `.gitignore` blocks `*.csv` and `*.xlsx`. If the page is published with a `data.csv` beside it, keep the repository private and access-controlled.

## Publish
Settings, Pages, deploy from the `main` branch, root folder.
