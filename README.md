# META 3d OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_565_rows-blue)](https://getdata.finance/datasets/meta) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/meta)

### -> [**Download the full META dataset on getdata.finance**](https://getdata.finance/datasets/meta)

**META 3d OHLCV us stocks historical data** — ultra high-quality 3d OHLCV for **META**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 3d OHLCV** for **META** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/meta) · **1,565** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `META_3d.csv` (20 rows, `2026-07-06` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/meta)** — **1,565** `1m` rows (~0.29 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2012-05-17` -> `2026-07-30`.

## Download sample

**[META_3d.csv](https://github.com/getdata-finance/meta-3d-ohlcv-stocks-historical-data/blob/main/META_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/meta-3d-ohlcv-stocks-historical-data/main/META_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/meta-3d-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/meta-3d-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/meta-3d-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/meta](https://getdata.finance/datasets/meta)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/meta))** |
|---|--:|---|
| Instrument | META · US stocks | META · US stocks |
| Timeframes | `3d` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 20 | **1,565** |
| Size | 0.00 MB | ~0.29 MB |
| Period | `2026-07-06` -> `2026-07-31` | `2012-05-17` -> `2026-07-30` |
| File | `META_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/meta) |
| Coverage report | — | [META coverage](https://getdata.finance/coverage/meta) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/meta)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/meta) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`META_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-06T00:00:00+00:00 | 695.077 | 715.847 | 694.127 | 712.577 | 33810 |
| 2026-07-07T00:00:00+00:00 | 712.577 | 737.577 | 712.577 | 727.787 | 43519 |
| 2026-07-08T00:00:00+00:00 | 727.787 | 727.787 | 710.327 | 715.567 | 29446 |
| 2026-07-09T00:00:00+00:00 | 715.567 | 745.527 | 689.327 | 743.867 | 45071 |
| 2026-07-10T00:00:00+00:00 | 743.867 | 790.127 | 743.867 | 781.317 | 60650 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-27T00:00:00+00:00 | 707.687 | 722.637 | 705.337 | 706.287 | 26934 |
| 2026-07-28T00:00:00+00:00 | 706.287 | 713.057 | 699.327 | 706.157 | 34553 |
| 2026-07-29T00:00:00+00:00 | 706.157 | 712.027 | 694.537 | 699.217 | 30434 |
| 2026-07-30T00:00:00+00:00 | 699.217 | 699.217 | 636.447 | 651.007 | 45837 |
| 2026-07-31T00:00:00+00:00 | 651.007 | 670.547 | 651.007 | 669.217 | 36630 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('META_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('META_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('META_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **META** archive on **[getdata.finance](https://getdata.finance/datasets/meta)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **1,565** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full META dataset on getdata.finance](https://getdata.finance/datasets/meta)**

---
*GetData · META 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/meta) · 2026-08-05 UTC*
