# Yocto Setup Guide

## Installation Steps:
1. Installed dependencies: `sudo apt install [packages]`
2. Cloned poky: `git clone git://git.yoctoproject.org/poky`
3. Checked out kirkstone: `git checkout kirkstone`
4. Initialized build: `source oe-init-build-env`
5. Configured for QEMU: `MACHINE = "qemux86-64"`

## Current Build:
- Target: core-image-minimal
- Machine: qemux86-64
- Started: $(date)
- Status: Building...
