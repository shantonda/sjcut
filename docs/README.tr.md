<p align="center">
  <img src="https://raw.githubusercontent.com/shantonda/sjcut/main/assets/concat-mark-dark.png" alt="SJCut" width="100" />
</p>

<h1 align="center">SJCut</h1>
<h3 align="center">Ücretsiz, açık kaynaklı ve çok platformlu CapCut alternatifi.</h3>

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

[🇬🇧 English](../README.md) · [🇩🇪 Deutsch](README.de.md) · [🇪🇸 Español](README.es.md) · [🇫🇷 Français](README.fr.md) · [🇮🇹 Italiano](README.it.md) · [🇳🇱 Nederlands](README.nl.md) · [🇵🇱 Polski](README.pl.md) · [🇧🇷 Português (Brasil)](README.pt-BR.md) · [🇷🇺 Русский](README.ru.md) · [🇺🇦 Українська](README.uk.md) · **🇹🇷 Türkçe** · [🇦🇿 Azərbaycanca](README.az.md) · [🇭🇷 Hrvatski](README.hr.md) · [🇮🇩 Bahasa Indonesia](README.id.md) · [🇻🇳 Tiếng Việt](README.vi.md) · [🇹🇭 ไทย](README.th.md) · [🇯🇵 日本語](README.ja.md) · [🇰🇷 한국어](README.ko.md) · [🇨🇳 简体中文](README.zh-Hans.md) · [🇹🇼 繁體中文](README.zh-TW.md) · [🇸🇦 العربية](README.ar.md) · [🇮🇱 עברית](README.he.md) · [🇮🇷 فارسی](README.fa.md) · [🇮🇳 हिन्दी](README.hi.md) · [🇵🇰 اردو](README.ur.md) · [🇧🇩 বাংলা](README.bn.md)

> İngilizce README’den 11 Ekim 2026’da çevrildi. Güncel tutulan sürüm İngilizce olandır.

</div>


## Hakkında

SJCut; macOS, Windows, Linux ve Android için ücretsiz, açık kaynaklı bir video düzenleyici ve bir CapCut alternatifidir. İnsanların CapCut’ı gerçekten ne için açtıklarını karşılar: otomatik altyazı, metinden sese, arka plan kaldırma, anahtar kare animasyonu, efektler ve yazılar, çok parçalı kurgu, 4K dışa aktarma. Hiçbir tuzak olmadan: filigran yok, hesap yok, abonelik yok, yükleme yok.

Her şey, GPU birleştiricili yerel bir Rust motorunda yerel olarak çalışır. Kurun, görüntüleri bırakın, kesin. Altyazı, ses ve kesme için yapay zekâ modelleri Ayarlar’dan bir kez indirilir ve sonrasında çevrimdışı çalışır. Görüntüleriniz diskinizden asla çıkmaz.

**Şunlar için uygun:** TikTok, Reels ve Shorts, YouTube videoları, eğitimler ve ekran kayıtları, podcast kesitleri, memler.

**Makineler için de:** bir JSON-RPC API’si; böylece betikler ve yapay zekâ ajanları da onunla video kesebilir.

## Öne çıkanlar

- 🚫 **Filigran yok. Hesap yok. Ödeme duvarı yok.** Asla.
- 🔒 **%100 yerel.** Hiçbir şey yüklenmez. Çevrimdışı çalışır.
- 💬 **Otomatik altyazı.** Yerel Whisper. Bir model boyutu seçin, zaman çizelgesinde biçimli altyazılar alın.
- 🗣️ **Metinden sese + ses klonlama.** Ücretsiz yerel sesler ya da birkaç saniyelik kayıttan herhangi bir ses.
- 🧍 **Arka plan kaldırma.** İnsanlar, nesneler ya da maskeyi kendiniz boyayın.
- 🎞️ **Anahtar kareler.** Konum, ölçek, döndürme, saydamlık, ses düzeyi, efekt parametreleri. Yerleşik eğri düzenleyici.
- ✨ **100 efekt, filtre ve geçiş.** GPU ile çizilir, önizlemede canlı.
- ✂️ **Hızlı kesin.** Böl, kırp, ripple, birleştir, kareyi dondur, hız. İsterseniz manyetik zaman çizelgesi.
- 🎚️ **Çok parçalı, çok zaman çizelgeli.** Bir projede birden çok kurgu. Karışım modları, kırpma, çevirmeler.
- 📝 **Yazılar.** Yazı tipleri, kontur, gölge, arka plan plakası. Başlamak için hazır ayarlar.
- 🎙️ **Tek anahtarla ses temizliği.** Gürültü azaltma, sesi iyileştirme, ses düzeyini dengeleme. Artı sincap, robot, telefon ve arkadaşları.
- 📤 **Dışa aktarma.** H.264, HEVC, AV1. 4K 60’a kadar, 10 bit renk.
- 🦀 **Yerel Rust motoru.** GPU birleştirici, proxy’ler, donanım çözme. 4K akıcı gezinir.
- 🤖 **Betiklenebilir.** Betiklerin ve yapay zekâ ajanlarının video kesebileceği bir JSON-RPC API’si. Kaynaktan derlenen sürüm buna gRPC ve bir komut satırı aracı ekler.
- 🖥️ **macOS, Windows, Linux, Android.** 26 dil. Aynı uygulama, aynı proje dosyaları.

