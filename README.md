# Catppuccin Codex Theme for bb

A custom theme for [bb](https://getbb.app) bringing UI and layout parity with the OpenAI Codex / ChatGPT desktop app, built on top of the Catppuccin palette (Mocha dark, Latte light).

## Features

- **Codex / ChatGPT Typography**: Uses the macOS system font (`SF Pro`) matching the desktop app, with tuned `430` text weight and 14px scale.
- **Codex Send Indicator Arrow**: Replaces the return icon (`CornerDownLeft`) with the upward send arrow from Codex (`arrow-up-lg-light-20`).
- **Codex Composer Geometry**:
  - `26px` rounded container corners (matching Codex's `calc(var(--spacing) * 7)` radius).
  - Compact ~72px box height with proportional breathing room.
  - Circular `32px` send button (`rounded-full`).
- **Color Parity**:
  - `#3b3c4f` composer background and `#404153` border sampled directly from Codex dark mode.
  - Preserves native theme contrast, focus states, and disabled button behavior.
- **Decluttered View**: Removes the top-right collapse chevron and bottom composer footer for a minimal, focused prompt area.
- **Catppuccin Palette**: Retains full Catppuccin syntax highlighting and terminal ANSI colors.

## Installation

Clone into your custom themes directory and activate it:

```bash
git clone https://github.com/steveafrost/bb-theme-catppuccin-codex.git ~/.bb/theme/catppuccin-codex-font
bb theme set catppuccin-codex-font
```

The theme takes effect immediately in running windows without a restart.

## Updating

```bash
git -C ~/.bb/theme/catppuccin-codex-font pull
bb theme set catppuccin-codex-font
```

## Reset / Uninstall

To return to the default theme:

```bash
bb theme set catppuccin
# or
bb theme reset
```
