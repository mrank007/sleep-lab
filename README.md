# Sleep Lab

A single-page dashboard that turns a Garmin **Sleep.csv** export into a plain-English, interactive breakdown of the night — sleep score, stage architecture (deep / light / REM / awake), and overnight vitals (HR, HRV, SpO₂, respiration, Body Battery, stress), each graded against typical healthy ranges.

## Use

1. Open the page.
2. In Garmin Connect, export the Sleep.csv for a night.
3. Drag it onto the upload box (or tap to choose it).

Each night is saved in your browser's localStorage, building a tappable history and a score/REM trend chart over time.

## Privacy

No backend, no accounts, no analytics. Sleep data is parsed and stored entirely in your own browser — nothing is uploaded anywhere, and nothing is stored in this repository.

## Notes

- Wrist-based sleep staging is an estimator, not a lab. Trends over weeks matter more than any single night.
- Not medical advice.
