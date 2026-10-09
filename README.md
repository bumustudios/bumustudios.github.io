# bumustudios.github.io

The public site for **BumuStudios**, served by GitHub Pages at
<https://bumustudios.github.io/>.

It is plain, hand-written HTML. There is no build step, no framework and no
dependencies: every page carries its own `<style>` block. Edit the HTML, push to
`main`, and Pages republishes in about a minute.

## What it publishes

| Page | Address |
| --- | --- |
| Studio landing | <https://bumustudios.github.io/> |
| ImageToPdf privacy policy (EN) | <https://bumustudios.github.io/imagetopdf/privacy/> |
| ImageToPdf gizlilik politikası (TR) | <https://bumustudios.github.io/imagetopdf/privacy/tr/> |
| PdfPages privacy policy (EN) | <https://bumustudios.github.io/pdfpages/privacy/> |
| PdfPages gizlilik politikası (TR) | <https://bumustudios.github.io/pdfpages/privacy/tr/> |
| Grid Smash privacy policy (EN) | <https://bumustudios.github.io/gridsmash/privacy/> |
| Grid Smash gizlilik politikası (TR) | <https://bumustudios.github.io/gridsmash/privacy/tr/> |
| Arrow Rush privacy policy (EN) | <https://bumustudios.github.io/arrowrush/privacy/> |
| Arrow Rush gizlilik politikası (TR) | <https://bumustudios.github.io/arrowrush/privacy/tr/> |
| Color Pour privacy policy (EN) | <https://bumustudios.github.io/colorpour/privacy/> |
| Color Pour gizlilik politikası (TR) | <https://bumustudios.github.io/colorpour/privacy/tr/> |
| Fortify privacy policy (EN) | <https://bumustudios.github.io/fortify/privacy/> |
| Fortify gizlilik politikası (TR) | <https://bumustudios.github.io/fortify/privacy/tr/> |
| Hill Rush privacy policy (EN) | <https://bumustudios.github.io/hillrush/privacy/> |
| Hill Rush gizlilik politikası (TR) | <https://bumustudios.github.io/hillrush/privacy/tr/> |
| Pulse Runner privacy policy (EN) | <https://bumustudios.github.io/pulserunner/privacy/> |
| Pulse Runner gizlilik politikası (TR) | <https://bumustudios.github.io/pulserunner/privacy/tr/> |
| PaperLite privacy policy (EN) | <https://bumustudios.github.io/paperlite/privacy/> |
| PaperLite gizlilik politikası (TR) | <https://bumustudios.github.io/paperlite/privacy/tr/> |
| QR Pocket privacy policy (EN) | <https://bumustudios.github.io/qrpocket/privacy/> |
| QR Pocket gizlilik politikası (TR) | <https://bumustudios.github.io/qrpocket/privacy/tr/> |
| Polyglance privacy policy (EN) | <https://bumustudios.github.io/linguasnap/privacy/> |
| Polyglance gizlilik politikası (TR) | <https://bumustudios.github.io/linguasnap/privacy/tr/> |
| Habit Loom privacy policy (EN) | <https://bumustudios.github.io/habitloom/privacy/> |
| Habit Loom gizlilik politikası (TR) | <https://bumustudios.github.io/habitloom/privacy/tr/> |
| PennyLeaf privacy policy (EN) | <https://bumustudios.github.io/pennyleaf/privacy/> |
| PennyLeaf gizlilik politikası (TR) | <https://bumustudios.github.io/pennyleaf/privacy/tr/> |
| Tomato Focus privacy policy (EN) | <https://bumustudios.github.io/tomatofocus/privacy/> |
| Tomato Focus gizlilik politikası (TR) | <https://bumustudios.github.io/tomatofocus/privacy/tr/> |
| Mahjong Solitaire privacy policy (EN) | <https://bumustudios.github.io/mahjong/privacy/> |
| Mahjong Solitaire gizlilik politikası (TR) | <https://bumustudios.github.io/mahjong/privacy/tr/> |
| Solitaire Grove privacy policy (EN) | <https://bumustudios.github.io/solitairegrove/privacy/> |
| Solitaire Grove gizlilik politikası (TR) | <https://bumustudios.github.io/solitairegrove/privacy/tr/> |
| 2048 Zen privacy policy (EN) | <https://bumustudios.github.io/zen2048/privacy/> |
| 2048 Zen gizlilik politikası (TR) | <https://bumustudios.github.io/zen2048/privacy/tr/> |
| Word Lantern privacy policy (EN) | <https://bumustudios.github.io/wordhunt/privacy/> |
| Word Lantern gizlilik politikası (TR) | <https://bumustudios.github.io/wordhunt/privacy/tr/> |

