# Kerbside Driver App (prototype)

A clickable, mobile-first prototype of a money and tax app for UK taxi and private hire drivers. "Kerbside" is a working name.

It is a single file, `index.html`, with no build step. Open it in a browser or host it on any static host such as GitHub Pages.

## What it shows

- **Today:** start and end shifts, today's takings, the last 7 days, how much to set aside for tax, and anything that needs attention.
- **Add sheet:** log takings, costs or a shift on a meter-style keypad. Each cost is mapped to its HMRC category, and you can attach a receipt photo.
- **Date range:** add missed takings or costs for several days at once. You can split a total evenly, repeat the same amount each day, or save one total for the whole period. Days off can be unticked. The app spots runs of missed days and offers to fill them in.
- **Tax:** projected income tax and Class 4 National Insurance (including Scottish rates), Making Tax Digital quarterly updates, payments on account, mileage rate compared with actual car costs, and the VAT threshold.
- **Vehicle:** UK number plate, renewal countdowns for licences, MOT, insurance, road tax, DBS and medical, plus a registration lookup.
- **More:** Universal Credit monthly figures, CSV export, business-use percentages and night mode.

## Notes

- Sample data is for a London private hire driver. Changes are saved in the browser's local storage only.
- Tax figures use 2026/27 rates.
- Nothing is sent to HMRC, DVLA or any other service. The HMRC submission and registration lookup are mock-ups.
