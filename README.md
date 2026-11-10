<p align="center">
  <img src="https://raw.githubusercontent.com/shantonda/sjcut/main/assets/concat-mark-dark.png" alt="SJCut" width="100" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">The free, open-source, cross-platform CapCut replacement.</h3>

<div align="center">

<img src="https://raw.githubusercontent.com/shantonda/sjcut/main/assets/editor.png" alt="SJCut editor" width="100%" />

<p align="center">
  <a href="https://github.com/shantonda/sjcut/releases"><img src="https://img.shields.io/github/downloads/shantonda/sjcut/total?style=flat&logo=github&logoColor=F8F8F8&label=Downloads&labelColor=212123&color=0568FD" alt="Total Downloads" /></a>
  <a href="https://github.com/shantonda/sjcut/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/shantonda/sjcut/ci.yml?style=flat&logo=githubactions&logoColor=F8F8F8&label=Build&labelColor=000000" alt="Build Status" /></a>
  <a href="https://github.com/shantonda/sjcut/releases"><img src="https://img.shields.io/badge/Version-0.2.9-0568FD?style=flat&logo=semver&logoColor=F8F8F8&labelColor=212123" alt="SJCut Version 0.2.9" /></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-0568FD?style=flat&logo=gnu&logoColor=F8F8F8&labelColor=212123" alt="License: AGPL-3.0-or-later" /></a>
</p>

<p align="center">
  <a href="https://www.star-history.com/shantonda/sjcut"><img src="https://api.star-history.com/badge?repo=shantonda/sjcut&type=rank" alt="Star History Rank" height="62" /></a>
  <a href="https://github.com/shantonda/sjcut/releases"><img src="assets/download_button.svg" alt="Download SJCut" width="251" /></a>
</p>

**🇬🇧 English** · [🇩🇪 Deutsch](docs/README.de.md) · [🇪🇸 Español](docs/README.es.md) · [🇫🇷 Français](docs/README.fr.md) · [🇮🇹 Italiano](docs/README.it.md) · [🇳🇱 Nederlands](docs/README.nl.md) · [🇵🇱 Polski](docs/README.pl.md) · [🇧🇷 Português (Brasil)](docs/README.pt-BR.md) · [🇷🇺 Русский](docs/README.ru.md) · [🇺🇦 Українська](docs/README.uk.md) · [🇹🇷 Türkçe](docs/README.tr.md) · [🇦🇿 Azərbaycanca](docs/README.az.md) · [🇭🇷 Hrvatski](docs/README.hr.md) · [🇮🇩 Bahasa Indonesia](docs/README.id.md) · [🇻🇳 Tiếng Việt](docs/README.vi.md) · [🇹🇭 ไทย](docs/README.th.md) · [🇯🇵 日本語](docs/README.ja.md) · [🇰🇷 한국어](docs/README.ko.md) · [🇨🇳 简体中文](docs/README.zh-Hans.md) · [🇹🇼 繁體中文](docs/README.zh-TW.md) · [🇸🇦 العربية](docs/README.ar.md) · [🇮🇱 עברית](docs/README.he.md) · [🇮🇷 فارسی](docs/README.fa.md) · [🇮🇳 हिन्दी](docs/README.hi.md) · [🇵🇰 اردو](docs/README.ur.md) · [🇧🇩 বাংলা](docs/README.bn.md)

</div>


## About

SJCut is a free, open-source video editor and a CapCut alternative for macOS, Windows, Linux and Android. It covers what people actually open CapCut for: auto-captions, text-to-speech, background removal, keyframe animation, effects and titles, multi-track cutting, 4K export. With none of the catches: no watermark, no account, no subscription, no upload.

Everything runs locally on a native Rust engine with a GPU compositor. Install it, drop in footage, cut. The AI models for captions, voices and cutout download once from Settings and work offline after that. Your footage never leaves your disk.

**Good for:** TikTok, Reels and Shorts, YouTube videos, tutorials and screen recordings, podcast clips, memes.

**Also for machines:** a built-in MCP server for AI agents (`concat --mcp`, [set up](docs/MCP.md)) and a JSON-RPC API for scripts, so they can cut video with it too.

## Highlights

