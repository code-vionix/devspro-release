# DevsPro

A local development environment manager for Linux and Windows, in one window:
nginx or Apache sites with trusted HTTPS, Docker, databases, workers, a mail
catcher, logs, ports, SSH, SFTP, a terminal and local LLM traces.

**Website:** [devspro.codevionix.com](https://devspro.codevionix.com)

This repository hosts DevsPro's installers only. Download the latest version
from **[Releases](https://github.com/code-vionix/devspro-release/releases/latest)**.

## Install

| Platform | File |
| --- | --- |
| Debian / Ubuntu / Pop!_OS (64-bit) | `DevsPro_<version>_amd64.deb` |
| Fedora / RHEL (64-bit) | `DevsPro-<version>-1.x86_64.rpm` |
| Windows 10/11 (64-bit) | `DevsPro_<version>_x64-setup.exe` |

```sh
sudo apt install ./DevsPro_<version>_amd64.deb      # Debian / Ubuntu
sudo dnf install ./DevsPro-<version>-1.x86_64.rpm   # Fedora / RHEL
```

On Linux the package needs `pkexec` (polkit). On Windows the installer sets
DevsPro up for every user, so it asks for administrator rights. It isn't
code-signed yet: when SmartScreen shows "Windows protected your PC", choose
**More info → Run anyway**.

Once installed, DevsPro updates itself. The `.sig` file next to each package is
the signature the in-app updater checks.

## License

Free to use under the [CodeVionix License](LICENSE).
Copyright © 2026 CodeVionix. All rights reserved.

**Developed by CodeVionix**
