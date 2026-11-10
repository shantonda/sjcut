<p align="center">
  <img src="../assets/concat-mark-dark.png" alt="SJCut" width="180" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">CapCut کا مفت، اوپن سورس اور کراس پلیٹ فارم متبادل۔</h3>

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

[🇬🇧 English](../README.md) · [🇩🇪 Deutsch](README.de.md) · [🇪🇸 Español](README.es.md) · [🇫🇷 Français](README.fr.md) · [🇮🇹 Italiano](README.it.md) · [🇳🇱 Nederlands](README.nl.md) · [🇵🇱 Polski](README.pl.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · [🇷🇺 Русский](README.ru.md) · [🇺🇦 Українська](README.uk.md) · [🇹🇷 Türkçe](README.tr.md) · [🇦🇿 Azərbaycanca](README.az.md) · [🇭🇷 Hrvatski](README.hr.md) · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇻🇳 Tiếng Việt](README.vi.md) · [🇹🇭 ไทย](README.th.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇨🇳 简体中文](README.zh-Hans.md) · [🇹🇼 繁體中文](README.zh-TW.md) · [🇸🇦 العربية](README.ar.md) · [🇮🇱 עברית](README.he.md) · [🇮🇷 فارسی](README.fa.md) · [🇮🇳 हिन्दी](README.hi.md) · **🇵🇰 اردو** · [🇧🇩 বাংলা](README.bn.md)

> 28 اکتوبر 2026 کو انگریزی README سے ترجمہ کیا گیا۔ انگریزی نسخہ ہی تازہ رکھا جاتا ہے۔

</div>


## تعارف

SJCut ایک مفت، اوپن سورس ویڈیو ایڈیٹر اور macOS، Windows، Linux اور Android کے لیے CapCut کا متبادل ہے۔ یہ وہی سب کرتا ہے جس کے لیے لوگ اصل میں CapCut کھولتے ہیں: خودکار کیپشن، متن سے آواز، پس منظر ہٹانا، کی فریم اینیمیشن، ایفیکٹس اور ٹائٹل، ملٹی ٹریک کٹنگ، 4K ایکسپورٹ۔ اور کسی چالاکی کے بغیر: نہ واٹر مارک، نہ اکاؤنٹ، نہ سبسکرپشن، نہ اپ لوڈ۔

سب کچھ GPU کمپوزیٹر والے نیٹو Rust انجن پر مقامی طور پر چلتا ہے۔ انسٹال کریں، فوٹیج ڈالیں، کاٹیں۔ کیپشن، آوازوں اور کٹ آؤٹ کے AI ماڈل سیٹنگز سے ایک بار ڈاؤن لوڈ ہوتے ہیں اور اس کے بعد آف لائن کام کرتے ہیں۔ آپ کی فوٹیج کبھی آپ کی ڈسک سے باہر نہیں جاتی۔

**ان کے لیے موزوں:** TikTok، Reels اور Shorts، YouTube ویڈیوز، ٹیوٹوریل اور اسکرین ریکارڈنگ، پوڈکاسٹ کلپس، میمز۔

**مشینوں کے لیے بھی:** AI ایجنٹس کے لیے بلٹ ان MCP سرور (`concat --mcp`، [سیٹ اپ](MCP.md)) اور اسکرپٹس کے لیے ایک JSON-RPC API، تاکہ وہ بھی اس سے ویڈیو کاٹ سکیں۔

## نمایاں خصوصیات

- 🚫 **نہ واٹر مارک۔ نہ اکاؤنٹ۔ نہ پے وال۔** کبھی نہیں۔
- 🔒 **100 % مقامی۔** کچھ اپ لوڈ نہیں ہوتا۔ آف لائن کام کرتا ہے۔
- 💬 **خودکار کیپشن۔** مقامی Whisper۔ ماڈل کا سائز چنیں، ٹائم لائن پر اسٹائل شدہ کیپشن پائیں۔
- 🗣️ **متن سے آواز + آواز کی نقل۔** مفت مقامی آوازیں، یا چند سیکنڈ کی ریکارڈنگ سے کوئی بھی آواز۔
- 🧍 **پس منظر ہٹانا۔** لوگ، اشیا، یا ماسک خود پینٹ کریں۔
- 🎞️ **کی فریمز۔** پوزیشن، اسکیل، گردش، شفافیت، والیوم، ایفیکٹ پیرامیٹرز۔ کرو ایڈیٹر شامل۔
- ✨ **100 ایفیکٹس، فلٹرز اور ٹرانزیشنز۔** GPU سے رینڈر، پری ویو میں لائیو۔
- ✂️ **تیزی سے کاٹیں۔** اسپلٹ، ٹرم، رِپل، مرج، فریز فریم، اسپیڈ۔ چاہیں تو مقناطیسی ٹائم لائن۔
- 🎚️ **ملٹی ٹریک، ملٹی ٹائم لائن۔** اوورلیز اور پکچر ان پکچر: جتنی ٹریکس چاہیں، ویڈیو، تصاویر اور ٹائٹل ایک دوسرے پر رکھیں۔ ایک پراجیکٹ میں کئی کٹس۔ بلینڈ موڈز (اسکرین، ایڈ، ملٹی پلائی…)، کراپ، فلپس۔
- 📝 **ٹائٹل۔** فونٹس، اسٹروک، سایہ، پس منظر پلیٹ۔ شروعات کے لیے پری سیٹس۔
- 🎙️ **ایک سوئچ سے آواز کی صفائی۔** شور ہٹائیں، آواز نکھاریں، لاؤڈنیس برابر کریں۔ ساتھ میں چپمنک، روبوٹ، ٹیلی فون وغیرہ۔
- 📤 **ایکسپورٹ۔** H.264، HEVC، AV1۔ 4K 60 تک، 10 بٹ رنگ۔
- 🦀 **نیٹو Rust انجن۔** GPU کمپوزیٹر، پراکسیز، ہارڈویئر ڈی کوڈ۔ 4K آسانی سے اسکرب ہوتا ہے۔
- 🤖 **اسکرپٹ کے قابل۔** بلٹ ان MCP سرور، جس سے Claude اور دوسرے AI ایجنٹس اس سے ایڈٹ کر سکتے ہیں ([ایک لائن میں سیٹ اپ](MCP.md))، اور اسکرپٹس کے لیے ایک JSON-RPC API۔ سورس سے بلڈ کرنے پر gRPC اور ایک کمانڈ لائن ٹول بھی ملتا ہے۔
- 🖥️ **macOS، Windows، Linux، Android۔** 26 زبانیں۔ وہی ایپ، وہی پراجیکٹ فائلیں۔

