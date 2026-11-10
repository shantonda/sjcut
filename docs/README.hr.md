<p align="center">
  <img src="https://raw.githubusercontent.com/shantonda/sjcut/main/assets/concat-mark-dark.png" alt="SJCut" width="100" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">Besplatna zamjena za CapCut otvorenog koda, za sve platforme.</h3>

<div align="center">

<img src="https://raw.githubusercontent.com/shantonda/sjcut/main/assets/editor.png" alt="SJCut editor" width="100%" />

<p align="center">
  <a href="https://github.com/shantonda/sjcut/releases"><img src="https://img.shields.io/github/downloads/shantonda/sjcut/total?style=flat&logo=github&logoColor=F8F8F8&label=Downloads&labelColor=212123&color=0568FD" alt="Total Downloads" /></a>
  <a href="https://github.com/shantonda/sjcut/actions/workflows/ci.yml"><img src="https://img.shields.io/github/actions/workflow/status/shantonda/sjcut/ci.yml?style=flat&logo=githubactions&logoColor=F8F8F8&label=Build&labelColor=000000" alt="Build Status" /></a>
  <a href="https://github.com/shantonda/sjcut/releases"><img src="https://img.shields.io/badge/Version-0.2.9-0568FD?style=flat&logo=semver&logoColor=F8F8F8&labelColor=212123" alt="SJCut Version 0.2.9" /></a>
  <a href="../LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-0568FD?style=flat&logo=gnu&logoColor=F8F8F8&labelColor=212123" alt="License: AGPL-3.0-or-later" /></a>
</p>

<p align="center">
  <a href="https://www.star-history.com/shantonda/sjcut"><img src="https://api.star-history.com/badge?repo=shantonda/sjcut&type=rank" alt="Star History Rank" height="62" /></a>
  <a href="https://github.com/shantonda/sjcut/releases"><img src="../assets/download_button.svg" alt="Download SJCut" width="251" /></a>
</p>

[🇬🇧 English](../README.md) · [🇩🇪 Deutsch](README.de.md) · [🇪🇸 Español](README.es.md) · [🇫🇷 Français](README.fr.md) · [🇮🇹 Italiano](README.it.md) · [🇳🇱 Nederlands](README.nl.md) · [🇵🇱 Polski](README.pl.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · [🇷🇺 Русский](README.ru.md) · [🇺🇦 Українська](README.uk.md) · [🇹🇷 Türkçe](README.tr.md) · [🇦🇿 Azərbaycanca](README.az.md) · **🇭🇷 Hrvatski** · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇻🇳 Tiếng Việt](README.vi.md) · [🇹🇭 ไทย](README.th.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇨🇳 简体中文](README.zh-Hans.md) · [🇹🇼 繁體中文](README.zh-TW.md) · [🇸🇦 العربية](README.ar.md) · [🇮🇱 עברית](README.he.md) · [🇮🇷 فارسی](README.fa.md) · [🇮🇳 हिन्दी](README.hi.md) · [🇵🇰 اردو](README.ur.md) · [🇧🇩 বাংলা](README.bn.md)

> Prevedeno s engleskog README-a 11. listopada 2026. Engleska je verzija ona koja se održava ažurnom.

</div>


## O projektu

SJCut je besplatan videouređivač otvorenog koda i alternativa CapCutu za macOS, Windows, Linux i Android. Pokriva ono zbog čega ljudi zapravo otvaraju CapCut: automatske titlove, pretvorbu teksta u govor, uklanjanje pozadine, animaciju ključnim kadrovima, efekte i naslove, višetračno rezanje, izvoz u 4K. Bez ikakvih kvaka: bez vodenog žiga, bez računa, bez pretplate, bez učitavanja.

Sve se izvodi lokalno na nativnom Rust motoru s GPU kompozitorom. Instalirajte, ubacite snimke, režite. AI modeli za titlove, glasove i izrezivanje preuzimaju se jednom iz Postavki i nakon toga rade izvan mreže. Vaše snimke nikada ne napuštaju vaš disk.

**Dobro za:** TikTok, Reels i Shorts, YouTube videe, tutorijale i snimke zaslona, isječke podcasta, memeove.

**I za strojeve:** JSON-RPC API, pa skripte i AI agenti također mogu njime rezati video.

## Istaknuto

