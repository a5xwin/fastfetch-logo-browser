# fastfetch-logo-browser

An interactive Bash script to cycle through all available Fastfetch logos using arrow keys or keyboard shortcuts. This script makes it easier to visually choose a Fastfetch logo without manually editing config files or rerunning commands.

## Features

- Preview 400+ Fastfetch logos one by one
- Left/Right arrow key support (or Z/X)
- Instant rendering via `fastfetch --logo`
- No dependencies beyond Fastfetch and Bash

## Installation

Make the script executable:

```bash
chmod +x fastfetch-logo-browser.sh
```

Then run it:

```bash
./fastfetch-logo-browser.sh
```

Or use curl to download and run it directly:

```bash
curl -LO https://raw.githubusercontent.com/a5xwin/fastfetch-logo-browser/main/fastfetch-logo-browser.sh
chmod +x fastfetch-logo-browser.sh
./fastfetch-logo-browser.sh
```

## Controls

- **Left arrow key** or **Z** — previous logo
- **Right arrow key** or **X** — next logo
- **Q** — quit

## Requirements

- `fastfetch` must be installed and available in your PATH
- Bash (version 4 or higher)