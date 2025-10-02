# Linux-Package-Browser
A simple cross-platform GUI package browser built with wxWidgets. Currently supports pacman package manager, allowing you to browse installed packages, view their details, and inspect dependencies in a clean graphical interface.

## Features
- Package List - Lists installed packages using pacman -Qq
- Package Details - View descriptions, version info, and dependencies
- GUI with wxWidgets - Split view for easy navigation
- Dependency Information - explore forward and reverse dependencies

## Getting Started
### Prerequisites
- A linux distribution with pacman (e.g., Arch Linux, Manjaro).
- CMAKE (3.10+ recommended)
- wxWidgets (must be installed and available to your compiler).

Install dependencies on Arch-based systems:
```bash
sudo pacman -S base-devel cmake wxwidgets
```

### Build Instructions
Clone the repo and build with CMake:
```bash
git clone https://github.com/jerichijer/Linux-Package-Browser.git
cd Linux-Package-Browser
mkdir build && cd build
cmake ..
make
```

### Run
```bash
./package-browser
```
