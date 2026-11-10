<p align="center">
  <img src="../assets/concat-mark-dark.png" alt="SJCut" width="180" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">התחליף החינמי, בקוד פתוח וחוצה פלטפורמות ל-CapCut.</h3>

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

[🇬🇧 English](../README.md) · [🇩🇪 Deutsch](README.de.md) · [🇪🇸 Español](README.es.md) · [🇫🇷 Français](README.fr.md) · [🇮🇹 Italiano](README.it.md) · [🇳🇱 Nederlands](README.nl.md) · [🇵🇱 Polski](README.pl.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · [🇷🇺 Русский](README.ru.md) · [🇺🇦 Українська](README.uk.md) · [🇹🇷 Türkçe](README.tr.md) · [🇦🇿 Azərbaycanca](README.az.md) · [🇭🇷 Hrvatski](README.hr.md) · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇻🇳 Tiếng Việt](README.vi.md) · [🇹🇭 ไทย](README.th.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇨🇳 简体中文](README.zh-Hans.md) · [🇹🇼 繁體中文](README.zh-TW.md) · [🇸🇦 العربية](README.ar.md) · **🇮🇱 עברית** · [🇮🇷 فارسی](README.fa.md) · [🇮🇳 हिन्दी](README.hi.md) · [🇵🇰 اردو](README.ur.md) · [🇧🇩 বাংলা](README.bn.md)

> תורגם מה-README האנגלי ב-11 באוקטובר 2026. הגרסה האנגלית היא זו שמתעדכנת.

</div>


## אודות

SJCut הוא עורך וידאו חינמי בקוד פתוח וחלופה ל-CapCut עבור macOS, Windows, Linux ו-Android. הוא מכסה את מה שאנשים באמת פותחים בשבילו את CapCut: כתוביות אוטומטיות, טקסט לדיבור, הסרת רקע, אנימציית פריימי מפתח, אפקטים וכותרות, עריכה מרובת רצועות, ייצוא ב-4K. ובלי שום מלכודות: בלי סימן מים, בלי חשבון, בלי מנוי, בלי העלאה.

הכול רץ מקומית על מנוע Rust נייטיב עם קומפוזיטור GPU. מתקינים, גוררים חומר, חותכים. מודלי ה-AI לכתוביות, לקולות ולחיתוך רקע יורדים פעם אחת מההגדרות ואחר כך עובדים במצב לא מקוון. החומר שלכם לעולם לא עוזב את הדיסק.

**מתאים ל:** TikTok, Reels ו-Shorts, סרטוני YouTube, מדריכים והקלטות מסך, קטעי פודקאסט, ממים.

**וגם למכונות:** API של JSON-RPC, כך שגם סקריפטים וסוכני AI יכולים לערוך איתו וידאו.

## עיקרי הדברים

- 🚫 **בלי סימני מים. בלי חשבון. בלי חומת תשלום.** לעולם.
- 🔒 **100 % מקומי.** שום דבר לא עולה. עובד בלי אינטרנט.
- 💬 **כתוביות אוטומטיות.** Whisper מקומי. בוחרים גודל מודל ומקבלים כתוביות מעוצבות על ציר הזמן.
- 🗣️ **טקסט לדיבור + שיבוט קול.** קולות מקומיים בחינם, או כל קול מתוך כמה שניות של הקלטה.
- 🧍 **הסרת רקע.** אנשים, עצמים, או ציירו את המסכה בעצמכם.
- 🎞️ **פריימי מפתח.** מיקום, קנה מידה, סיבוב, אטימות, עוצמה, פרמטרים של אפקטים. עורך עקומות מובנה.
- ✨ **100 אפקטים, פילטרים ומעברים.** מרונדרים ב-GPU, חיים בתצוגה המקדימה.
- ✂️ **חותכים מהר.** פיצול, קיצוץ, ripple, מיזוג, הקפאת פריים, מהירות. ציר זמן מגנטי אם רוצים.
- 🎚️ **רב-רצועתי, רב-ציר זמן.** כמה עריכות בפרויקט אחד. מצבי מיזוג, חיתוך, היפוכים.
- 📝 **כותרות.** גופנים, קו מתאר, צל, לוח רקע. הגדרות מוכנות להתחיל מהן.
- 🎙️ **ניקוי קול במתג אחד.** הפחתת רעש, חיזוק הקול, איזון עוצמה. ועוד סנאי, רובוט, טלפון וחברים.
- 📤 **ייצוא.** H.264, HEVC, AV1. עד 4K 60, צבע 10 ביט.
- 🦀 **מנוע Rust נייטיב.** קומפוזיטור GPU, פרוקסי, פענוח חומרה. 4K נגלל חלק.
- 🤖 **ניתן לתסריט.** API של JSON-RPC שאיתו סקריפטים וסוכני AI יכולים לערוך וידאו. בנייה מקוד המקור מוסיפה gRPC וכלי שורת פקודה.
- 🖥️ **macOS, Windows, Linux, Android.** 26 שפות. אותה אפליקציה, אותם קובצי פרויקט.

