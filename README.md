# Arivu Marp Theme

This repository contains the **Arivu** custom CSS theme for Marp presentations, designed for professional, beautiful, and flexible slides. It is built upon the base marp gaia theme and with some customization on the [awesome marp](https://github.com/favourhong/Awesome-Marp) theme.
---

## ✨ Features

- 🎨 Clean, modern slide designs
- ✅ Multiple *bullet list* styles for different contexts
- 📐 Responsive layouts
- 🖼️ Customizable header and footer with logos
- ⭐ Font Awesome icon support in lists
- 📄 Automatic pagination
- ⚡ Works with Marp CLI and Marp for VS Code

---

## 🚀 How to Use

1️⃣ Install [Marp CLI](https://marp.app/) or [Marp for VS Code](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode).  

2️⃣ Add `arivu.css` to your project. 

## ⚙️ Preferred Method: Using arivu.css URL in Marp for VS Code

If you want to use the Arivu theme directly from GitHub **without manually downloading it**, you can add `https://raw.githubusercontent.com/gsm-india/arivu/refs/heads/main/arivu.css` in the Markdown:Marp>Themes Add Item section of Marp extension settings in VS Code.


3️⃣ In your markdown frontmatter, set the theme:

```markdown
---
marp: true
theme: arivu
---
```

4️⃣ Use **section classes** to choose your bullet style:

```markdown
<!-- _class: box -->
```

5️⃣ Most of the classes show an icon before the bullet text. The generic format for such slides is like this:
```

---
<!-- _class: icon_box  -->

# heading

* :+1:

  - point one

* :+1:

  - point two

* :+1:

  - point three

* :+1:

  - point four

* :+1:

  - point five

---
```

---

## 📌 Header and Footer Example

Add this to your frontmatter for custom branding:

```markdown
header: |
  <div class="logo-header">
    <img src="media/logo-small-black.svg" alt="Logo">
    <p>Presentation Header</p>
  </div>

footer: <span class="date"></span>
```

---

## 🎨 Available Section Classes

Below is a **complete list of classes**, with descriptions and usage examples:

---

### 1️⃣ `box`

Colorful rounded boxes:

```markdown
<!-- _class: box -->

* :rocket: Launch
* :bulb: Ideas
```

---

### 2️⃣ `capsule`

Pill-shaped bullets:

```markdown
<!-- _class: capsule -->

* :heart: Care
* :book: Learn
```

---

### 3️⃣ `white`

Clean, formal blocks:

```markdown
<!-- _class: white -->

* Planning
* Execution
```

---

### 4️⃣ `white_circle`

Bullets with circle accents:

```markdown
<!-- _class: white_circle -->

* Step One
* Step Two
```

---

### 5️⃣ `white_delta`

Alternating shaded bullets:

```markdown
<!-- _class: white_delta -->

* Understand
* Propose
* Implement
```

---

### 6️⃣ `card`

Grid of colorful cards:

```markdown
<!-- _class: card -->

* :one: Define
* :two: Build
* :three: Test
```

---

### 7️⃣ `card_color`

Colored card grid:

```markdown
<!-- _class: card_color -->

* :one: Plan
* :two: Develop
```

---

### 8️⃣ `panel`

Panel layout with icons and descriptions:

```markdown
<!-- _class: panel -->

* :rocket:
  - Launch initiatives
* :bulb:
  - Generate ideas
```

---

### 9️⃣ `panel_card`

Uniform-height panel cards:

```markdown
<!-- _class: panel_card -->

* :book:
  - Learning
* :heart:
  - Caring
```

---

### 10️⃣ `panel_transparent`

Clean transparent panels:

```markdown
<!-- _class: panel_transparent -->

* :star:
  - Excellence
* :gear:
  - Engineering
```

---

### 11️⃣ `panel_capsule`

Capsule-shaped panels:

```markdown
<!-- _class: panel_capsule -->

* :bulb:
  - Bright Ideas
```

---

### 12️⃣ `panel_shirt`

Panels in shirt-style layout:

```markdown
<!-- _class: panel_shirt -->

* :rocket:
  - Speed
* :book:
  - Knowledge
```

---

### 13️⃣ `icon_shirt`

Icon-based grid layout:

```markdown
<!-- _class: icon_shirt -->

* :rocket:
  - Launch
* :bulb:
  - Ideas
```

---

### 14️⃣ `icon_shirt4`

4x4 icon grid:

```markdown
<!-- _class: icon_shirt4 -->

* :star:
  - Quality
* :gear:
  - Precision
```

---

### 15️⃣ `icon_pillar`

Vertical pillar icons:

```markdown
<!-- _class: icon_pillar -->

* :rocket:
  - Innovation
* :book:
  - Learning
```

---

### 16️⃣ `icon_pillar4`

4-column pillar grid:

```markdown
<!-- _class: icon_pillar4 -->

* :star:
  - Excellence
* :gear:
  - Engineering
```

---

### 17️⃣ `icon_card`

Icon grid cards:

```markdown
<!-- _class: icon_card -->

* :rocket:
  - Launch
* :book:
  - Study
```

---

### 18️⃣ `icon_box`

Icon bullets with boxes:

```markdown
<!-- _class: icon_box -->

* :rocket:
  - Lift-off
* :bulb:
  - Insights
```

---

### 19️⃣ `icon_capsule`

Icon capsule bullets:

```markdown
<!-- _class: icon_capsule -->

* :star:
  - Shine
* :heart:
  - Care
```

---

### 20️⃣ `icon_flower`

Petal-style layout:

```markdown
<!-- _class: icon_flower -->

* :rocket:
  - Start
* :bulb:
  - Brighten
```

---

### 21️⃣ `hexagon`

Hexagon-shaped bullets:

```markdown
<!-- _class: hexagon -->

* One
* Two
```

---

### 22️⃣ `caterpillar`

Caterpillar line bullets:

```markdown
<!-- _class: caterpillar -->

* Stage 1
* Stage 2
```

---

### 23️⃣ `triangle`

Triangle bullets:

```markdown
<!-- _class: triangle -->

* Alpha
* Beta
```

---

### 24️⃣ `arrow`

Arrow bullets:

```markdown
<!-- _class: arrow -->

* Point A
* Point B
```

---

### 25️⃣ `timeline`

Chronological timeline:

```markdown
<!-- _class: timeline -->

* 1940
  - Event one
* 1950
  - Event two
* 19620
  - Event three
* 1970
  - Event four
```

---

### 26️⃣ `timeline2`

Alternate timeline:

```markdown
<!-- _class: timeline2 -->

* Phase 1
* Phase 2
```

---

### 27️⃣ `roadmap`

Top-to-bottom roadmap:

```markdown
<!-- _class: roadmap -->

* Concept
* Launch
```

---

### 28️⃣ `roadmap2`

Bottom-to-top roadmap:

```markdown
<!-- _class: roadmap2 -->

* Start
* Finish
```

---

### 29️⃣ `flower`

Flower petal bullets:

```markdown
<!-- _class: flower -->

* :rocket:
  - Launch
* :bulb:
  - Idea
```

---

### 30️⃣ `zigsaw`

Puzzle piece bullets:

```markdown
<!-- _class: zigsaw -->

* Part 1
* Part 2
```

---

### 31️⃣ `paintbrush`

Creative paintbrush bullets:

```markdown
<!-- _class: paintbrush -->

* :star:
  - Creativity
* :heart:
  - Passion
```

---

### 32️⃣ `pyramid`

Pyramid top-down bullets:

```markdown
<!-- _class: pyramid -->

* Vision
* Strategy
* Execution
```

---

### 33️⃣ `pyramid2`

Pyramid bottom-up bullets:

```markdown
<!-- _class: pyramid2 -->

* Foundation
* Growth
```

---

## ⚙️ Font Awesome Icons

Arivu theme supports Font Awesome icons in bullets:

```markdown
* <i class="fa fa-rocket "></i>

  - point one

* <i class="fa fa-car "></i>

  - point two

* <i class="fa fa-ship "></i>

  - point three
```

---



## ✨ Special Animation / Effect Classes

In addition to all the bullet and panel layout styles, the **Arivu theme** also supports special *effect classes* that add extra visual flair.  

These can be combined with other section classes to create dynamic, eye-catching slides.

---

### ✅ `shine`

Adds a subtle glowing effect to list items or cards.

**Usage Example:**

```markdown
<!-- _class: box shine -->

* :rocket: Launch
* :bulb: Idea

```

### ✅ `marchants` / `crawl`
Creates a continuous crawl/marquee animation for list items.


Usage Example:

```markdown

<!-- _class: box marchants -->

* :rocket: Launch
* :bulb: Idea

```

### 📹 `screen and bg-video`
Creates a dynamic video background in your slides


Usage Example:

```markdown

<video class="bg-video" autoplay muted loop playsinline>
  <source src="media/video.mp4" type="video/mp4">
</video>

# <!--fit--> <span style="color: transparent; -webkit-text-stroke: 1px black;">Thank You</span>

```



---

## 📁 Files Included

- `arivu.css` – The custom theme
- `arivu-theme-example.md` – Example markdown showcasing all styles

---

## 🚥 Dynamic Content

- The markdown file has script for auto-inserting "today's data" in the footer.

---

## ➕ Additional html content

- The markdown file contains some slide to illustrate how additional html content/tags/local styling can be done in marp slides.

---

## 📺 Preview

- To see how the markdown file is rendered using arivu.css, please visit [https://gsm-arivu.github.io](https://gsm-arivu.github.io).

## 💡 Tips

- Use emojis or Font Awesome icons which are context appropriate.

---

## 📜 License

- Licensed under the MIT License (requires attribution).


---

*Happy presenting with Arivu!* 🎉