## İndir

İki yol var:

1. **[Web sitesi](https://github.com/shantonda/sjcut/releases)** makineniz için doğru derlemeyi verir. Buradan başlayın.
2. **[GitHub Releases](https://github.com/shantonda/sjcut/releases)** her platform için her derlemeyi kurucular, paketler ve sağlama toplamlarıyla sunar. Kendiniz seçmek istediğinizde.

SJCut **beta** aşamasında: çalışıyor, ama hâlâ pürüzleri var. Bir tane bulduğunuzda [söyleyin](https://github.com/shantonda/sjcut/issues).

**Platformlar**

- ✅ **Windows** · x86_64 (ARM derlemelerine ara verildi, bkz. [#326](https://github.com/shantonda/sjcut/issues/326)). Bir kurulum ve bir `.msi`. SmartScreen imzasız bir derlemeyi durdurursa: **Daha fazla bilgi** › **Yine de çalıştır**
- ✅ **macOS** · Intel ve Apple Silicon. macOS imzasız bir derlemeyi açmayı reddederse: `xattr -dr com.apple.quarantine /Applications/SJCut.app`
- ✅ **Linux** · x86_64 ve ARM. `.deb`, `.rpm`, `.AppImage` ve bir Arch paketi. Ayrıca her sürümün x86_64 `.deb`’ini saran ve onunla güncellenen topluluk Flatpak deposu **[Flatpark](https://flatpark.org/apps/app.concat.editor/)** üzerinde bir Flatpak
- ✅ **Android** · telefonlar ve tabletler
- ✅ **iOS / iPadOS** · iPhone ve iPad, sideload ile

✅ Destekleniyor · 🚧 Çalışılıyor · 🧪 Test edilecek

**Sistem gereksinimleri** ve isteğe bağlı model boyutları [web sitesinde](https://concat.standalones.org/guides/system-requirements).

**[Code signing policy](../CODE_SIGNING.md)**

## Nasıl katkıda bulunulur

> [!IMPORTANT]
> Katkıda bulunmanın en iyi yolu [Releases](https://github.com/shantonda/sjcut/releases) sayfasından bir derleme alıp kullanmaktır: nerede bozulduğunu bulun ve nerede daha iyi olabileceğini söyleyin.
>
> Kod yazmaya hazır mısınız? [CONTRIBUTING.md](../CONTRIBUTING.md) kurulumu, ağacın düzenini, çalıştırılacak denetimleri ve katkıların nasıl lisanslandığını anlatır. SJCut’i bir betikten, servisten ya da ajandan mı sürüyorsunuz? [Geliştirici belgeleri](https://concat.standalones.org/docs) SJCut API’sini ve taşıyıcılarını anlatır: JSON-RPC ve gRPC. Proje [bu tartışmada](https://github.com/shantonda/sjcut/discussions/3) duyuruldu.
> 
> Katkıda bulunanlar Discord sunucusunda bir `@Contributor` rolü alabilir: istemeniz yeter.

## Yıldız geçmişi

<a href="https://www.star-history.com/?repos=shantonda%2Fsjcut&type=date&releases=&legend=bottom-right">
 <img alt="Star History Chart" src="https://api.star-history.com/chart?repos=shantonda/sjcut&type=date&legend=bottom-right" />
</a>

## Katkıda bulunanlar

<a href="https://github.com/shantonda/sjcut/graphs/contributors">
  <img alt="Contributors" src="https://contrib.rocks/image?repo=shantonda/sjcut">
</a>

