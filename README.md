# Nostos Runtime Stats Nostlet

A nostlet (plugin panel) for the Nostos TUI that displays runtime statistics.

## Stats Displayed

- **CPU Threads**: Number of available CPU threads
- **Uptime**: Time since the TUI started (seconds)
- **Memory**: Current process memory usage (MB)
- **PID**: Process ID

## Installation

```bash
nostos nostlet install runtime-stats
```

Or manually copy `runtime-stats.nos` to `~/.nostos/nostlets/`

## Usage

1. Start the Nostos TUI: `nostos tui`
2. Press `Ctrl+N` to open the nostlet picker
3. Select "Runtime Stats"

## Keys

- `r` - Refresh display
- `Esc` or `Ctrl+W` - Close panel

## License

MIT
