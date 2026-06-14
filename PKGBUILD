#!/usr/bin/env bash
# -*- mode: sh; mode: sh-bash -*-
# shellcheck disable=SC2034,SC2154,SC2164

pkgname=colab-cli
pkgver=0.5.11
pkgrel=1
pkgdesc="A command-line interface for Google Colab"
arch=('x86_64')
url="https://github.com/googlecolab/google-colab-cli"
license=('Apache-2.0')
depends=(
    'jupyter-nbformat'
    'python'
    'python-click'
    'python-filelock'
    'python-google-auth'
    'python-google-auth-oauthlib'
    'python-jupyter-kernel-client'
    'python-packaging'
    'python-prompt_toolkit'
    'python-pydantic'
    'python-pygments'
    'python-requests'
    'python-rich'
    'python-typer'
    'python-typing_extensions'
    'python-websocket-client'
)
makedepends=(
    'python-build'
    'python-hatch-vcs'
    'python-hatchling'
    'python-installer'
)
source=(
    "google_colab_cli-$pkgver.tar.gz::https://files.pythonhosted.org/packages/source/g/google-colab-cli/google_colab_cli-$pkgver.tar.gz"
)
sha256sums=(
    'edded4f6453620b83c8ff4b0a6a0bf9da20f1f3c247ddfa7eecdc213561a1aa2'
)
build() {
    cd "google_colab_cli-$pkgver"
    python -m build --wheel --no-isolation
}
package() {
    cd "google_colab_cli-$pkgver"
    python -m installer --destdir="$pkgdir" dist/*.whl
}
