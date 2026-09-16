<p align="center">
  <img src="https://www.metaprotrader.com.br/uploads/TradeMetaPro-logo.png" alt="MetaPro Trader logo" width="180" />
</p>

<h1 align="center">MetaPro Trader</h1>

<p align="center">
  AI-powered desktop trading platform, built with native support for MetaTrader 5.
</p>

<p align="center">

  <img alt="MetaTrader 5" src="https://img.shields.io/badge/MetaTrader-5-2563eb?style=for-the-badge" />

  <img alt="Cross Platform" src="https://img.shields.io/badge/Desktop-Windows%20%7C%20Linux%20%7C%20macOS-16a34a?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://www.metaprotrader.com.br/meta-3.png" alt="MetaPro Trader platform preview" width="100%" />
</p>
<br>
<p align="center">
<img width="1919" height="1151" alt="meta-4" src="https://github.com/user-attachments/assets/6c4df1d2-9da9-4cae-9b19-38d1e2a4dbb6" />
</p>
<br>
<p align="center">
<img width="1918" height="1150" alt="meta-5" src="https://github.com/user-attachments/assets/2739e65c-006d-4fb8-95f1-4e5d8970d32b" />
</p>
<br>
<p align="center">
<img width="1917" height="1153" alt="rb" src="https://github.com/user-attachments/assets/da96815e-6bdb-4a5a-9e89-5fe4fbbe2043" />
</p>

# MetaPro Trader

