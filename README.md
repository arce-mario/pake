# Pake

Turn any webpage into a desktop app. Built with Rust Tauri.

Forked from [tw93/Pake](https://github.com/tw93/Pake).

## Requirements

- Rust >=1.85
- Node >=22 (18 works too)
- pnpm

## Setup

```bash
pnpm i
```

## Development

```bash
pnpm run dev
```

Right-click to open devtools in debug mode.

## Build

```bash
pnpm run build
```

Output will be in `src-tauri/target/release/bundle/`.

## Usage

```bash
pnpm run cli:build
node dist/cli.js https://example.com --name MyApp --author "Your Name"
```

Use `--author` to set the publisher name (appears in Windows MSI installer properties, avoiding "Unknown Publisher"). Use `--identifier` to set a custom bundle ID (e.g. `com.yourname.appname`).

## Configuration

Edit `src-tauri/pake.json` to set the target URL, window options, and other settings before building.

## License

GPL-3.0
