# Мастер по ключам и вскрытию замков — Иркутск и Шелехов

Одностраничный сайт-визитка (чистый HTML, без сборки).

## Структура
- `index.html` — сайт целиком (стили, скрипты и картинки внутри)
- `netlify.toml` — настройки Netlify (публикация из корня, заголовки безопасности)
- `robots.txt` — разрешение индексации

## Деплой на Netlify через GitHub
1. Создай репозиторий на GitHub и загрузи в него все эти файлы.
2. В Netlify: **Add new site → Import an existing project → GitHub**, выбери репозиторий.
3. Build command — оставь пустым, Publish directory — `.` (уже задано в `netlify.toml`).
4. Нажми **Deploy** — сайт появится по ссылке вида `https://название.netlify.app`.

Любой следующий commit в `main` будет автоматически обновлять сайт.

## Заметки
- Форма заявки отправляется через Formspree (`formspree.io/f/xrpbnzne`), Netlify Forms не нужен.
- После подключения своего домена добавь в `<head>` тег `<link rel="canonical" href="https://твой-домен/">` и `og:image` / `og:url`.