## Read this before editing a policy page

These are not marketing pages. They are the legal documents that

- are **compiled into the shipped apps** — `SettingsScreen.kt` in each app opens
  its policy URL directly, so an app already installed on someone's phone points
  at whatever is live here, and
- are **declared to Google Play** as each app's privacy policy URL. Play re-checks
  that URL after publication and can suspend a listing over a dead link or over
  content that contradicts the Data Safety form.

Consequences of that:

- **Never move or rename a policy directory.** Old app versions cannot be
  updated to follow you.
- **Change both languages together.** A Turkish page that describes different
  data handling than the English one is a discrepancy, not a translation lag.
- **Update the "last updated" date** in the page when the substance changes, and
  keep it identical across the two languages.
- Keep the apps' pages structurally parallel. They are deliberately the same
  template, which is what makes a difference between them readable as meaningful.
- **Name every ad network the app can serve ads from.** The apps published from
  October 2026 (Mahjong Solitaire onwards) use AdMob mediation with AppLovin, Unity Ads,
  Liftoff, Meta Audience Network, Mintegral and Pangle; their policies list each one. If a
  network is added to or removed from an app's mediation, its policy changes with it.

## Layout

```
index.html              studio landing page
404.html                served for any unknown path, at any depth
imagetopdf/privacy/     ImageToPdf policy, English
imagetopdf/privacy/tr/  ImageToPdf policy, Turkish
pdfpages/privacy/       PdfPages policy, English
pdfpages/privacy/tr/    PdfPages policy, Turkish
gridsmash/privacy/      Grid Smash policy, English
gridsmash/privacy/tr/   Grid Smash policy, Turkish
arrowrush/privacy/      Arrow Rush policy, English
arrowrush/privacy/tr/   Arrow Rush policy, Turkish
colorpour/privacy/      Color Pour policy, English
colorpour/privacy/tr/   Color Pour policy, Turkish
fortify/privacy/        Fortify policy, English
fortify/privacy/tr/     Fortify policy, Turkish
hillrush/privacy/       Hill Rush policy, English
hillrush/privacy/tr/    Hill Rush policy, Turkish
pulserunner/privacy/    Pulse Runner policy, English
pulserunner/privacy/tr/ Pulse Runner policy, Turkish
paperlite/privacy/      PaperLite policy, English
paperlite/privacy/tr/   PaperLite policy, Turkish
qrpocket/privacy/       QR Pocket policy, English
qrpocket/privacy/tr/    QR Pocket policy, Turkish
linguasnap/privacy/     Polyglance policy, English
linguasnap/privacy/tr/  Polyglance policy, Turkish
habitloom/privacy/      Habit Loom policy, English
habitloom/privacy/tr/   Habit Loom policy, Turkish
pennyleaf/privacy/      PennyLeaf policy, English
pennyleaf/privacy/tr/   PennyLeaf policy, Turkish
tomatofocus/privacy/    Tomato Focus policy, English
tomatofocus/privacy/tr/ Tomato Focus policy, Turkish
mahjong/privacy/        Mahjong Solitaire policy, English
mahjong/privacy/tr/     Mahjong Solitaire policy, Turkish
solitairegrove/privacy/ Solitaire Grove policy, English
solitairegrove/privacy/tr/Solitaire Grove policy, Turkish
zen2048/privacy/        2048 Zen policy, English
zen2048/privacy/tr/     2048 Zen policy, Turkish
wordhunt/privacy/       Word Lantern policy, English
wordhunt/privacy/tr/    Word Lantern policy, Turkish
.nojekyll               tells Pages to serve the files as-is, skipping Jekyll
```

