# Nitos_OS Development Guide

## Project

Nitos_OS (Νι.Τοσ)

Pronunciation: Ni.Tos

## Base System

Ubuntu Linux

## Architecture

amd64 (x86-64)

## Desktop Environment

KDE Plasma

## Design Goals

- Modern, minimal interface
- Custom Nitos_OS branding
- Support for desktop PCs and laptops
- Good performance on a range of hardware
- Gradual development of a custom desktop environment

## Initial Release

Version: 0.1.0

## Development Roadmap

1. Establish project configuration.
2. Define the default package selection.
3. Create the branded Ubuntu-based image.
4. Customize the desktop environment.
5. Build a bootable ISO.
6. Test in a virtual machine.
7. Document installation and recovery.

## Build Safety

Build and test images in a dedicated environment.

Do not overwrite the host operating system or modify its bootloader during development.
