# Arivu Marp Theme

![](media/logo.png)

**Arivu** is a custom CSS theme for [Marp](https://marp.app/) designed for creating professional and beautiful presentations. It builds on the `gaia` theme and imports some classes from the [Awesome Marp](https://github.com/favourhong/Awesome-Marp) theme.

## ✨ Features

*   **60+ Slide Layouts:** A wide variety of styles for bullet points, cards, panels, timelines, and more.
*   **Animated Backgrounds:** Three cinematic background modes — `vortex`, `aurora`, and `ember`.
*   **Soft Fragments:** Use `softfrag` for smooth per-item reveal animations.
*   **Customizable:** Easily add headers, footers, and logos.
*   **Icon Support:** Use GitHub emoticons or Font Awesome icons in your slides.
*   **Special Effects:** Animations like `shine`, `crawl`/`marchants`, `frost`, and `slidein`.
*   **Video Backgrounds:** Embed videos as slide backgrounds using the `screen` class.

## 🚀 Quick Start

1.  **Install Marp:** Get the [Marp for VS Code extension](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode) or the [Marp CLI](https://marp.app/).

2.  **Add the Theme:** In VS Code's Marp extension settings, add the following URL to `Markdown: Marp > Themes`:
    ```
    https://gsm-arivu.github.io/css/arivu.css
    ```

3.  **Set the Theme in Your Markdown:**
    ```markdown
    ---
    marp: true
    theme: arivu
    ---
    ```

## 🎨 Animated Backgrounds

Prefix any layout class with one of the three animated background classes:

| Class | Effect |
|-------|--------|
| `vortex` | Dark swirling vortex animation |
| `aurora` | Northern lights colour-wash |
| `ember` | Glowing embers / fire effect |

Example: `<!-- _class: vortex box softfrag -->`

## 🧩 Available Layouts

Apply a class to a slide to change its style. For example: `<!-- _class: box -->`

The **Sweet spot** column shows how many bullets fit best on a 16:9 slide without crowding.

### Bullet Styles
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `box` | Coloured box bullets | 4–8 |
| `capsule` | Pill/capsule shaped bullets | 4–8 |
| `white` | Clean white bullets | 4–8 |
| `white_circle` | White circle bullets | 4–8 |
| `white_delta` | White triangle/delta bullets | 4–8 |
| `glass` | Frosted glass bullets | 4–8 |
| `neon` | Neon glow bullets | 4–8 |

### Card & Grid Layouts
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `card` | Simple card grid | 4–9 |
| `card_color` | Coloured card grid (up to 4 per row) | 6–12 |
| `card_color_round` | Rounded coloured cards | 4–8 |

### Panel Layouts
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `panel` | Icon + description panels | 4–6 |
| `panel_card` | Card-style panels | 4–6 |
| `panel_transparent` | Transparent panels | 4–6 |
| `panel_capsule` | Capsule-shaped panels | 3–4 |
| `panel_shirt` | Shirt-shaped panels | 3–4 |
| `panel_pillar` | Pillar-style panels | 3–4 |

Add `frost` to any panel class for a frosted-glass overlay: `<!-- _class: panel frost -->`

### Icon Layouts
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `icon_box` | Icon in a box | 4–6 |
| `icon_capsule` | Icon in a capsule | 4–6 |
| `icon_card` | Icon card (title + body) | 4–6 |
| `icon_flower` | Icon flower arrangement | 4–6 |
| `icon_pillar` | Icon pillar — 3×2 grid | **6** |
| `icon_pillar4` | Icon pillar — 2×2 grid | **4** |
| `icon_shirt` | Icon shirt — 3×2 grid | **6** |
| `icon_shirt4` | Icon shirt — 2×2 grid | **4** |

### Timeline & Process Layouts
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `timeline` | Horizontal timeline with year labels | 4–8 |
| `timeline2` | Icon-based timeline | 4–6 |
| `roadmap` | Top-to-bottom roadmap | 4–6 |
| `roadmap2` | Bottom-to-top roadmap | 4–6 |
| `chevron` | Chevron process flow | 3–5 |
| `stairs` | Stair-step progression | 4–8 |

### Decorative Shapes
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `hexagon` | Hexagon bullets | 4–8 |
| `caterpillar` | Caterpillar chain | 4–8 |
| `triangle` | Triangle bullets | 4–8 |
| `arrow` | Arrow bullets | 4–8 |
| `flower` | Flower arrangement | **4** |
| `zigsaw` | Zigzag/jigsaw layout | **4** |
| `paintbrush` | Paintbrush strokes | 3–4 |
| `pyramid` | Pyramid (top to bottom) | 3–5 |
| `pyramid2` | Pyramid (bottom to top) | 3–5 |

### Other Layouts
| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `ribbon` | Ribbon banners | 4–8 |
| `ticket` | Ticket stubs | 4–8 |
| `chat` | Chat bubbles | 4–8 |
| `tag` | Label tags | 4–8 |
| `leaf` | Leaf pairs | 4–8 |
| `bookmark` | Bookmark ribbons | 3–5 |
| `fold` | Sticky notes | 4–8 |
| `fa` | Font Awesome icon list | 4–8 |
| `bq-purple` | Purple blockquote callout | — |
| `bq-blue` | Blue blockquote callout | — |

### New Shape Classes

These classes were added most recently. All support the `frost` modifier when paired with a dark background (`aurora`, `vortex`, or `ember`).

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `pennant` | Auto-numbered downward-pointing royal banner bullets | 3–6 |
| `parallelogram` | Horizontal process panels in slanted parallelogram columns | 3–6 |
| `folder_tab` | Upright cards with a coloured folder-tab tongue at the top | 2–4 |
| `banner_card` | White cards with a colour-splash banner protruding above | 2–4 |
| `tab_card` | White outline cards with a coloured header band and fold-corner dog-ear | 2–4 |
| `chevron_panel` | Overlapping chevron/arrow cards for process flows | 3–5 |
| `fold_banner` | Full-width rows with auto-number, diagonal fold, and icon zone | 2–6 |
| `dash_button` | Tall pill cards with a centred icon circle; alternating layout | 2–4 |
| `chevron_block` | Stacked rows alternating icon strip and chevron text panel | 2–6 |

Markdown structure for all new shape classes:
```markdown
<!-- _class: banner_card -->

# Slide Title

* :icon:

  - **Bold Title**
  - Body text here…
```

Frost example:
```markdown
<!-- _class: aurora fold_banner frost softfrag -->
```

## 🎬 Special Effects

Combine these modifier classes with any layout:

| Class | Effect |
|-------|--------|
| `softfrag` | Fade-in each list item on click |
| `shine` | Adds a glow / shimmer effect |
| `frost` | Frosted-glass overlay on panels |
| `marchants` / `crawl` | Scrolling marquee animation |
| `slidein` | Slide-in entrance animation |
| `screen` + `bg-video` | Full-slide video background |

## 📁 Included Files

*   `css/arivu.css` — The theme file.
*   `markdown/arivu-theme-example.md` — A comprehensive two-part example presentation (Part 1: dark animated, Part 2: traditional).
*   `vs code/snippets/arivu.code-snippets` — VS Code snippets for all layout classes (per-slide `_class` and front-matter `class` variants).
*   `vs code/snippets/markdown.code-snippets` — General Marp markdown snippets.

## :tv: Preview

Visit [https://gsm-arivu.github.io](https://gsm-arivu.github.io) to see how the markdown is rendered in HTML.

## 📜 License

This project is licensed under the MIT License.
