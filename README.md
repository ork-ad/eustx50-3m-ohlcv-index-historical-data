# EUSTX50 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-948_564_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full EUSTX50 dataset on ork.ad**](https://ork.ad/)

**EUSTX50 3m OHLCV Stock index historical data** — ultra high-quality 3m OHLCV for **Euro Stoxx 50**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Euro Stoxx 50** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **948,564** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `EUSTX50_3m.csv` (35,559 rows, `2026-01-05` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **948,564** `3m` rows (~50.21 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2012-08-27` → `2026-07-03`.

## Download sample

**[EUSTX50_3m.csv](https://github.com/ork-ad/eustx50-3m-ohlcv-index-historical-data/blob/main/EUSTX50_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/eustx50-3m-ohlcv-index-historical-data/main/EUSTX50_3m.csv)) · [GitHub Releases](https://github.com/ork-ad/eustx50-3m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/eustx50-3m-ohlcv-index-historical-data/](https://ork-ad.github.io/eustx50-3m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Euro Stoxx 50 · Stock index | Euro Stoxx 50 · Stock index |
| Timeframes | `3m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 3m rows | 35,559 | **948,564** |
| Size | 1.95 MB | ~50.21 MB |
| Period | `2026-01-05` → `2026-07-03` | `2012-08-27` → `2026-07-03` |
| File | `EUSTX50_3m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`3m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `3m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`EUSTX50_3m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-05T07:00:00Z | 5872.1 | 5897.24 | 5872.1 | 5894.74 | 16.0 |
| 2026-01-05T07:03:00Z | 5894.74 | 5897.23 | 5893.22 | 5896.73 | 38.0 |
| 2026-01-05T07:06:00Z | 5896.73 | 5899.24 | 5895.22 | 5897.22 | 23.0 |
| 2026-01-05T07:09:00Z | 5897.22 | 5900.24 | 5897.22 | 5899.23 | 25.0 |
| 2026-01-05T07:12:00Z | 5899.23 | 5899.23 | 5895.23 | 5897.22 | 12.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T19:45:00Z | 6420.15 | 6421.66 | 6420.15 | 6421.16 | 8.0 |
| 2026-07-03T19:48:00Z | 6421.16 | 6421.17 | 6419.66 | 6420.67 | 14.0 |
| 2026-07-03T19:51:00Z | 6420.67 | 6421.16 | 6420.15 | 6420.66 | 10.0 |
| 2026-07-03T19:54:00Z | 6420.66 | 6421.17 | 6420.15 | 6420.17 | 16.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('EUSTX50_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('EUSTX50_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('EUSTX50_3m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **EUSTX50** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **948,564** rows at `3m`, plus all other timeframes in the same ZIP.

**[→ Get the full EUSTX50 dataset on ork.ad](https://ork.ad/)**

---
*GetData · EUSTX50 3m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*