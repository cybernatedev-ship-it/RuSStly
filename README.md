# RuSStly

A native podcast client built with Rust and egui.

## Features

- Subscribe to RSS/Atom podcast feeds
- Browse episodes with unplayed/downloaded filters
- Download episodes for offline playback
- Playback with speed control, skip, and seek
- Auto-mark episodes as played near the end
- Sleep timer
- OPML import/export
- Sync downloads to a directory
- Dark/light theme

## Build

```sh
cargo build --release
```

## Run

```sh
cargo run --release
```

Data is stored in `~/.local/share/russtly/`.

## Usage

1. Paste a feed URL in the sidebar and click **Add Feed**
2. Click on a feed to browse its episodes
3. Click **Download** to save an episode, then **Play** to listen
4. Use **Refresh All** to update all feeds

## Settings

Configure download directory, auto-download, max episodes per feed, and playback options from the ⚙ settings panel.
