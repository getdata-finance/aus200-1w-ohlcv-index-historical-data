# AUS200 1w OHLCV Stock index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_784_rows-blue)](https://getdata.finance/datasets/aus200) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/aus200)

### -> [**Download the full AUS200 dataset on getdata.finance**](https://getdata.finance/datasets/aus200)

**AUS200 1w OHLCV stock index historical data** — ultra high-quality 1w OHLCV for **Australia 200**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1w OHLCV** for **Australia 200** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1w`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/aus200) · **1,784** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1w` sample updated in sync

> **Sample on GitHub** · `AUS200_1w.csv` (105 rows, `2024-08-01` -> `2026-07-30`). **Full archive on [getdata.finance](https://getdata.finance/datasets/aus200)** — **1,784** `1m` rows (~0.12 MB), **11 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W), `1992-05-28` -> `2026-07-30`.

## Download sample

**[AUS200_1w.csv](https://github.com/getdata-finance/aus200-1w-ohlcv-index-historical-data/blob/main/AUS200_1w.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/aus200-1w-ohlcv-index-historical-data/main/AUS200_1w.csv)) · [GitHub Releases](https://github.com/getdata-finance/aus200-1w-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/aus200-1w-ohlcv-index-historical-data/](https://getdata-finance.github.io/aus200-1w-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/aus200](https://getdata.finance/datasets/aus200)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/aus200))** |
|---|--:|---|
| Instrument | Australia 200 · Stock index | Australia 200 · Stock index |
| Timeframes | `1w` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 105 | **1,784** |
| Size | 0.01 MB | ~0.12 MB |
| Period | `2024-08-01` -> `2026-07-30` | `1992-05-28` -> `2026-07-30` |
| File | `AUS200_1w.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/aus200) |
| Coverage report | — | [AUS200 coverage](https://getdata.finance/coverage/aus200) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1w` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/aus200)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

GitHub = `1w` sample · [getdata.finance](https://getdata.finance/datasets/aus200) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1w` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_1w.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-08-01T00:00:00+00:00 | 8092.07 | 8134.18 | 7489.01 | 7618.16 | 237839 |
| 2024-08-08T00:00:00+00:00 | 7618.16 | 7889.68 | 7598.63 | 7860.57 | 122844 |
| 2024-08-15T00:00:00+00:00 | 7860.57 | 8009.03 | 7823.76 | 8003.85 | 79101 |
| 2024-08-22T00:00:00+00:00 | 8003.85 | 8079.1 | 7949.11 | 8001.69 | 89880 |
| 2024-08-29T00:00:00+00:00 | 8001.69 | 8080.28 | 7887.98 | 7927.38 | 101859 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-02T00:00:00+00:00 | 8660.94 | 8827.08 | 8589.59 | 8685.39 | 160758 |
| 2026-07-09T00:00:00+00:00 | 8685.39 | 8840.11 | 8661 | 8788.19 | 142291 |
| 2026-07-16T00:00:00+00:00 | 8788.19 | 8863.41 | 8682.87 | 8835.41 | 155838 |
| 2026-07-23T00:00:00+00:00 | 8835.41 | 9049.01 | 8691 | 9022.09 | 173005 |
| 2026-07-30T00:00:00+00:00 | 9022.09 | 9150.24 | 8979.43 | 9008.67 | 50391 |

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

df = pd.read_csv('AUS200_1w.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_1w.csv', parse_dates=['datetime'])
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

df = pd.read_csv('AUS200_1w.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[getdata.finance](https://getdata.finance/datasets/aus200)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,784** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUS200 dataset on getdata.finance](https://getdata.finance/datasets/aus200)**

---
*GetData · AUS200 1w OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/aus200) · 2026-08-05 UTC*
