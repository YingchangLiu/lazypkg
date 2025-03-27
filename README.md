# lazypkg

Common package manager commands for lazy me.

`lazypkg` is a lightweight Bash script that unifies package management commands. It simplifies common tasks like updating, upgrading, installing, and removing packages, so you don't have to remember distribution-specific commands.

## Supported Distributions

- **Arch Linux** (`pacman`)
- **Debian/Ubuntu** (`apt`)
- **Fedora/CentOS** (`dnf`)
- **openSUSE** (`zypper`)
- **Gentoo** (`emerge`)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/lazypkg.git
   cd lazypkg

2. Add the script to your $PATH:
    ```bash
   mkdir -p $HOME/.local/bin
   cp ./pkg $HOME/.local/bin

3. Verfy the installation:
    ```bash
    pkg --version

## Usage

Run pkg help to see the full list of available commands:
    ```

    Usage: pkg [command] [options]

    Commands:
    update, upd, up       Update package lists
    upgrade, upg, ug      Upgrade all packages
    install, ins, in      Install a package
    reinstall, reins, rin Reinstall a package
    cleanup, clean, cl    Clean up unused packages
    remove, rm, rem       Remove a package
    search, se, srch      Search for a package
    provider, prov, prv   Find which package provides a file
    help, h               Show this help message
