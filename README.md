<p align="center"><img src="https://raw.githubusercontent.com/ShinozakiKasumi/ProjectA/main/docs/brand/akari-logo.svg" width="120" alt="Akari logo" /></p>

<h1 align="center">Project Akari — Desktop Client</h1>
<p align="center"><em>Illuminating the Path of Learning</em></p>

---

## About

Akari Desktop Client is the cross-platform desktop application of [Project Akari](https://github.com/ShinozakiKasumi/ProjectA), powered by Tauri 2 with a Rust backend and web-based frontend. It delivers a native-feeling desktop experience with a lightweight footprint across Windows, macOS, and Linux.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Framework | [Tauri 2](https://v2.tauri.app/) — lightweight native desktop framework |
| Backend | Rust 1.77+, serde, tauri-plugin-log |
| CLI | @tauri-apps/cli 2.11.2 |
| Frontend | HTML5, CSS3, JavaScript (WebView-backed) |
| Platforms | Windows (.exe), macOS (.dmg), Linux (.AppImage) |
| Releases | [GitHub Releases](https://github.com/ShinozakiKasumi/ProjectA-Desktop/releases) |

## Features

- Native desktop packaging via Tauri (Rust backend + WebView frontend)
- Multi-platform builds: Windows, macOS, Linux
- Tiny binary size compared to Electron-based solutions
- Automatic log collection via tauri-plugin-log

## Building

```bash
# Install dependencies
npm install

# Development
npm run build  # or: npx tauri build
```

## License

MIT License. See [LICENSE](./LICENSE).
