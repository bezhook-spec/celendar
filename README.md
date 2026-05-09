# PDR Календарь — Android PWA

Файлы для GitHub Pages лежат прямо в корне архива:

- `index.html`
- `manifest.webmanifest`
- `sw.js`
- `icon.svg`
- `icons/icon-192.png`
- `icons/icon-512.png`
- `.nojekyll`

## Как залить

1. Распакуй архив.
2. Загрузи именно файлы изнутри архива в корень репозитория, не папку целиком.
3. В GitHub включи Pages: Settings → Pages → Deploy from branch → main → /root.
4. Открой ссылку в Chrome на Android.

## Если Chrome всё ещё показывает только ярлык

Открой эти ссылки и проверь, что они не дают 404:

- `https://ТВОЙ-НИК.github.io/РЕПО/manifest.webmanifest`
- `https://ТВОЙ-НИК.github.io/РЕПО/sw.js`
- `https://ТВОЙ-НИК.github.io/РЕПО/icon.svg`

Потом очисти данные сайта в Chrome: настройки сайта → хранилище → очистить данные, и открой страницу заново.
