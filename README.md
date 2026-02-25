# 📻 TownieRadio

A minimal, terminal-based radio streamer for local **St. John's, Newfoundland & Labrador** stations.

TownieRadio is a lightweight Rust TUI app that lets you stream local radio directly from your terminal with a retro pixel-art vibe.

No browsers. No ads. Just radio.

---

## ✨ Features

- 🎧 Stream local St. John's radio stations
- 🖥 Retro terminal UI (built with `ratatui`)
- 🎨 Pixelated station logos
- 📡 Live status (LOADING / ONLINE / OFFLINE)
- 📊 Animated spectrum display
- ⌨ Simple keyboard controls

---

## 📡 Included Stations

- CBC Radio 1 (St. John's)
- CHMR 93.5 FM
- CHOZ OZFM
- VOCM AM 590
- VOWR 800

---

## 🛠 Requirements

You need:

- Rust (latest stable recommended)
- `ffplay` (from FFmpeg)

### Install Rust

```bash
curl https://sh.rustup.rs -sSf | sh
```

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/townieradio.git
cd townieradio
```

### Run the app
```bash
cargo run
```
### Build an optimized release version

```bash
cargo build --release
./target/release/townieradio
```