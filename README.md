# Nostos Runtime Stats Nostlet

A nostlet (plugin panel) for the Nostos TUI that displays runtime statistics.

## Stats Displayed

- **CPU Threads**: Number of available CPU threads
- **OS Threads**: Total number of OS threads in the process
- **Tokio Workers**: Number of tokio async worker threads
- **Blocking Threads**: Number of tokio blocking threads
- **Uptime**: Time since the TUI started (seconds)
- **Memory**: Current process memory usage (MB)
- **PID**: Process ID
- **Load Averages**: 1, 5, and 15 minute system load averages

## Installation

```bash
nostos nostlet install runtime-stats
```

Or manually copy `runtime-stats.nos` to `~/.nostos/nostlets/`

## Usage

1. Start the Nostos TUI: `nostos tui`
2. Press `Ctrl+N` to open the nostlet picker
3. Select "Runtime Stats"
4. Use `Ctrl+Left/Right` to navigate between windows

## Keys

- `r` - Refresh display
- `Esc` or `Ctrl+W` - Close panel

## License

MIT
