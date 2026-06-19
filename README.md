# Arivu Marp Theme

![](media/logo.png)

**Arivu** is a custom CSS theme for [Marp](https://marp.app/) designed for creating professional and beautiful presentations. It builds on the `gaia` theme and imports some classes from the [Awesome Marp](https://github.com/favourhong/Awesome-Marp) theme.

## ✨ Features

*   **80+ Slide Layouts:** A wide variety of styles for bullet points, cards, panels, timelines, and more.
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

---

### Bullet List Styles

Shaped list bullets — each item in your list gets the named shape as its marker.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `box` | Coloured box bullets | 4–8 |
| `capsule` | Pill/capsule shaped bullets | 4–8 |
| `white` | Clean white bullets | 4–8 |
| `white_circle` | White circle bullets | 4–8 |
| `white_delta` | White triangle/delta bullets | 4–8 |
| `glass` | Frosted glass bullets | 4–8 |
| `neon` | Neon glow bullets | 4–8 |
| `pennant` | Auto-numbered downward-pointing royal banner bullets | 3–6 |

---

### Arrow & Chevron Layouts

Directional shapes — arrows, pentagons, and chevrons that guide the eye through a process or flow.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `arrow` | Horizontal arrow bullets | 4–8 |
| `arrow_v` | Vertical columns of alternating up/down pentagon arrows | 3–5 |
| `arrow_tab` | Portrait cards with a coloured pentagon icon zone and auto-counter badge | 3–5 |
| `chevron` | Horizontal chevron process flow | 3–5 |
| `chevron_panel` | Overlapping chevron/arrow cards for process flows | 3–5 |
| `chevron_block` | Stacked rows alternating icon strip and chevron text panel | 2–6 |

Add `frost` to any of these with a dark animated background for a frosted-glass overlay.

---

### Card Layouts

Uniform grid of upright cards — each item is a self-contained card tile.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `card` | Simple card grid | 4–9 |
| `card_color` | Coloured card grid (up to 4 per row) | 6–12 |
| `card_color_round` | Rounded coloured cards | 4–8 |
| `folder_tab` | Upright cards with a coloured folder-tab tongue at the top | 2–4 |
| `banner_card` | White cards with a colour-splash banner protruding above | 2–4 |
| `tab_card` | White outline cards with a coloured header band and dog-ear fold | 2–4 |
| `cap_card` | Upright cards with a thick colour-cap at the top (icon zone) and grey content zone | 3–5 |
| `dash_button` | Tall pill cards with a centred icon circle; alternating layout | 2–4 |

---

### Panel Layouts

Wide horizontal panels — typically full-width rows or columns with a coloured accent zone.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `panel` | Icon + description panels | 4–6 |
| `panel_card` | Card-style panels | 4–6 |
| `panel_transparent` | Transparent panels | 4–6 |
| `panel_capsule` | Capsule-shaped panels | 3–4 |
| `panel_shirt` | Shirt-shaped panels | 3–4 |
| `panel_pillar` | Pillar-style panels | 3–4 |
| `parallelogram` | Horizontal process panels in slanted parallelogram columns | 3–6 |
| `fold_banner` | Full-width rows with auto-number, diagonal fold, and icon zone | 2–6 |

Add `frost` to any panel class for a frosted-glass overlay: `<!-- _class: panel frost -->`

---

### Icon Grid Layouts

Each item combines an icon with text — the icon takes centre stage in its own zone.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `icon_box` | Icon in a box | 4–6 |
| `icon_capsule` | Icon in a capsule | 4–6 |
| `icon_card` | Horizontal icon card (title + body) | 4–6 |
| `icon_card_alt` | Horizontal icon cards with alternating icon side (odd left, even right) | 4–6 |
| `icon_quad` | 2×2 grid of horizontal icon cards with icons clustering toward the centre | **4** |
| `icon_flower` | Icon flower arrangement | 4–6 |
| `icon_pillar` | Icon pillar — 3×2 grid | **6** |
| `icon_pillar4` | Icon pillar — 2×2 grid | **4** |
| `icon_shirt` | Icon shirt — 3×2 grid | **6** |
| `icon_shirt4` | Icon shirt — 2×2 grid | **4** |
| `envelop` | Portrait lollipop cards with dome icon zone and step-counter badge | 3–5 |
| `hex_card` | Six icon+text cards arranged in a hexagonal ring | **6** |

---

### Timeline Layouts

Horizontal sequential flows — items are placed along a horizontal axis in chronological or step order.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `timeline` | Horizontal timeline with year labels | 4–8 |
| `timeline2` | Icon-based timeline | 4–6 |
| `timeline_pin` | Absolute-positioned timeline cards alternating above/below a centre spine | **5** |
| `timeline_split` | Timeline with text panels alternating above and below a centre spine | **5** |

---

### Roadmap Layouts

Vertical sequential flows — items are placed along a vertical axis from top to bottom (or bottom to top).

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `roadmap` | Top-to-bottom roadmap | 4–6 |
| `roadmap2` | Bottom-to-top roadmap | 4–6 |
| `roadmap_pin` | Vertical roadmap cards alternating left/right on a centre spine | **5** |
| `roadmap_split` | Vertical roadmap with text panels splitting left and right off a centre spine | **5** |

---

### Staircase & Chain Layouts

Items that are visually linked or stacked in a step/chain pattern.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `stairs` | Stair-step progression | 4–8 |
| `caterpillar` | Caterpillar chain of connected segments | 4–8 |

---

### Geometric & Decorative Shapes

Polygon and organic shapes — each item takes a distinct geometric or natural form.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `hexagon` | Hexagon bullets | 4–8 |
| `triangle` | Triangle bullets | 4–8 |
| `pyramid` | Pyramid (top to bottom) | 3–5 |
| `pyramid2` | Pyramid (bottom to top) | 3–5 |
| `flower` | Flower arrangement | **4** |
| `zigsaw` | Zigzag/jigsaw layout | **4** |
| `paintbrush` | Paintbrush stroke rows | 3–4 |
| `leaf` | Leaf pairs | 4–8 |

---

### Labels, Tags & Ribbons

Badge and label shapes — each item is presented as a decorative tag, ribbon, or sticker.

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `ribbon` | Ribbon banners | 4–8 |
| `ticket` | Ticket stubs | 4–8 |
| `tag` | Label tags | 4–8 |
| `bookmark` | Bookmark ribbons | 3–5 |
| `fold` | Sticky notes | 4–8 |
| `chat` | Chat bubbles | 4–8 |

---

### Utilities & Callouts

| Class | Description | Sweet spot |
|-------|-------------|-----------|
| `fa` | Font Awesome icon list | 4–8 |
| `bq-purple` | Purple blockquote callout | — |
| `bq-blue` | Blue blockquote callout | — |

---

### Markdown Structure

All icon-zone layouts (icon grid, arrow/chevron cards, panel rows, roadmap/timeline variants) share this structure:

```markdown
<!-- _class: banner_card -->

# Slide Title

* :icon:

  - **Bold Title**
  - Body text here…
```

Frost + animated background example:

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
