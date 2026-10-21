# Windows 95 Web Simulator

[![Static checks](https://github.com/Fernando-Silvano/Fernando-Silvano.github.io/actions/workflows/static-checks.yml/badge.svg)](https://github.com/Fernando-Silvano/Fernando-Silvano.github.io/actions/workflows/static-checks.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**[Try the live demo](https://fernando-silvano.github.io/)** · [Report a bug](https://github.com/Fernando-Silvano/Fernando-Silvano.github.io/issues/new/choose) · [Contribute](CONTRIBUTING.md)

An independent, educational, browser-based simulation inspired by the Windows 95 user experience. Built using **HTML, CSS and vanilla JavaScript**, without a build step. It is **not an emulator**, a Microsoft product, or an actual operating system.

## Why this project exists

The simulator offers an approachable environment for exploring historical desktop interaction patterns and learning how browser UI state, draggable windows, menus, application dialogs, and small games can be implemented without frameworks. Students and developers can inspect and modify the source directly.

## Features

- Interactive power-on, simulated BIOS setup, boot animation and **fictional** login screen
- Desktop with icons, Start menu, taskbar, and clock
- Draggable windows with minimize, maximize and close controls
- Simulated My Computer, drives, Control Panel and Recycle Bin interfaces
- Editable Notepad-like text area
- Internet Explorer-inspired **simulated** browser experience
- Minesweeper-style game (8×8 board, 10 mines, flags, timer and reset)
- Functional four-operation Calculator with keyboard support, clear, percent, sign toggle and backspace
- Desktop right-click menu for opening apps and refreshing selection
- Notepad file import/export as plain text, with a 1 MB import limit and discard confirmation
- Calculator shortcut: **Ctrl+Alt+C**
- Shutdown, reboot and logoff-themed flows

Features above describe the intended browser simulation; they do not grant access to real Windows software, physical drives or operating-system settings.

## Getting started

No package installation is needed.

```bash
git clone https://github.com/Fernando-Silvano/Fernando-Silvano.github.io.git
cd Fernando-Silvano.github.io
python -m http.server 8000
```

Open **http://localhost:8000/**. Alternatively, open `index.html` directly in a modern browser.

To explore the simulated boot sequence, click the power button. The demonstration login described by the original project uses the fictional username `administrador` and password `github`. **Never enter your real passwords.**

## Project structure

```text
index.html                       Main HTML, CSS and JavaScript simulator
favicon.png                      Site icon asset
README.md                        Introduction and setup instructions
LICENSE                          License for original code/eligible assets
CONTRIBUTING.md                  Contribution guidelines
SECURITY.md                      Vulnerability reporting policy
.github/workflows/               Basic continuous-integration checks
.github/ISSUE_TEMPLATE/          Bug report and feature request forms
.github/pull_request_template.md Pull request checklist
```

## Development and quality

This intentionally small static web project is a useful starting point for frontend experimentation. Pull requests are welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) for local setup, testing expectations and review workflow. The [GitHub Actions checks](.github/workflows/static-checks.yml) verify basic file and HTML structure, and scan for a limited set of common secret patterns. **They are not a complete security audit or browser test suite.**

Security disclosures: [SECURITY.md](SECURITY.md).

### Roadmap (proposals, not implemented promises)

- Improve accessibility and keyboard navigation
- Add automated browser interaction tests
- Make window management more modular and easier to test
- Add Paint and more classic mini-apps
- Explore opt-in local persistence for simulated user data
- Improve layouts for smaller screens

## Open source and third-party attribution

Original project source code is released under the [MIT License](LICENSE), to the extent the copyright holder has rights to license it. **This grant does not cover third-party materials.** Windows, Windows 95, Internet Explorer, associated logos and interface trademarks belong to their respective owners. Some icon imagery is referenced from [Windows 98 Icon Viewer](https://win98icons.alexmeub.com) (Alex Meub); inspect third-party usage rights before redistribution or reuse.

This fan-made educational interface is not affiliated with, endorsed by, or sponsored by Microsoft.

## Community and transparency

The repository is publicly accessible and accepts contributions, but no claim of large-scale adoption, external contributors or particular download counts is made here. Project impact should be assessed through verifiable public activity and its potential learning value.

[Open an issue](https://github.com/Fernando-Silvano/Fernando-Silvano.github.io/issues) to report a reproducible problem or suggest an improvement.