- 🚫 **No watermarks. No account. No paywall.** Ever.
- 🔒 **100% local.** Nothing uploads. Works offline.
- 💬 **Auto-captions.** Local Whisper. Pick a model size, get styled captions on the timeline.
- 🗣️ **Text-to-speech + voice cloning.** A free local voice on the desktop, or any voice from a few seconds of a recording. Phones are getting their own system voice.
- 🧍 **Background removal.** People, objects, or paint the mask yourself.
- 🎞️ **Keyframes.** Position, scale, rotation, opacity, volume, effect parameters. Curve editor built in.
- ✨ **100 effects, filters and transitions.** GPU-rendered, live in the preview.
- ✂️ **Cut fast.** Split, trim, ripple, merge, freeze frame, speed. Magnetic timeline if you want it.
- 🎚️ **Multi-track, multi-timeline.** Overlays and picture-in-picture: stack video, stills and titles on as many tracks as you like. Several cuts in one project. Blend modes (screen, add, multiply…), crop, flips.
- 📝 **Titles.** Fonts, stroke, shadow, background plate. Presets to start from.
- 🎙️ **One-switch voice cleanup.** Denoise, enhance voice, level the loudness. Plus chipmunk, robot, telephone and friends.
- 📤 **Export.** H.264, HEVC, AV1. Up to 4K 60, 10-bit colour.
- 🦀 **Native Rust engine.** GPU compositor, proxies, hardware decode. 4K scrubs smoothly.
- 🤖 **Scriptable.** An MCP server built in, so Claude and other AI agents can edit with it ([one line to set up](docs/MCP.md)), and a JSON-RPC API for scripts. A build from source adds gRPC and a command-line tool.
- 🖥️ **macOS, Windows, Linux, Android.** 26 languages. Same app, same project files.

## Download

**[GitHub Releases](https://github.com/shantonda/sjcut/releases)** has every build for every platform, with installers, packages and checksums.

SJCut is in **beta**: it works, and it still has edges. [Say so](https://github.com/shantonda/sjcut/issues) when you find one.

**Platforms**

- ✅ **Windows** · x86_64. A setup (`SJCut-0.2.9-windows-x86_64-setup.exe`) and an `.msi` (`SJCut-0.2.9-windows-x86_64.msi`). If SmartScreen stops an unsigned build: **More info** › **Run anyway**
- ✅ **macOS** · Intel and Apple silicon. If macOS refuses to open an unsigned build: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 and ARM. `.deb`, `.rpm`, `.AppImage` and an Arch package.
- ✅ **Android** · phones and tablets
- ✅ **iOS / iPadOS** · iPhone and iPad, sideloaded

✅ Supported · 🚧 Work in progress · 🧪 To be tested

**[Code signing policy](CODE_SIGNING.md)**: why the Windows builds are not signed yet, and what SJCut sends over the network (nothing you did not ask for).

## Build from source

You need Rust 1.93 or newer (see `rust-version` in `src/Cargo.toml`), the FFmpeg 7+ development libraries, cmake and a C++ compiler.

- **macOS:** `brew install ffmpeg`
- **Windows:** from [FFmpeg's Windows downloads](https://ffmpeg.org/download.html#build-windows), take BtbN's `win64-gpl-shared` build (the one CI uses), unpack it and point `FFMPEG_DIR` at it
- **Linux:** use your distro's FFmpeg if it is version 7 or newer, otherwise use a BtbN `shared` build with `FFMPEG_DIR` like on Windows

Then:

```sh
cd src
cargo run -p concat          # the editor window
```

Other useful commands:

```sh
cargo build --profile app -p concat   # the shipping binary (fat LTO, stripped)
cargo test                            # run the test suite
cargo fmt --check && cargo clippy --all-targets -- -D warnings   # what CI checks
```

If you change text the interface shows, run `python3 scripts/locales.py` from the repo root so the string inventory stays in sync. Full details live in [CONTRIBUTING.md](CONTRIBUTING.md).

## How to Contribute

> [!IMPORTANT]
> The best way to contribute is to grab a build from the [Releases](https://github.com/shantonda/sjcut/releases) page and use it: find where it breaks, and say where it could be better.
>
> Ready to write code? [CONTRIBUTING.md](./CONTRIBUTING.md) covers setup, the layout of the tree, the checks to run, and how contributions are licensed. Driving SJCut from a script, a service or an agent? [docs/MCP.md](docs/MCP.md) connects an AI agent over MCP.

## Star History

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## Contributors

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

## Licence

SJCut is free software under [AGPL-3.0-or-later](LICENSE). See [LICENSING.md](LICENSING.md).
