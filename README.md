# PolyMC-Offline

## This repository has been archived.

### This fork reverts commit `e0a04c50316089b9a443355394c5babf39a1771d` on pull request [#113](https://github.com/PolyMC/PolyMC/pull/113) by [@NyaomiDEV](https://github.com/NyaomiDEV) to implement offline accounts.

PolyMC-Offline is a custom launcher for Minecraft that focuses on predictability, long term stability and simplicity. **This is an offline version of PolyMC that lets you play the game without a Mojang account.**

This software is not related to PolyMC developers. **Don't create issues on the original repository if something goes wrong.**
This is a **fork** of the MultiMC Launcher and not endorsed by MultiMC. The PolyMC community felt that the maintainer was not acting in the spirit of Free Software so this fork was made.
<br>

# Installation

- Last build status:

[![CI](https://github.com/lebestnoob/PolyMC/actions/workflows/main.yml/badge.svg)](https://github.com/lebestnoob/PolyMC/actions/workflows/trigger_builds.yml)

## 🐧 Linux

### <img src="https://www.vectorlogo.zone/logos/linuxfoundation/linuxfoundation-icon.svg" height="20" alt=""/> Cross-distro packages

<a href="https://nightly.link/lebestnoob/PolyMC-Offline/workflows/trigger_builds/develop/PolyMC-Linux-Release-x86_64.AppImage.zip"><img src="https://docs.appimage.org/_images/download-appimage-banner.svg" width="240" alt="Download as AppImage" /></a>

- Must remove .zip from file name

[Linux (64-bit)](https://nightly.link/lebestnoob/PolyMC-Offline/workflows/trigger_builds/develop/PolyMC-Linux-Release.zip) - this is a portable package, you can extract it anywhere and run it. This package needs testing and may not run on all distros. You may need to manually make the binary executable by running the command `chmod +x polymc` in the terminal.

## <img src="https://www.vectorlogo.zone/logos/microsoft/microsoft-icon.svg" height="20" /> Windows

[Windows (32-bit)](https://nightly.link/lebestnoob/PolyMC-Offline/workflows/trigger_builds/develop/PolyMC-Windows-Release.zip) - this is a portable package, you can extract it anywhere and run it. This package needs testing.

## <img src="https://www.vectorlogo.zone/logos/apple/apple-tile.svg" height="20" /> MacOS

[MacOS Binary (64-bit)](https://nightly.link/lebestnoob/PolyMC-Offline/workflows/trigger_builds/develop/PolyMC-macOS-Release.zip) - this is a portable package, you can extract it anywhere and run it. This package needs testing. You may need to manually make the binary executable by running the command `chmod +x polymc` in the terminal.

## Development Builds

There are per-commit development builds available [here](https://github.com/lebestnoob/PolyMC-Offline/actions). These have debug information in the binaries, so their file sizes are relatively larger.
Builds are provided for Linux, AppImage on Linux, Windows, and macOS.

# Help & Support

Feel free to create an issue if you need help.

## Building

If you want to build PolyMC yourself, check [BUILD.md](BUILD.md) for build instructions.

## Code formatting

Just follow the existing formatting.

In general, in order of importance:

- Make sure your IDE is not messing up line endings or whitespace and avoid using linters.
- Prefer readability over dogma.
- Keep to the existing formatting.
- Indent with 4 space unless it's in a submodule.
- Keep lists (of arguments, parameters, initializers...) as lists, not paragraphs. It should either read from top to bottom, or left to right. Not both.

## Translations

The translation effort for PolyMC is hosted on [Weblate](https://hosted.weblate.org/projects/polymc/polymc/) and information about translating PolyMC is available at https://github.com/PolyMC/Translations

## Forking/Redistributing/Custom builds policy

Do whatever you want, we don't care. Just follow the license. If you have any questions about this feel free to ask in an issue.
