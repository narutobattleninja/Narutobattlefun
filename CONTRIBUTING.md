# Contributing to Shinobi Clash

Thanks for your interest in improving Shinobi Clash! 🥷

## How to Contribute

1. **Fork** this repository and clone it locally.
2. **Create a branch** for your change: `git checkout -b feat/your-feature` or `fix/your-bug`.
3. **Make your changes** in `index.html`. The whole game lives in one file — HTML, CSS, and JS.
4. **Test locally** by opening `index.html` in a browser (or serving it with `python3 -m http.server`).
5. **Commit** with a clear message: `git commit -m 'feat: add double-jump'`.
6. **Push** your branch: `git push origin feat/your-feature`.
7. **Open a Pull Request** describing what you changed and why.

## Reporting Bugs

Please [open an issue](../../issues/new?template=bug_report.md) with:

- What you expected to happen
- What actually happened
- Steps to reproduce
- Browser/device you were testing on

## Suggesting Features

Open a [feature request](../../issues/new?template=feature_request.md) describing the idea and why it'd be useful.

## Code Style

- Keep everything self-contained in `index.html` unless a change genuinely needs a new file.
- Match the existing style: 2-space indentation, descriptive variable names, comments for non-obvious game logic.
- Test on both desktop and a mobile-sized viewport before submitting — this is a touch-first game.

Thanks for helping make Shinobi Clash better!
