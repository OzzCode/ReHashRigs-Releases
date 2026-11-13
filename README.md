# ReHashRigs Farm Monitor

A free Windows dashboard for monitoring Bitmain Antminer ASIC miners on your local network.

- Auto-discovers miners on your LAN
- Live farm view: hashrate, temperatures, fan speeds and pool status per miner
- Alerts by email, Telegram or Discord
- Profitability and electricity cost tracking (BTC and ZEC)

## Download

**[Download the latest version for Windows](https://github.com/OzzCode/ReHashRigs-Releases/releases/latest/download/ReHashRigs-Monitor.exe)**

All versions and release notes are on the [Releases page](https://github.com/OzzCode/ReHashRigs-Releases/releases).

## Getting started

1. Put `ReHashRigs-Monitor.exe` in its own folder (for example `C:\ReHashRigs`). The app stores its
   database and logs next to the exe.
2. Double-click it. The dashboard opens in your browser at <http://localhost:5000>.
3. Your miners are discovered automatically on the local network.

> **Windows SmartScreen:** the first time you run it, Windows may show "Windows protected your PC".
> Click **More info → Run anyway**. You can confirm the download is genuine by checking its SHA-256
> hash against the one listed in the release notes:
> `Get-FileHash .\ReHashRigs-Monitor.exe -Algorithm SHA256`

## Requirements

- Windows 10 or 11 (64-bit)
- Bitmain Antminers reachable on the same network

## Support

Found a bug or have a feature request? [Open an issue](https://github.com/OzzCode/ReHashRigs-Releases/issues).
