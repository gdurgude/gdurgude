# Setup — gdurgude animated GitHub profile

This package follows the supplied animated-profile guide.

1. Create or open the public repository **gdurgude/gdurgude**.
2. Upload `README.md`, `banner.svg`, `banner-light.svg`, `lanyard.svg`, `stats.svg`, `langs.svg`, `trophies.svg` and the `assets/` folder to the repository root.
3. Upload `.github/workflows/github-snake.yml` to that exact path.
4. Commit the files.
5. Open **Actions → Generate contribution snake → Run workflow**. The workflow publishes the snake SVGs to the `output` branch and then refreshes every day.
6. Test both GitHub themes under **Settings → Appearance**.
7. GitHub caches README images aggressively. After editing a local SVG, first commit the SVG and then increase the image query in `README.md`, e.g. `banner.svg?v=7` → `banner.svg?v=8`.

## Files
- `banner.svg` — dark animated banner: terminal typing, outlined animated name, cycling roles, quote typing, tech pills, code card typing, one-time hologram formation, 3.5 s scanner, particles/hearts/sparkles, pulsing orbs, stats bar and flickering neon sign.
- `banner-light.svg` — light-theme equivalent, auto-selected with `<picture>`.
- `lanyard.svg` — drop-in swinging badge with damped pendulum motion, strap text, metal hardware, avatar, handle, barcode and holographic shine.
- `stats.svg` — local animated stats/rank card.
- `langs.svg` — local animated language bars.
- `trophies.svg` — local trophy cells with pop-in and shine sweep.
- `.github/workflows/github-snake.yml` — daily custom-colored contribution snake.

The language percentages and local stats are static by design; update them as your profile changes.