- 🚫 **Bez vodenih žigova. Bez računa. Bez naplate.** Nikad.
- 🔒 **100 % lokalno.** Ništa se ne učitava. Radi izvan mreže.
- 💬 **Automatski titlovi.** Lokalni Whisper. Odaberite veličinu modela i dobit ćete stilizirane titlove na vremenskoj crti.
- 🗣️ **Tekst u govor + kloniranje glasa.** Besplatni lokalni glasovi ili bilo koji glas iz nekoliko sekundi snimke.
- 🧍 **Uklanjanje pozadine.** Osobe, predmeti ili sami nacrtajte masku.
- 🎞️ **Ključni kadrovi.** Položaj, skala, rotacija, prozirnost, glasnoća, parametri efekata. Ugrađeni uređivač krivulja.
- ✨ **100 efekata, filtara i prijelaza.** Iscrtano na GPU-u, uživo u pregledu.
- ✂️ **Brzo rezanje.** Podijeli, skrati, ripple, spoji, zamrzni kadar, brzina. Magnetska vremenska crta ako je želite.
- 🎚️ **Više traka, više vremenskih crta.** Više montaža u jednom projektu. Načini stapanja, obrezivanje, zrcaljenja.
- 📝 **Naslovi.** Fontovi, obrub, sjena, pozadinska pločica. Predlošci za početak.
- 🎙️ **Čišćenje glasa jednim prekidačem.** Uklanjanje šuma, poboljšanje glasa, izjednačavanje glasnoće. Plus vjeverica, robot, telefon i društvo.
- 📤 **Izvoz.** H.264, HEVC, AV1. Do 4K 60, 10-bitna boja.
- 🦀 **Nativni Rust motor.** GPU kompozitor, proxyji, hardversko dekodiranje. 4K se pregledava glatko.
- 🤖 **Skriptabilan.** JSON-RPC API kojim skripte i AI agenti mogu rezati video. Inačica izgrađena iz izvornog koda dodaje gRPC i alat za naredbeni redak.
- 🖥️ **macOS, Windows, Linux, Android.** 26 jezika. Ista aplikacija, iste datoteke projekta.

## Preuzimanje

Dva ulaza:

1. **[Web-stranica](https://github.com/shantonda/sjcut/releases)** daje vam pravu inačicu za vaše računalo. Počnite ovdje.
2. **[GitHub Releases](https://github.com/shantonda/sjcut/releases)** ima svaku inačicu za svaku platformu, s instalacijama, paketima i kontrolnim zbrojevima. Za kad želite birati.

SJCut je u **beti**: radi, a još ima rubova. [Javite](https://github.com/shantonda/sjcut/issues) kad naiđete na jedan.

**Platforme**

- ✅ **Windows** · x86_64 (ARM inačice su pauzirane, vidi [#326](https://github.com/shantonda/sjcut/issues/326)). Instalacija i `.msi`. Ako SmartScreen zaustavi nepotpisanu inačicu: **Više informacija** › **Svejedno pokreni**
- ✅ **macOS** · Intel i Apple Silicon. Ako macOS odbije otvoriti nepotpisanu inačicu: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 i ARM. `.deb`, `.rpm`, `.AppImage` i Arch paket. Također Flatpak na **[Flatparku](https://flatpark.org/apps/app.concat.editor/)**, Flatpak repozitoriju zajednice koji omata x86_64 `.deb` svakog izdanja i ažurira se s njim
- ✅ **Android** · telefoni i tableti
- ✅ **iOS / iPadOS** · iPhone i iPad, sideloadom

✅ Podržano · 🚧 U izradi · 🧪 Za testiranje

**Zahtjevi sustava** i veličine neobaveznih modela nalaze se na [web-stranici](https://concat.standalones.org/guides/system-requirements).

**[Code signing policy](../CODE_SIGNING.md)**

## Kako doprinijeti

> [!IMPORTANT]
> Najbolji način doprinosa jest uzeti inačicu sa stranice [Releases](https://github.com/shantonda/sjcut/releases) i koristiti je: pronaći gdje puca i reći gdje bi mogla biti bolja.
>
> Spremni pisati kod? [CONTRIBUTING.md](../CONTRIBUTING.md) pokriva postavljanje, raspored stabla, provjere koje treba pokrenuti i kako se doprinosi licenciraju. Upravljate SJCutom iz skripte, servisa ili agenta? [Dokumentacija za razvojne programere](https://concat.standalones.org/docs) pokriva SJCut API i njegove prijenose: JSON-RPC i gRPC. [U ovoj raspravi](https://github.com/shantonda/sjcut/discussions/3) projekt je najavljen.
> 
> Suradnici mogu zatražiti ulogu `@Contributor` na Discord poslužitelju: samo pitajte.

## Povijest zvjezdica

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## Suradnici

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

