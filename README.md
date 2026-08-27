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
.nojekyll               tells Pages to serve the files as-is, skipping Jekyll
```

`.nojekyll` is not strictly required — nothing here starts with an underscore —
but without it a stray `{{` anywhere in the copy would fail the whole Pages build
rather than one file.

## Related repositories

- [ImageToPdf](https://github.com/bumustudios/ImageToPdf) *(private)*
- [PdfPages](https://github.com/bumustudios/PdfPages) *(private)*
- [GridSmash](https://github.com/bumustudios/GridSmash) *(private)*
- [ArrowRush](https://github.com/bumustudios/ArrowRush) *(private)*

## Licence

The site content is proprietary; see [LICENSE](LICENSE). The policy text is
published so that users and Google Play can read it, not so that it can be
reused.
