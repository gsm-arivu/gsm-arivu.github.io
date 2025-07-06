# Arivu Marp Theme

![](media/logo.png)

**Arivu** is a custom CSS theme for [Marp](https://marp.app/) designed for creating professional and beautiful presentations. It builds on the `gaia` theme and incorporates features from the [Awesome Marp](https://github.com/favourhong/Awesome-Marp) theme.

## ✨ Features

*   **30+ Slide Layouts:** A wide variety of styles for bullet points, cards, panels, and timelines.
*   **Customizable:** Easily add headers, footers, and logos.
*   **Icon Support:** Use github emoticons or Font Awesome icons in your slides.
*   **Animations:** Add visual flair with effects like `shine` and `crawl`.
*   **Video Backgrounds:** Embed videos as slide backgrounds.
*   **Responsive Design:** Slides look great on any screen size.

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

## 🎨 Available Styles

Apply a class to a slide to change its style. For example: `<!-- _class: box -->`

Here are some of the available style categories:

*   **Boxes & Capsules:** `box`, `capsule`
*   **Cards & Panels:** `card`, `card_color`, `panel`, `panel_card`, `panel_transparent`
*   **Icon-based Layouts:** `icon_shirt`, `icon_pillar`, `icon_card`, `icon_box`
*   **Timelines & Roadmaps:** `timeline`, `timeline2`, `roadmap`, `roadmap2`
*   **Unique Shapes:** `hexagon`, `caterpillar`, `triangle`, `arrow`, `flower`, `zigsaw`, `paintbrush`
*   **Pyramids:** `pyramid`, `pyramid2`

For a full list of styles and examples, see `arivu-theme-example.md`.

## 🎬 Special Effects

Combine these with other classes for more dynamic slides:

*   `shine`: Adds a glow effect.
*   `marchants` / `crawl`: Creates a scrolling animation.
*   `screen` and `bg-video`: For video backgrounds.

## 📁 Included Files

*   `arivu.css`: The theme file.
*   `arivu-theme-example.md`: A comprehensive example presentation.
*   `vs code/snippets/markdown.code-snippets`: VS Code snippets for faster authoring.

## 📜 License

This project is licensed under the MIT License.
