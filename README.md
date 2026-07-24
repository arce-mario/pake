# Pake

Turn any webpage into a desktop app. Built with Rust Tauri.

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
node dist/cli.js https://example.com --name MyApp
```

## Configuration

Edit `src-tauri/pake.json` to set the target URL, window options, and other settings before building.

## License

GPL-3.0
