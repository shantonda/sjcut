<p align="center">
  <img src="../assets/concat-mark-dark.png" alt="SJCut" width="180" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">Бесплатная кроссплатформенная замена CapCut с открытым исходным кодом.</h3>

<div align="center">

<img src="../assets/editor.png" alt="SJCut editor" width="100%" />

<p align="center">
  <a href="https://github.com/shantonda/sjcut/releases"><img src="https://img.shields.io/badge/Version-0.2.9-0568FD?style=flat&logo=semver&logoColor=F8F8F8&labelColor=212123" alt="SJCut Version 0.2.9" /></a>
  <a href="https://github.com/shantonda/sjcut"><img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux%20%7C%20Android-0568FD?style=flat&logo=rust&logoColor=F8F8F8&labelColor=212123" alt="Platforms" /></a>
  <a href="../LICENSE"><img src="https://img.shields.io/badge/License-AGPL%20v3-0568FD?style=flat&logo=gnu&logoColor=F8F8F8&labelColor=212123" alt="License: AGPL-3.0-or-later" /></a>
</p>

<p align="center">
  <a href="https://github.com/shantonda/sjcut/releases"><img src="../assets/download_button.svg" alt="Download SJCut" width="251" /></a>
</p>

[🇬🇧 English](../README.md) · [🇩🇪 Deutsch](README.de.md) · [🇪🇸 Español](README.es.md) · [🇫🇷 Français](README.fr.md) · [🇮🇹 Italiano](README.it.md) · [🇳🇱 Nederlands](README.nl.md) · [🇵🇱 Polski](README.pl.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · **🇷🇺 Русский** · [🇺🇦 Українська](README.uk.md) · [🇹🇷 Türkçe](README.tr.md) · [🇦🇿 Azərbaycanca](README.az.md) · [🇭🇷 Hrvatski](README.hr.md) · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇻🇳 Tiếng Việt](README.vi.md) · [🇹🇭 ไทย](README.th.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇨🇳 简体中文](README.zh-Hans.md) · [🇹🇼 繁體中文](README.zh-TW.md) · [🇸🇦 العربية](README.ar.md) · [🇮🇱 עברית](README.he.md) · [🇮🇷 فارسی](README.fa.md) · [🇮🇳 हिन्दी](README.hi.md) · [🇵🇰 اردو](README.ur.md) · [🇧🇩 বাংলা](README.bn.md)

> Переведено с английского README 11 октября 2026 года. Актуальной поддерживается английская версия.

</div>


## О проекте

SJCut является бесплатным видеоредактором с открытым исходным кодом и альтернативой CapCut для macOS, Windows, Linux и Android. Он умеет то, ради чего люди на самом деле открывают CapCut: автоматические субтитры, синтез речи, удаление фона, анимацию по ключевым кадрам, эффекты и титры, многодорожечный монтаж, экспорт в 4K. И без подвохов: ни водяного знака, ни аккаунта, ни подписки, ни загрузки на сервер.

Всё работает локально на нативном движке на Rust с GPU-композитором. Установите, перетащите материал, режьте. Модели ИИ для субтитров, голосов и вырезания фона скачиваются один раз из настроек и дальше работают офлайн. Ваш материал никогда не покидает ваш диск.

**Подходит для:** TikTok, Reels и Shorts, видео на YouTube, обучающих роликов и записей экрана, фрагментов подкастов, мемов.

**И для машин тоже:** API JSON-RPC, чтобы скрипты и ИИ-агенты тоже могли монтировать в нём видео.

## Главное

