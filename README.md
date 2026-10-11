# PhotoCraft Guide

**English** · [简体中文](README.zh-CN.md)

Practical, unofficial guides to [PhotoCraft](https://github.com/storytold/photocraft), the open-source Photoshop alternative written in Rust. The guides live at **[photocraft.im](https://photocraft.im/)**, in English and Simplified Chinese. This repository is their index and their issue tracker: if a guide is wrong, out of date or missing something, [open an issue](https://github.com/clearlove567/photocraft-guide/issues/new/choose).

> **Unofficial.** photocraft.im is a community project and is not affiliated with the ArtCraft team that builds PhotoCraft. Every download link points to the [official GitHub releases](https://github.com/storytold/photocraft/releases), and the site hosts no installers. The official homes of PhotoCraft are [storytold/photocraft](https://github.com/storytold/photocraft) and [getartcraft.com](https://getartcraft.com/apps/photocraft). Report bugs in PhotoCraft itself [upstream](https://github.com/storytold/photocraft/issues), not here.

The guides currently cover **PhotoCraft v0.7.0** (October 2026). Upstream ships a new release every day or two, so each page lists its sources and the date it was last checked.

## Try it in your browser

- **[Online editor](https://photocraft.im/online)**: runs the official PhotoCraft web build, unmodified, at [photocraft.im/app/](https://photocraft.im/app/). The page shows the version and the SHA-256 of the release zip, so you can check it against the official `SHA256SUMS.txt`. Your images are edited on your own device and never uploaded.

## Download and install

| Guide | What it covers |
|---|---|
| [Windows](https://photocraft.im/download/windows) | MSI or portable zip for x64, ARM64 or x86; the setup wizard; checking SHA256SUMS.txt; where `photocraft-cli.exe` is; fixing GPU crashes at launch. |
| [macOS](https://photocraft.im/download/mac) | The signed, notarized universal DMG for Apple silicon and Intel; the community Homebrew cask; installing the separate CLI; start-up problems on older Macs. |
| [Linux](https://photocraft.im/download/linux) | AppImage, deb, rpm, Flatpak and tarball for x86_64 and ARM64, plus the RISC-V tarball; Wayland drag and drop and the X11 switch; pen tablets. Also covers FreeBSD. |
| [Web (WebAssembly)](https://photocraft.im/download/web) | What is in `photocraft-web.zip`, self-hosting it on any static server or with Docker, browser requirements (WebGPU or WebGL2) and how it differs from the desktop app. |

See all platforms on the [download page](https://photocraft.im/download).

## How-to guides

| Guide | What it covers |
|---|---|
| [Change the language](https://photocraft.im/guides/language) | Switch between 17 bundled interface languages without restarting, including Simplified and Traditional Chinese, Japanese and Korean; IME input tips; what stays in English. |
| [Keyboard shortcuts](https://photocraft.im/guides/shortcuts) | Every default shortcut for Windows, Linux and macOS, checked against the v0.7.0 source: menus, tool keys, brush size, number keys for opacity, layers, crop, and how to customise them. |
| [Supported file formats](https://photocraft.im/guides/file-formats) | What opens and what saves: PSD/PSB, Affinity, Paint.NET, OpenRaster, SVG, HEIC, camera RAW, TIFF, WebP, EXR and more, with bit depths, how to convert other editors' files to PSD, and the limits of the web build. |
| [CLI and MCP automation](https://photocraft.im/guides/mcp-cli) | Batch-convert and process images with `photocraft-cli`, and connect Claude Code, Claude Desktop or Cursor to PhotoCraft's MCP server with file access limited to the folders you choose. |
| [Troubleshooting](https://photocraft.im/guides/troubleshooting) | Crashes at launch, GPU and Wayland problems, pen pressure, saving errors and text bugs, with which release fixed each one, where the logs are and how to report a bug. |

## Release notes

Plain-language summaries of what changed in each version: [all release notes](https://photocraft.im/releases).

- [v0.5.0](https://photocraft.im/releases/v0.5.0): Remove Background, Relight, HEIC, a CPU rendering mode and six new interface languages.
- [v0.3.0](https://photocraft.im/releases/v0.3.0): the first Chinese interface, crash-safe saving, and Flatpak, FreeBSD and Windows ARM64 builds.
- [v0.2.0](https://photocraft.im/releases/v0.2.0): camera RAW, a colour-managed canvas, sandboxed plug-ins and safer automation.
- [v0.1.1](https://photocraft.im/releases/v0.1.1): Photomerge, Merge to HDR Pro, Variables and a video Timeline.
- [v0.1.0](https://photocraft.im/releases/v0.1.0): the first public release.

## Report a problem with a guide

- **A guide is wrong or out of date:** use the [guide error](https://github.com/clearlove567/photocraft-guide/issues/new?template=guide-error.yml) form. Include the page URL and, if you can, the PhotoCraft version you tested.
- **Something is missing:** suggest a topic with the [guide request](https://github.com/clearlove567/photocraft-guide/issues/new?template=guide-request.yml) form.
- **PhotoCraft itself crashes or misbehaves:** report it to the [PhotoCraft issue tracker](https://github.com/storytold/photocraft/issues). The [troubleshooting guide](https://photocraft.im/guides/troubleshooting#logs-settings-and-reporting-a-bug) explains what to include.

## License

The text in this repository is licensed under [CC BY 4.0](LICENSE). PhotoCraft is © the ArtCraft team and licensed under MIT OR Apache-2.0; see [its repository](https://github.com/storytold/photocraft) for details.
