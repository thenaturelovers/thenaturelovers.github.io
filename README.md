# thenaturelovers.github.io
Public website of The Nature Lovers

## Working on the site

- Preview: `jekyll serve` (plain CSS in `assets/css/main.css`, no build step).
- **Bilingual:** English lives at `/`, Marathi under `/mr/`. UI strings are in
  `_data/i18n.yml` (add every key to both `en` and `mr`); menu items are in
  `_data/nav.yml`.
- To translate a page, add a copy under `mr/` (or a post with `lang: mr`) and
  give both versions the same `ref:` in the front matter. The language toggle and
  navigation pick it up automatically; untranslated pages fall back to English.
- To list a post under **Upcoming** on the Events page, add `upcoming: true` to
  its front matter (remove it once the event is over).
- Fonts (Inter, Fraunces, Noto Devanagari) are self-hosted in `assets/fonts/`.