`.nojekyll` is not strictly required — nothing here starts with an underscore —
but without it a stray `{{` anywhere in the copy would fail the whole Pages build
rather than one file.

## Related repositories

- [ImageToPdf](https://github.com/bumustudios-dev/ImageToPdf) *(private)*
- [PdfPages](https://github.com/bumustudios-dev/PdfPages) *(private)*
- [GridSmash](https://github.com/bumustudios-dev/GridSmash) *(private)*
- [ArrowRush](https://github.com/bumustudios-dev/ArrowRush) *(private)*
- [ColorPour](https://github.com/bumustudios-dev/ColorPour) *(private)*
- [Fortify](https://github.com/bumustudios-dev/Fortify) *(private)*
- [HillRush](https://github.com/bumustudios-dev/HillRush) *(private)*
- [PulseRunner](https://github.com/bumustudios-dev/PulseRunner) *(private)*
- [PaperLite](https://github.com/bumustudios-dev/PaperLite) *(private)*
- [QrPocket](https://github.com/bumustudios-dev/QrPocket) *(private)*
- [LinguaSnap](https://github.com/bumustudios-dev/LinguaSnap) *(private)*
- [HabitNest](https://github.com/bumustudios-dev/HabitNest) *(private)*
- [PennyLeaf](https://github.com/bumustudios-dev/PennyLeaf) *(private)*
- [TomatoFocus](https://github.com/bumustudios-dev/TomatoFocus) *(private)*
- [Mahjong](https://github.com/bumustudios-dev/Mahjong) *(private)*
- [SolitaireGrove](https://github.com/bumustudios-dev/SolitaireGrove) *(private)*
- [Zen2048](https://github.com/bumustudios-dev/Zen2048) *(private)*
- [WordHunt](https://github.com/bumustudios-dev/WordHunt) *(private)*

## Licence

The site content is proprietary; see [LICENSE](LICENSE). The policy text is
published so that users and Google Play can read it, not so that it can be
reused.

## app-ads.txt

`app-ads.txt` sitenin **kökünde** durur: https://bumustudios.github.io/app-ads.txt

AdMob, bir uygulamanın mağaza kaydındaki **geliştirici web sitesi** alanından alan adını
alır ve dosyayı orada arar. Dosya alan adı başına birdir, uygulama başına değil — tek
satır bütün uygulamalarımızı kapsar. Bu yüzden iki koşul birlikte sağlanmalı:

1. Dosya kökte yayında kalmalı (alt klasöre taşınmamalı, silinmemeli).
2. Her uygulamanın Play Console mağaza kaydında **Web sitesi** alanı
   `https://bumustudios.github.io` olmalı.

Yeni bir reklam ağı eklenirse satırı buraya eklemek gerekir; AdMob tarafında
**Uygulamalar → app-ads.txt → Güncellemeleri kontrol et** ile tarama tetiklenir.

### Mediation ortakları

Mahjong Solitaire ve sonrasındaki uygulamalar AdMob mediation ile şu ağlardan da reklam
alır: **AppLovin, Unity Ads, Liftoff Monetize, Meta Audience Network, Mintegral, Pangle**.
Her ağın hesabı açıldığında, o ağın panelinin verdiği app-ads.txt satır(lar)ı dosyadaki
ilgili yorumun altına eklenmeli — bizim yayıncı/hesap kimliklerimizle, başka yerden
kopyalanmadan. Satırı eksik olan ağ, Tier-1 alıcıların büyük kısmına "doğrulanmamış
envanter" görünür ve o ağdan gelen gelir belirgin düşer.