## הורדה

שתי דרכים פנימה:

1. **[האתר](https://github.com/shantonda/sjcut/releases)** נותן לכם את הגרסה הנכונה למחשב שלכם. התחילו כאן.
2. **[GitHub Releases](https://github.com/shantonda/sjcut/releases)** מכיל כל גרסה לכל פלטפורמה, עם מתקינים, חבילות וסכומי ביקורת. למקרה שתרצו לבחור בעצמכם.

SJCut נמצא ב**בטא**: הוא עובד, ועדיין יש לו קצוות. [ספרו](https://github.com/shantonda/sjcut/issues) כשתמצאו אחד.

**פלטפורמות**

- ✅ **Windows** · x86_64 (בניות ה-ARM מושהות, ראו [#326](https://github.com/shantonda/sjcut/issues/326)). תוכנית התקנה ו-`.msi`. אם SmartScreen עוצר גרסה לא חתומה: **מידע נוסף** › **הפעל בכל זאת**
- ✅ **macOS** · Intel ו-Apple Silicon. אם macOS מסרב לפתוח גרסה לא חתומה: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 ו-ARM. ‏`.deb`, ‏`.rpm`, ‏`.AppImage` וחבילת Arch. וגם Flatpak ב-**[Flatpark](https://flatpark.org/apps/app.concat.editor/)**, מאגר Flatpak קהילתי שעוטף את ה-`.deb` ל-x86_64 של כל גרסה ומתעדכן איתה
- ✅ **Android** · טלפונים וטאבלטים
- ✅ **iOS / iPadOS** · iPhone ו-iPad, בהתקנה צדדית

✅ נתמך · 🚧 בעבודה · 🧪 טרם נבדק

**דרישות המערכת** וגודלי המודלים האופציונליים נמצאים [באתר](https://concat.standalones.org/guides/system-requirements).

**[Code signing policy](../CODE_SIGNING.md)**

## איך לתרום

> [!IMPORTANT]
> הדרך הטובה ביותר לתרום היא לקחת גרסה מעמוד ה-[Releases](https://github.com/shantonda/sjcut/releases) ולהשתמש בה: למצוא איפה היא נשברת, ולומר איפה היא יכולה להיות טובה יותר.
>
> מוכנים לכתוב קוד? [CONTRIBUTING.md](../CONTRIBUTING.md) מכסה את ההתקנה, מבנה העץ, הבדיקות שצריך להריץ ואת רישוי התרומות. מפעילים את SJCut מסקריפט, משירות או מסוכן? [תיעוד המפתחים](https://concat.standalones.org/docs) מכסה את ה-API של SJCut ואת ערוצי התעבורה שלו: JSON-RPC ו-gRPC. [בדיון הזה](https://github.com/shantonda/sjcut/discussions/3) הוכרז הפרויקט.
> 
> תורמים יכולים לקבל תפקיד `@Contributor` בשרת ה-Discord: רק צריך לבקש.

## היסטוריית כוכבים

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## תורמים

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

