<p align="center">
  <img src="Assets/Logo.png" alt="MetaPro Trader logo" width="180" />
</p>

<h1 align="center">MetaPro Trader</h1>

<p align="center">
  AI-powered desktop trading platform for MetaTrader 5, built with .NET 10 and Avalonia.
</p>

<p align="center">
  <img alt=".NET 10" src="https://img.shields.io/badge/.NET-10.0-0f172a?style=for-the-badge&logo=dotnet" />
  <img alt="Avalonia UI" src="https://img.shields.io/badge/Avalonia-11.3-1f6feb?style=for-the-badge" />
  <img alt="MetaTrader 5" src="https://img.shields.io/badge/MetaTrader-5-2563eb?style=for-the-badge" />
  <img alt="Cloudflare" src="https://img.shields.io/badge/Cloudflare-2563eb?style=for-the-badge&logo=cloudflare" />
  <img alt="Cross Platform" src="https://img.shields.io/badge/Desktop-Windows%20%7C%20Linux%20%7C%20macOS-16a34a?style=for-the-badge" />
</p>

<p align="center">
  <img src="Assets/back-image.jpg" alt="MetaPro Trader platform preview" width="100%" />
</p>

## Overview

MetaPro Trader is a professional desktop trading workstation that combines MetaTrader 5 connectivity, advanced charting, technical analysis tools, AI-assisted pattern intelligence, and release automation in a single cross-platform application.

It is designed for traders and teams who want a richer trading environment with customizable charts, order monitoring, indicator workflows, secure credential handling, and integrated model training pipelines.

## Highlights

- MetaTrader 5 server integration with multi-server workflow support
- Advanced chart workspace with drawing tools, Fibonacci tools, text annotations, and technical overlays
- Dedicated indicators window for configuring and applying chart studies
- Order and trade monitoring interface with filtering and summary views
- AI training and retraining workflows powered by ML.NET
- Pattern detection, scoring, calibration, and operational decision support services
- Secure local storage for credentials and encrypted password handling
- Automatic update flow powered by Velopack
- Cross-platform packaging scripts for Windows, Linux, and macOS
- Built-in language support for English and Portuguese (Brazil)

## Tech Stack

- `.NET 10`
- `Avalonia UI`
- `CommunityToolkit.Mvvm`
- `ScottPlot`
- `ML.NET`
- `Supabase`
- `Npgsql`
- `Velopack`

## Project Structure

```text
Assets/           Branding and UI assets
Models/           Domain and persistence models
Services/         Trading, AI, updates, security, and data services
ViewModels/       Application state and workflows
Views/            Avalonia desktop UI
Themes/           App theming and visual styling
docs/             Supporting project documentation
build-*.sh|ps1    Platform-specific release automation
```

## Getting Started

### Prerequisites

- .NET 10 SDK
- MetaTrader 5 API dependency available to the project
- Access to the configured backend services when authentication is required

### Run locally

```bash
dotnet restore
dotnet run --project MetaProTrader.csproj
```

## Build and Release

Official release scripts are included for every supported desktop target:

- Windows: `./build-windows.ps1`
- Linux: `./build-linux.sh`
- macOS: `./build-macos.sh`

For release pipeline details, see [`docs/release.md`](docs/release.md).

## Configuration

The application supports environment-based backend configuration for Supabase:

- `METAPROTRADER_SUPABASE_URL`
- `METAPROTRADER_SUPABASE_ANON_KEY`

If not provided, the application falls back to its built-in defaults.

## Why MetaPro Trader

MetaPro Trader was built to deliver a modern trading desktop experience that goes beyond basic chart viewing. The platform brings together chart interaction, order visibility, technical studies, AI-assisted decision tooling, and production-ready release automation in one cohesive application.

## Website

- https://www.metaprotrader.com.br

## License

This repository currently does not declare a public license. Add a license file before distributing or accepting external contributions under open-source terms.