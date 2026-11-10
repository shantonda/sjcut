<p align="center">
  <img src="https://raw.githubusercontent.com/shantonda/sjcut/main/assets/concat-mark-dark.png" alt="SJCut" width="100" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">Безкоштовна кросплатформна заміна CapCut з відкритим кодом.</h3>

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

[🇬🇧 English](../README.md) · [🇩🇪 Deutsch](README.de.md) · [🇪🇸 Español](README.es.md) · [🇫🇷 Français](README.fr.md) · [🇮🇹 Italiano](README.it.md) · [🇳🇱 Nederlands](README.nl.md) · [🇵🇱 Polski](README.pl.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · [🇷🇺 Русский](README.ru.md) · **🇺🇦 Українська** · [🇹🇷 Türkçe](README.tr.md) · [🇦🇿 Azərbaycanca](README.az.md) · [🇭🇷 Hrvatski](README.hr.md) · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇻🇳 Tiếng Việt](README.vi.md) · [🇹🇭 ไทย](README.th.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇨🇳 简体中文](README.zh-Hans.md) · [🇹🇼 繁體中文](README.zh-TW.md) · [🇸🇦 العربية](README.ar.md) · [🇮🇱 עברית](README.he.md) · [🇮🇷 فارسی](README.fa.md) · [🇮🇳 हिन्दी](README.hi.md) · [🇵🇰 اردو](README.ur.md) · [🇧🇩 বাংলা](README.bn.md)

> Перекладено з англійського README 11 жовтня 2026 року. Актуальною підтримується англійська версія.

</div>


## Про проєкт

SJCut є безкоштовним відеоредактором з відкритим кодом і альтернативою CapCut для macOS, Windows, Linux та Android. Він уміє те, заради чого люди насправді відкривають CapCut: автоматичні субтитри, синтез мовлення, видалення фону, анімацію за ключовими кадрами, ефекти й титри, багатодоріжковий монтаж, експорт у 4K. І без пасток: ані водяного знака, ані облікового запису, ані підписки, ані завантаження на сервер.

Усе працює локально на нативному рушії на Rust із GPU-композитором. Встановіть, перетягніть матеріал, ріжте. Моделі ШІ для субтитрів, голосів і вирізання фону завантажуються один раз із налаштувань і далі працюють офлайн. Ваш матеріал ніколи не залишає ваш диск.

**Підходить для:** TikTok, Reels і Shorts, відео на YouTube, навчальних роликів і записів екрана, фрагментів подкастів, мемів.

**І для машин теж:** API JSON-RPC, щоб скрипти та ШІ-агенти теж могли монтувати в ньому відео.

## Головне

- 🚫 **Без водяних знаків. Без облікового запису. Без платного доступу.** Ніколи.
- 🔒 **100 % локально.** Нічого не завантажується. Працює офлайн.
- 💬 **Автоматичні субтитри.** Локальний Whisper. Оберіть розмір моделі, і стилізовані субтитри опиняться на таймлайні.
- 🗣️ **Синтез мовлення + клонування голосу.** Безкоштовні локальні голоси або будь-який голос із кількох секунд запису.
- 🧍 **Видалення фону.** Люди, об’єкти або намалюйте маску самі.
- 🎞️ **Ключові кадри.** Положення, масштаб, поворот, прозорість, гучність, параметри ефектів. Вбудований редактор кривих.
- ✨ **100 ефектів, фільтрів і переходів.** Рендер на GPU, наживо в попередньому перегляді.
- ✂️ **Швидкий монтаж.** Розрізати, підрізати, ripple, об’єднати, стоп-кадр, швидкість. Магнітний таймлайн за бажанням.
- 🎚️ **Багато доріжок, багато таймлайнів.** Кілька монтажів в одному проєкті. Режими накладання, кадрування, віддзеркалення.
- 📝 **Титри.** Шрифти, обведення, тінь, підкладка. Пресети для старту.
- 🎙️ **Чищення голосу одним перемикачем.** Шумозаглушення, покращення голосу, вирівнювання гучності. Плюс бурундук, робот, телефон і компанія.
- 📤 **Експорт.** H.264, HEVC, AV1. До 4K 60, 10-бітний колір.
- 🦀 **Нативний рушій на Rust.** GPU-композитор, проксі, апаратне декодування. 4K перемотується плавно.
- 🤖 **Скриптований.** API JSON-RPC, через який скрипти та ШІ-агенти можуть монтувати відео. Збірка з вихідного коду додає gRPC та інструмент командного рядка.
- 🖥️ **macOS, Windows, Linux, Android.** 26 мов. Один застосунок, ті самі файли проєктів.

## Завантажити

Два шляхи:

1. **[Сайт](https://github.com/shantonda/sjcut/releases)** добере збірку під вашу машину. Почніть звідси.
2. **[GitHub Releases](https://github.com/shantonda/sjcut/releases)** містить кожну збірку для кожної платформи, з інсталяторами, пакетами й контрольними сумами. Коли хочеться обрати самому.

SJCut у **беті**: він працює, але шорсткості ще є. [Повідомте](https://github.com/shantonda/sjcut/issues), якщо знайдете.

**Платформи**

- ✅ **Windows** · x86_64 (збірки для ARM призупинено, див. [#326](https://github.com/shantonda/sjcut/issues/326)). Інсталятор і `.msi`. Якщо SmartScreen зупиняє непідписану збірку: **Докладніше** › **Все одно запустити**
- ✅ **macOS** · Intel і Apple Silicon. Якщо macOS відмовляється відкрити непідписану збірку: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 і ARM. `.deb`, `.rpm`, `.AppImage` і пакет для Arch. А ще Flatpak на **[Flatpark](https://flatpark.org/apps/app.concat.editor/)**, спільнотному Flatpak-репозиторії, який обгортає `.deb` x86_64 кожного релізу й оновлюється разом із ним
- ✅ **Android** · телефони та планшети
- ✅ **iOS / iPadOS** · iPhone та iPad, через sideload

✅ Підтримується · 🚧 У роботі · 🧪 Треба перевірити

**Системні вимоги** та розміри необов’язкових моделей наведено на [сайті](https://concat.standalones.org/guides/system-requirements).

**[Code signing policy](../CODE_SIGNING.md)**

## Як долучитися

> [!IMPORTANT]
> Найкраще ви допоможете, якщо візьмете збірку зі сторінки [Releases](https://github.com/shantonda/sjcut/releases) і користуватиметеся нею: знайдете, де вона ламається, і скажете, де вона могла б бути кращою.
>
> Готові писати код? У [CONTRIBUTING.md](../CONTRIBUTING.md) описано налаштування, будову дерева, які перевірки запускати та як ліцензуються внески. Керуєте SJCut зі скрипту, сервісу чи агента? [Документація для розробників](https://concat.standalones.org/docs) описує API SJCut та його транспорти: JSON-RPC і gRPC. [У цьому обговоренні](https://github.com/shantonda/sjcut/discussions/3) проєкт було анонсовано.
> 
> Учасники можуть отримати роль `@Contributor` на сервері Discord: достатньо попросити.

## Історія зірок

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## Учасники

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

