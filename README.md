# YouTube Custom Subtitle Styler

A customizable UserCSS for **Stylus** that gives you full control over YouTube subtitle typography, spacing, backgrounds, borders, shadows, and blur effects—all adjustable live from Stylus's built-in settings menu.

## Features

- **Google Fonts & System Fonts:** Type any Google Font name (e.g., `Asap Condensed`, `Roboto Mono`, `IBM Plex Sans`) with no quotes or URLs required. Automatically falls back to YouTube's default subtitle font if disabled or unavailable.
- **Typography:** Customize font weight (`200`–`900`), font size (`0px` keeps YouTube's responsive default scaling), font color, and independent font blur.
- **Layout & Spacing:** Set individual top, right, bottom, and left padding, switch text alignment (`Left`, `Center`, `Right`), and adjust the distance between subtitle lines—including negative values to tighten or overlap lines.
- **Text Shadow:** Toggle drop shadows with custom color, opacity, X/Y offset, and blur radius.
- **Background & Box Styling:** Apply background color, opacity, and frosted-glass backdrop blur to either **each subtitle line** or the **entire subtitle window**.
- **Borders & Corners:** Choose between sharp **Rectangle** or **Rounded Rectangle** corners (customizable radius), plus border width, color, opacity, and soft border glow/blur.

## Requirements

- [Stylus](https://add0n.com/stylus.html) browser extension for [Chrome](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne) or [Firefox](https://addons.mozilla.org/en-US/firefox/addon/styl-us/).
  *(Not compatible with the legacy Stylish extension.)*

## Installation

1. Install the **Stylus** extension in Chrome or Firefox.
2. Click the direct install link below (Stylus will automatically open the installation prompt):
   - **[Install YouTube Custom Subtitle Styler](https://raw.githubusercontent.com/your-username/your-repo/main/youtube-subtitle-styler.user.css)**
3. Click **Install style**.

## Usage

1. Open any YouTube video with captions turned on.
2. Click the **Stylus** icon in your browser toolbar.
3. Click the **gear icon** next to **YouTube Custom Subtitle Styler** to open the settings panel.
4. Adjust any setting to preview changes live on the video.

## Troubleshooting

- **Google Fonts aren't loading on YouTube:** Open Stylus → **Options** → **Advanced** → enable **Patch CSP to allow style assets**, then refresh YouTube.
- **Overlapping text gets hidden when using negative line distance:** Lower the **Background Color** opacity or change **Apply Box Style To** from *Each Subtitle Line* to *Subtitle Window*.
