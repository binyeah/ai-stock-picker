# 🧠 智能选股 · AI Stock Picker

> AI-powered stock screening tool for China A-shares, ETFs, and funds. Available on Web, Windows, macOS, and Android.

AI 驱动的全平台智能选股工具，覆盖 **A 股选股**、**ETF 分析**、**基金分析**，支持 Web、Windows、macOS、Android。

---

## 🌐 Web App / 网页版

👉 [**h5.binyeah.com**](http://h5.binyeah.com/) — No installation required / 浏览器打开即用

---

## 📱 Downloads / 下载

| Platform | File | Size |
|----------|------|------|
| 🪟 **Windows** | [Setup 1.0.0.exe](https://github.com/binyeah/ai-stock-picker/releases/latest) | ~82 MB |
| 🍎 **macOS** (Intel) | [1.0.0-x64.dmg](https://github.com/binyeah/ai-stock-picker/releases/latest) | ~109 MB |
| 🍎 **macOS** (Apple Silicon) | [1.0.0-arm64.dmg](https://github.com/binyeah/ai-stock-picker/releases/latest) | ~105 MB |
| 🤖 **Android** | [1.0.0.apk](https://github.com/binyeah/ai-stock-picker/releases/latest) | ~70 MB |

> 📦 All versions / 所有版本 👉 [Releases](https://github.com/binyeah/ai-stock-picker/releases)

---

## ✨ Features / 功能

### 📊 Strategy Stock Picking / 策略选股

Multi-strategy stock screening engine with technical indicators and fundamental factors:

- **Multi-strategy parallel scanning** — Built-in strategies (trend following, oversold rebound, momentum breakout, steady growth, etc.)
- **Smart scoring & ranking** — Composite scoring with automatic deduplication
- **Dashboard overview** — Top 10 picks per strategy at a glance
- **Strategy detail view** — Factor breakdown (price change, volume confirmation, valuation, etc.)
- **Factor visualization** — Score bars, progress indicators, labels

> 多策略并行扫描、智能评分排序、策略速览与详情、因子可视化

### 📈 ETF Analysis / ETF 分析

- Real-time ETF quotes and price changes
- Multi-factor ETF scoring (trend strength, volume, volatility)
- Custom ETF watchlist

> ETF 行情扫描、评分系统、自选 ETF 监控

### 💰 Fund Analysis / 基金分析

- Fund NAV (Net Asset Value) lookup and history
- Interactive NAV trend charts with multi-period comparison
- Custom fund watchlist

> 基金净值查询、净值走势图、自选基金监控

### ⭐ Watchlist / 自选管理

- **Stock watchlist** — One-click add from scan results or manual entry
- **ETF watchlist** — Separate ETF tracking pool
- **Fund watchlist** — Separate fund tracking pool

> 股票 / ETF / 基金三大独立自选池

### 📉 K-Line Charts / K 线图表

- Interactive daily K-line charts with zoom and drag
- Real-time intraday charts during A-share trading hours
- Multi-period switching

> 日 K 线图、分时图、多周期切换

### 🎯 AI Stock Picking / AI 选股

- AI-assisted stock screening with intelligent analysis

### 🔬 Strategy Backtesting / 策略回测

- Historical backtesting engine
- Key metrics: win rate, average return, max drawdown, Sharpe ratio
- Multi-strategy cumulative return comparison chart
- Supports 3-year backtest period

> 回测引擎、胜率/收益/回撤/夏普比率、收益对比图

### 📤 Data Export / 数据导出

- CSV export
- Excel (.xlsx) export with selectable save path

> CSV / Excel 导出

### 🔔 Desktop Features / 桌面特性

- Auto-start on system boot
- System notification on scan completion
- Minimize to system tray
- Keyboard shortcuts
- Offline capable (local data cache)

> 开机自启、扫描通知、系统托盘、快捷键、离线可用

---

## ⚙️ Installation / 安装

### Windows

Double-click `AI-Stock-Picker-Setup-1.0.0.exe` and follow the installer. Custom install path supported.

### macOS

1. Download the correct `.dmg` for your chip (Intel or Apple Silicon)
2. Open `.dmg` and drag the app to `Applications`
3. If blocked: **System Settings → Privacy & Security → Open Anyway**

### Android

1. Download the `.apk` to your phone
2. Enable **Install unknown apps** in Settings
3. Open the APK to install

---

## 🛠 Tech Stack / 技术栈

| Layer | Technology |
|-------|------------|
| Desktop Framework | Electron |
| Frontend | React 19 + TypeScript |
| Build Tool | Vite + electron-vite |
| State Management | Zustand |
| Packaging | electron-builder |
| Data Source | Tencent Market API |

---

## 🔗 Links / 链接

- 🌐 Web App: [h5.binyeah.com](http://h5.binyeah.com/)
- 📦 Latest Release: [GitHub Releases](https://github.com/binyeah/ai-stock-picker/releases)
