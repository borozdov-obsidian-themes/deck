# Borozdov Deck

A theme from the Borozdov collection. Two faces — dark **Orbit**, a cosmic command deck, and
light **Daybreak**, the same deck in daylight. A deep void, glass panels, terminal green for
what you act on, sky-blue links and one ultraviolet rim.

![Borozdov Deck in dark mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/deck/main/screenshots/dark.png)

![Borozdov Deck in light mode](https://raw.githubusercontent.com/borozdov-obsidian-themes/deck/main/screenshots/light.png)

## Principles

- **A deep void, glass on top.** The canvas is near-black; callouts and embeds are
  translucent glass panels with a translucent edge and 24px corners. Nothing casts a
  shadow — the void does the separating.
- **A terminal cursor for the action.** One warm green fills the main button, a checked
  task and a toggle — a deliberate rejection of the cool-blue convention. Sky blue is kept
  for links, and ultraviolet for the one featured rim: pull quotes and a tag under the
  pointer.
- **Two shape vocabularies, never mixed.** 6px on buttons, fields and code; 24px on glass
  cards; 60px pills for tags.
- **Monospace for what reads as code.** Tags and property values are set in a monospace
  with a hairline rim; everything else is the platform's own sans, with headings that
  compress as they grow.

## Features

- Dark and light modes, following Settings → Appearance → Base color scheme
- Callouts as glass panels with the title in the type's colour
- A syntax palette in the tradition of the great dark editors
- Tables with hairline rules and 6px corners
- Quiet editing: no focus ring around the note, its title or form fields while you type;
  property names read as labels, not boxed fields
- Text colours meet WCAG contrast on both faces
- The phone layout keeps the same colours and shapes
- No embedded fonts, so the theme stays around 12 KB; Mona Sans is used when installed
- No `!important`: every rule can be overridden with a CSS snippet

## Installation

**From the community directory, as a variant:** this theme ships inside **Borozdov
Console**. Install Borozdov Console under Settings → Appearance → Themes → Manage, then
the [Style Settings](https://github.com/mgmeyers/obsidian-style-settings) plugin, and
choose **Deck** under Style Settings → Borozdov Console → Variant. The variant brings this
theme's palette, type and corners; its own layout, and its embedded font if it has one,
come with the full theme below.

**The full theme, by hand:** download `manifest.json` and `theme.css` from the
[latest release](https://github.com/borozdov-obsidian-themes/deck/releases/latest) into
`<vault>/.obsidian/themes/Borozdov Deck/`, then choose Borozdov Deck under
Settings → Appearance → Themes.

## License

MIT — see [LICENSE](LICENSE).

---

**По-русски.** Тема из коллекции Borozdov. Два лика: тёмный «Орбита» — космическая
командная палуба, и светлый «Рассветный» — та же палуба при дневном свете. Глубокая тьма,
стеклянные панели, терминальный зелёный для того, что вы делаете, небесно-голубые ссылки и
одна ультрафиолетовая кромка. Шрифты не встроены. В каталоге тема живёт вариантом Borozdov Console: установите Borozdov Console и плагин Style Settings, затем выберите Deck в Style Settings → Borozdov Console → Variant. Целиком, со своей вёрсткой, тема ставится вручную из последнего релиза репозитория.
