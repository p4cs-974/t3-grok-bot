# Grok Bot Max for T3 Code

A theme for T3 Code modeled on the Grok Bot chat app: flat grays, no accent color, pill buttons, rounded message bubbles and a Grok-style composer. It ships light and dark palettes and follows your system appearance.

Unofficial fan theme. Not affiliated with or endorsed by xAI.

## Install

### Ask your agent

In a T3 Code thread, paste:

```
Install the T3 theme from https://github.com/p4cs-974/t3-grok-bot
```

The agent follows [AGENTS.md](AGENTS.md).

### By hand

1. Copy the contents of [`theme.json`](theme.json).
2. In any T3 Code thread, ask the agent to publish it with `t3_theme_set`, using `themeId: "grok-bot-max"` and the JSON as `theme`.

To undo, switch back to a built-in theme: `t3-chat`, `grove`, `ocean`, `ember` or `iris`.

## What it changes

- **Colors:** `#121212` chat area, `#0E0E0E` sidebar with no divider, `#1C1C1C` bot bubbles, `#2C2C2C` user bubbles. White primary buttons in dark mode, black in light mode.
- **Shapes:** pill buttons and inputs, 24px dialogs and cards, 20px message bubbles, 12px sidebar rows.
- **Composer:** solid `#1F1F1F` with a 28px radius, so it's a pill when empty and a rounded card as it grows. No glass effect.
- **Bot replies:** each one sits in its own bubble, sized to its text.
- **Switches and sliders:** blue `#326CCB` when on, a gray track and a white knob.
- **Dictation:** borderless lighter pill, with a white finish button.
- **Extras:** thinner icon strokes, slim scrollbars, a frosted chat header, soft popup shadows, dimmed tool rows and blue text selection.
- **Font:** SF Pro / Helvetica Neue system stack.

The custom CSS relies on T3's stable selectors where it can. A few rules (composer layers, voice pill, settings sliders, draft icon) use internal attributes and class names that T3 may change between releases. If something looks off after an update, open an issue.
