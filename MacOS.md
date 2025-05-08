# Colima Installation Guide

Colima (Container on Lima) is a container runtime that provides a Docker-compatible experience using containerd or Docker on macOS and Linux. It’s a lightweight alternative to Docker Desktop.

## 📦 Requirements

- macOS or Linux
- [Homebrew](https://brew.sh/) (recommended for macOS users)
- [Lima](https://github.com/lima-vm/lima) will be installed automatically with Colima

## 🚀 Installation

### For macOS

```bash
# Homebrew
brew install colima

# MacPorts
sudo port install colima

# Nix
nix-env -iA nixpkgs.colima