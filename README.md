![Arcade Games](Arcade-Games-Banner.jpg)

# Arcade Games

Small arcade games written in plain JavaScript, HTML canvas and CSS, with no frameworks. A
learning project.

**Play:** https://selvalogesh.github.io/arcade-games/

| Game | Folder | Controls |
|---|---|---|
| Ping Pong | [table-tennis/](table-tennis) | Left/right arrows, or drag with finger or mouse; Space or Esc pauses |
| Snake | [snake/](snake) | Arrow keys or swipe |
| 2048 | [2048/](2048) | Arrow keys or swipe |

[ai-car/](ai-car) is an unfinished driving prototype and isn't linked from the menu yet.

## Run locally

The games are static files, so any web server works:

```sh
npx serve .
```

Then open the printed URL. Opening `index.html` straight from disk won't work, because the
scripts are ES modules.

## Layout

| Path | What |
|---|---|
| `index.html`, `main.js`, `style.css` | The menu page |
| `serviceWorker.js` | Service worker registered by the menu |
| `utilities/` | Shared code, such as swipe handling for touch screens |
| `apps/` | Android apps for Google Play, one per game, built with Capacitor. See [apps/README.md](apps/README.md) |
| `privacy-policy.html` | Privacy policy for the Play Store listings |

## License

GPL-3.0. See [LICENSE](LICENSE).