![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-AppImage-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![macOS](https://img.shields.io/badge/macOS-Portable-000000?style=for-the-badge&logo=apple&logoColor=white)
![MetaTrader 5](https://img.shields.io/badge/MetaTrader_5-native_connection-1E6FBA?style=for-the-badge)

**A desktop trading workstation that connects straight to your broker's MetaTrader 5 server — no MT5 terminal required.**

MetaPro Trader brings charting, order flow, order execution and AI-assisted analysis into a single cross-platform application. It connects natively to MetaTrader 5 servers, so you can run several broker connections side by side without keeping the MetaTrader terminal open.

Orders travel from your machine directly to your broker's MT5 server. They do not pass through MetaPro Trader's infrastructure.

- 🌐 **Website:** [metaprotrader.com.br](https://www.metaprotrader.com.br)
- 📘 **Manual:** [Online documentation](https://www.metaprotrader.com.br/documentacao) · [English](https://www.metaprotrader.com.br/en/documentation)
- ⬇️ **Downloads:** [Latest release](../../releases/latest)

---

## Download

Every release publishes four builds:

| Platform | Artifact | Notes |
|---|---|---|
| Windows (installer) | `*win-Setup.exe` | Guided setup for Windows 10 and 11 |
| Windows (portable) | `*win-Portable.zip` | Runs without installing |
| Linux | `*.AppImage` | Single executable file |
| macOS | `*osx-Portable.zip` | Portable package |

Pick the build for your system on the [Releases page](../../releases/latest), or use the [download page](https://www.metaprotrader.com.br/download) on the website, which always points to the latest release.

## Requirements

- **Operating system:** Windows 10 or 11, macOS, or Linux
- **Processor:** a modern Intel, AMD, or Apple Silicon processor
- **Memory:** 8 GB of RAM or more
- **GPU acceleration:** available on Windows; macOS and Linux run on CPU
- **MetaTrader 5 terminal:** not required — the application talks to your broker's MT5 server directly
- **Account:** an active MetaPro Trader subscription, validated at sign-in

How many MT5 servers you can keep connected at the same time depends on your own hardware: RAM, CPU, disk, and internet bandwidth.

## Quick start

1. **Install and open** the build for your operating system.
2. **Sign in** with your MetaPro Trader username and password.
3. **Add a connection** in *MetaTrader 5 Servers*, either by searching for your broker or by entering the server's domain or IP with the port. Enter your account number, password, and a name for the connection.
4. **Open a chart** from a connected server through *New Chart*.
5. **Set up your workspace**: choose the timeframe, add indicators, and save a template.
6. **Turn on the AI panel** or open the *Strategy Lab* when you want assisted analysis.

Full step-by-step instructions, with screenshots, are in the [online manual](https://www.metaprotrader.com.br/en/documentation).

## Features

### Broker connectivity

- Native connection to MetaTrader 5 servers, with no MT5 terminal installed
- Several broker servers connected at the same time, each with its own charts
- Connection by broker search or by domain/IP and port
- Optional automatic reconnection when the application starts
- Orders sent straight from your machine to the broker's MT5 server

### Order flow and market depth

- **Footprint** charts, cell by cell, with volume and delta per price level
- **Cumulative delta (CVD)** with divergence detection
- **Session profile** and session indicators in the header
- **Order book** (market depth)
- **Times and Sales** with a quick filter, a rule-based filter window, and an aggression meter
- Position overlay on top of the flow

### Charts and technical analysis

- Over 50 customizable technical indicators
- Drawing tools, Fibonacci tools, and text annotations
- Indicator templates you can save and reload
- Chart settings per workspace

### AI-assisted analysis

- Pattern analysis on the chart, with readings you configure yourself
- **Consensus panel** showing direction and confidence, plus live and performance sections
- **AI training and retraining** from the application, on the data and parameters you choose
- **Strategy Lab (Robot Entry Lab):** entry automation driven by AI predictions, with strategy selection, entry type, trailing stop, result cards, and an analysis table

### Trading and risk

- Market orders, limit orders, and position closing
- Trade history
- Risk management controls
- Subscription status visible inside the application

### Application

- Windows, Linux, and macOS from the same codebase
- Interface in English and Portuguese (Brazil)
- Built-in update check
- Reset to factory settings when you need a clean configuration

## Documentation

The manual covers the whole application and is published in English and Portuguese:

- Login, main window, and MT5 server management
- Charts, toolbar, indicators, and templates
- Order book, Times and Sales, and the filter rules
- AI on the chart, the consensus panel, and AI training
- Trading menu, order placement, and trade history
- Settings, Fibonacci, and subscription status
- Help, updates, and maintenance
- Strategy Lab (Robot Entry Lab) and the MetaPro Trader AI card
- Order Flow: Footprint, delta, and profile

Read it at [metaprotrader.com.br/en/documentation](https://www.metaprotrader.com.br/en/documentation), or open *Help → Online manual* inside the application.

## Subscription

MetaPro Trader is a paid application. A single **Pro** plan unlocks every feature listed above, in both billing intervals:

| Billing | Brazil (BRL) | International (USD) |
|---|---|---|
| Monthly | R$ 99,90 / month | $19.90 / month |
| Annual | R$ 999,00 / year | $199.00 / year |

- **7-day money-back guarantee**, with a full refund
- **Cancel at any time**
- Licenses are bound to the user: you may install on Windows, Linux, or macOS, with **one simultaneous connection per user**

Subscribe at [metaprotrader.com.br](https://www.metaprotrader.com.br).

## Support

- **Tickets:** after subscribing, the *My Tickets* menu appears in the website navigation — this is the main support channel
- **E-mail:** suporte@metaprotrader.com.br
- **Live chat:** Monday to Friday, 09:00–18:00
- **In-app:** *Help → Support*

## For brokerages

- **Broker compatibility check:** search your broker on the [broker check page](https://www.metaprotrader.com.br/broker-check)
- **Certification programme:** brokers go through technical mapping, controlled connectivity tests, stability validation, and receive a *Certified brokerage* badge
- **White-label:** the platform can carry your brokerage's logo, texts, name, and domain. Details on the [brokerage page](https://www.metaprotrader.com.br/en/metapro-for-brokers)

## Reporting a problem

Please open a support ticket from your account, or write to suporte@metaprotrader.com.br, including:

- the release version (shown in *Help → About*)
- your operating system
- the broker and server you were connected to
- what you expected to happen, and what happened instead

## Risk disclaimer

MetaPro Trader is analysis and execution software. It does not provide investment advice, and no indicator, AI reading, or automated entry can predict market behaviour. Trading leveraged instruments carries the risk of losing more than your initial capital. You remain responsible for every order sent from your account, including orders placed by automation. Test your setup on a demo account before trading live.


## Getting Started

- https://www.metaprotrader.com.br

## License

The MetaPro Trader licenses are proprietary and are specified on the official MetaPro Trader website.