## ڈاؤن لوڈ

دو راستے:

1. **[ویب سائٹ](https://github.com/shantonda/sjcut/releases)** آپ کی مشین کے لیے درست بلڈ دیتی ہے۔ یہیں سے شروع کریں۔
2. **[GitHub Releases](https://github.com/shantonda/sjcut/releases)** پر ہر پلیٹ فارم کی ہر بلڈ ہے، انسٹالرز، پیکجز اور چیک سمز کے ساتھ۔ جب آپ خود چننا چاہیں۔

SJCut **بیٹا** میں ہے: یہ کام کرتا ہے، اور ابھی اس میں کچھ کھردرا پن ہے۔ کوئی ملے تو [بتائیں](https://github.com/shantonda/sjcut/issues)۔

**پلیٹ فارمز**

- ✅ **Windows** · x86_64 (ARM بلڈز فی الحال روکی گئی ہیں، دیکھیں [#326](https://github.com/shantonda/sjcut/issues/326))۔ ایک سیٹ اپ اور ایک `.msi`۔ اگر SmartScreen غیر دستخط شدہ بلڈ روکے: **More info** › **Run anyway**
- ✅ **macOS** · Intel اور Apple Silicon۔ اگر macOS غیر دستخط شدہ بلڈ کھولنے سے انکار کرے: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 اور ARM۔ ‏`.deb`، `.rpm`، `.AppImage` اور ایک Arch پیکج۔ ساتھ ہی **[Flatpark](https://flatpark.org/apps/app.concat.editor/)** پر ایک Flatpak، جو ایک کمیونٹی Flatpak ریموٹ ہے اور ہر ریلیز کی x86_64 ‏`.deb` کو لپیٹ کر اس کے ساتھ اپ ڈیٹ ہوتا ہے
- ✅ **Android** · فون اور ٹیبلٹ
- ✅ **iOS / iPadOS** · iPhone اور iPad، سائیڈ لوڈ کے ذریعے

✅ معاون · 🚧 کام جاری · 🧪 آزمائش باقی

**سسٹم کی ضروریات** اور اختیاری ماڈلز کے سائز [ویب سائٹ](https://concat.standalones.org/guides/system-requirements) پر ہیں۔

**[Code signing policy](../CODE_SIGNING.md)**

## حصہ کیسے ڈالیں

> [!IMPORTANT]
> حصہ ڈالنے کا بہترین طریقہ یہ ہے کہ [Releases](https://github.com/shantonda/sjcut/releases) صفحے سے ایک بلڈ لیں اور اسے استعمال کریں: معلوم کریں کہاں ٹوٹتا ہے، اور بتائیں کہاں بہتر ہو سکتا ہے۔
>
> کوڈ لکھنے کو تیار ہیں؟ [CONTRIBUTING.md](../CONTRIBUTING.md) میں سیٹ اپ، ٹری کی ترتیب، چلائی جانے والی جانچیں اور شراکتوں کے لائسنس کی تفصیل ہے۔ کسی اسکرپٹ، سروس یا ایجنٹ سے SJCut چلا رہے ہیں؟ [ڈویلپر دستاویزات](https://concat.standalones.org/docs) میں SJCut API اور اس کے ٹرانسپورٹس ہیں: JSON-RPC اور gRPC۔ پراجیکٹ کا اعلان [اس Discussion](https://github.com/shantonda/sjcut/discussions/3) میں ہوا تھا۔
> 
> شراکت دار Discord سرور پر `@Contributor` رول لے سکتے ہیں: بس مانگ لیں۔

## اسٹار کی تاریخ

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## شراکت دار

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

