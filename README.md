# NHS England — 28-Day FDS Dashboard (Colorectal Cancer)

An interactive dashboard visualising NHS England 28-day Faster Diagnosis Standard (FDS) performance for **colorectal cancer** (suspected lower gastrointestinal cancer), Oct 2024 – Sep 2025.

Built for public health research using publicly available [NHS England Cancer Waiting Times](https://www.england.nhs.uk/statistics/statistical-work-areas/cancer-waiting-times/) data.

## Features

- **National trend** — England-wide 28-day FDS % over 12 months with 75% target line
- **Provider / Commissioner toggle** — switch between NHS Trust and ICB perspectives
- **Performance league table** — horizontal bar chart for any selected month, colour-coded by target
- **Trend drill-down** — compare individual organisations over time
- **Waiting time breakdown** — stacked bar chart showing delay bands (≤14d, 15–28d, 29–42d, 43–62d, >62d)
- **Data table + CSV export** — full data for any month, downloadable

## Data

- Source: NHS England Cancer Waiting Times (CWT) — publicly available
- 24 Excel workbooks (Provider + Commissioner, one per month, Oct 2024 – Sep 2025)
- Filtered to: *Suspected Lower Gastrointestinal Cancer* (28-Day FDS By Route sheet)

## Run locally

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Deploy to Streamlit Community Cloud

1. Fork or push this repo to your GitHub account
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub account
4. Select this repository, set `app.py` as the main file
5. Click **Deploy** — your dashboard will be live at a public URL

## Target

The NHS 28-day FDS target is that **≥ 75%** of patients receive a definitive cancer diagnosis (or exclusion) within 28 days of urgent referral.
