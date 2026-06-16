# Google Colab CLI PKGBUILD

A command-line interface for [Google Colab](https://colab.research.google.com). Provision high-performance CPU, GPU, and TPU runtimes, execute local code, manage remote files, and orchestrate automated cloud pipelines — directly from your terminal.

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

```bash
git clone https://aur.archlinux.org/colab-cli.git
cd colab-cli
makepkg -si
```

## Maintenance

The `PKGBUILD` tracks upstream releases published on [PyPI](https://pypi.org/project/google-colab-cli).

Issues related to the packaged software itself should be reported [upstream](https://github.com/googlecolab/google-colab-cli).

Issues related to Arch Linux packaging can be reported in this repository.
