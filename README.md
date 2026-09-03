# XAUUSD 3d OHLCV Metals Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-6_323_rows-blue)](https://getdata.finance/datasets/xauusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/xauusd)

### -> [**Download the full XAUUSD dataset on getdata.finance**](https://getdata.finance/datasets/xauusd)

**XAUUSD 3d OHLCV metals historical data** — ultra high-quality 3d OHLCV for **Gold / US Dollar**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **Gold / US Dollar** (Metals)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/xauusd) · **6,323** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `XAUUSD_3d.csv` (20 rows, `2026-07-06` -> `2026-09-01`, 1.38 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/xauusd)** — **6,323** `3d` rows (full `1m`: 6,032,490), **11 timeframes**, `1970-02-27` -> `2026-09-01`.

## Download sample

**[XAUUSD_3d.csv](https://github.com/getdata-finance/xauusd-3d-ohlcv-metals-historical-data/blob/main/XAUUSD_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/xauusd-3d-ohlcv-metals-historical-data/main/XAUUSD_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/xauusd-3d-ohlcv-metals-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/xauusd-3d-ohlcv-metals-historical-data/](https://getdata-finance.github.io/xauusd-3d-ohlcv-metals-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/xauusd](https://getdata.finance/datasets/xauusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/xauusd))** |
|---|--:|---|
| Instrument | Gold / US Dollar · Metals | Gold / US Dollar · Metals |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 20 | **6,323** |
| Size | 1.38 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Period | `2026-07-06` -> `2026-09-01` | `1970-02-27` -> `2026-09-01` |
| File | `XAUUSD_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/xauusd) |
| Coverage report | — | [XAUUSD coverage](https://getdata.finance/coverage/xauusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/xauusd)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/xauusd) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`XAUUSD_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-06T00:00:00+00:00 | 4075.27 | 4138.05 | 4054.21 | 4123.35 | 1586202 |
| 2026-07-09T00:00:00+00:00 | 4123.35 | 4134.83 | 4060.5 | 4099.67 | 1357750 |
| 2026-07-12T00:00:00+00:00 | 4111.51 | 4111.51 | 3983.11 | 4059.82 | 3110600 |
| 2026-07-15T00:00:00+00:00 | 4059.82 | 4065.24 | 3959.49 | 4050.83 | 4359944 |
| 2026-07-18T00:00:00+00:00 | 4013.3 | 4087.32 | 3982.21 | 4077.43 | 1668040 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-08-20T00:00:00+00:00 | 4518.53 | 4632.07 | 4508.71 | 4608.07 | 945337 |
| 2026-08-23T00:00:00+00:00 | 4608.07 | 4696.62 | 4566.48 | 4580.67 | 2401724 |
| 2026-08-26T00:00:00+00:00 | 4580.67 | 4626.71 | 4441.31 | 4452.78 | 1407193 |
| 2026-08-29T00:00:00+00:00 | 4456.77 | 4472.13 | 4322.66 | 4328.35 | 2056503 |
| 2026-09-01T00:00:00+00:00 | 4328.35 | 4335.81 | 4288.45 | 4289.48 | 162596 |

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

df = pd.read_csv('XAUUSD_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('XAUUSD_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('XAUUSD_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **XAUUSD** archive on **[getdata.finance](https://getdata.finance/datasets/xauusd)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **6,323** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full XAUUSD dataset on getdata.finance](https://getdata.finance/datasets/xauusd)**

---
*GetData · XAUUSD 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/xauusd)*
