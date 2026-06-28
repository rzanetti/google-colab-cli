# Google Colab CLI PKGBUILD

A command-line interface for [Google Colab](https://colab.research.google.com). Provision high-performance CPU, GPU, and TPU runtimes, execute local code, manage remote files, and orchestrate automated cloud pipelines — directly from your terminal.

![GitHub Tag](https://img.shields.io/github/v/tag/rzanetti/google-colab-cli?style=flat&logo=github&label=GitHub&color=888888) ![GitHub License](https://img.shields.io/github/license/rzanetti/google-colab-cli?style=flat&logo=github&label=License&color=888888) ![AUR Version](https://img.shields.io/aur/version/colab-cli?style=flat&logo=archlinux&label=AUR&color=1793d1) ![AUR License](https://img.shields.io/aur/license/colab-cli?style=flat&logo=archlinux&label=License&color=1793d1) ![PyPI - Version](https://img.shields.io/pypi/v/google-colab-cli?style=flat&logo=pypi&label=PyPI&color=0073b7) ![PyPI - License](https://img.shields.io/pypi/l/google-colab-cli?style=flat&logo=pypi&label=License&color=0073b7)

## Why this package exists?

This repository provides an [Arch Linux](https://archlinux.org) `PKGBUILD` for software that is not currently available in the [official repositories](https://wiki.archlinux.org/title/Official_repositories).

The goal is to make installation reproducible, auditable, and compatible with standard Arch Linux packaging practices.

## Upstream project

This repository **does not** contain the original software! It contains only the Arch Linux packaging files.

The software itself is maintained by the upstream project.

Upstream source code:

- [googlecolab/google-colab-cli](https://github.com/googlecolab/google-colab-cli)

[PyPI](https://pypi.org) package:

- [google-colab-cli · PyPI](https://pypi.org/project/google-colab-cli)

## Installation

You can install this package directly from the AUR using your favorite AUR helper:

```bash
yay -S colab-cli
```

If you prefer to build the package manually, just clone it from AUR:

```bash
git clone https://aur.archlinux.org/colab-cli.git
cd colab-cli
makepkg -si
```

## Maintenance

The `PKGBUILD` tracks upstream releases published on [PyPI](https://pypi.org/project/google-colab-cli).

Issues related to the packaged software itself should be reported [upstream](https://github.com/googlecolab/google-colab-cli).

Issues related to Arch Linux packaging can be reported in this repository.