- 🚫 **Без водяных знаков. Без аккаунта. Без платного доступа.** Никогда.
- 🔒 **100 % локально.** Ничего не загружается. Работает офлайн.
- 💬 **Автоматические субтитры.** Локальный Whisper. Выберите размер модели, и стилизованные субтитры окажутся на таймлайне.
- 🗣️ **Синтез речи + клонирование голоса.** Бесплатные локальные голоса или любой голос по нескольким секундам записи.
- 🧍 **Удаление фона.** Люди, объекты или нарисуйте маску сами.
- 🎞️ **Ключевые кадры.** Положение, масштаб, поворот, прозрачность, громкость, параметры эффектов. Встроенный редактор кривых.
- ✨ **100 эффектов, фильтров и переходов.** Рендер на GPU, вживую в предпросмотре.
- ✂️ **Быстрый монтаж.** Разрезать, подрезать, ripple, объединить, стоп-кадр, скорость. Магнитный таймлайн по желанию.
- 🎚️ **Много дорожек, много таймлайнов.** Несколько монтажей в одном проекте. Режимы наложения, кадрирование, отражения.
- 📝 **Титры.** Шрифты, обводка, тень, подложка. Пресеты для старта.
- 🎙️ **Чистка голоса одним переключателем.** Шумоподавление, улучшение голоса, выравнивание громкости. Плюс бурундук, робот, телефон и компания.
- 📤 **Экспорт.** H.264, HEVC, AV1. До 4K 60, 10-битный цвет.
- 🦀 **Нативный движок на Rust.** GPU-композитор, прокси, аппаратное декодирование. 4K перематывается плавно.
- 🤖 **Скриптуемый.** API JSON-RPC, через который скрипты и ИИ-агенты могут монтировать видео. Сборка из исходников добавляет gRPC и инструмент командной строки.
- 🖥️ **macOS, Windows, Linux, Android.** 26 языков. Одно приложение, одни и те же файлы проектов.

## Скачать

Два пути:

1. **[Сайт](https://github.com/shantonda/sjcut/releases)** подберёт сборку под вашу машину. Начните отсюда.
2. **[GitHub Releases](https://github.com/shantonda/sjcut/releases)** содержит каждую сборку для каждой платформы, с установщиками, пакетами и контрольными суммами. Когда хочется выбрать самому.

SJCut в **бете**: он работает, но шероховатости ещё есть. [Сообщите](https://github.com/shantonda/sjcut/issues), если найдёте.

**Платформы**

- ✅ **Windows** · x86_64 (сборки для ARM приостановлены, см. [#326](https://github.com/shantonda/sjcut/issues/326)). Установщик и `.msi`. Если SmartScreen останавливает неподписанную сборку: **Подробнее** › **Выполнить в любом случае**
- ✅ **macOS** · Intel и Apple Silicon. Если macOS отказывается открыть неподписанную сборку: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 и ARM. `.deb`, `.rpm`, `.AppImage` и пакет для Arch. А ещё Flatpak на **[Flatpark](https://flatpark.org/apps/app.concat.editor/)**, поддерживаемом сообществом Flatpak-репозитории, который оборачивает `.deb` x86_64 каждого релиза и обновляется вместе с ним
- ✅ **Android** · телефоны и планшеты
- ✅ **iOS / iPadOS** · iPhone и iPad, через sideload

✅ Поддерживается · 🚧 В работе · 🧪 Предстоит проверить

**Системные требования** и размеры необязательных моделей указаны на [сайте](https://concat.standalones.org/guides/system-requirements).

**[Code signing policy](../CODE_SIGNING.md)**

## Как помочь

> [!IMPORTANT]
> Лучше всего вы поможете, если возьмёте сборку со страницы [Releases](https://github.com/shantonda/sjcut/releases) и будете ею пользоваться: найдёте, где она ломается, и скажете, где она могла бы быть лучше.
>
> Готовы писать код? В [CONTRIBUTING.md](../CONTRIBUTING.md) описаны настройка, устройство дерева, какие проверки запускать и как лицензируются вклады. Управляете SJCut из скрипта, сервиса или агента? [Документация для разработчиков](https://concat.standalones.org/docs) описывает API SJCut и его транспорты: JSON-RPC и gRPC. [В этом обсуждении](https://github.com/shantonda/sjcut/discussions/3) проект был анонсирован.
> 
> Участники могут получить роль `@Contributor` на сервере Discord: достаточно попросить.

## История звёзд

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## Участники

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

