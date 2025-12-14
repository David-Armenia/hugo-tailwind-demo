# Hugo Tailwind Demo

Небольшой демонстрационный проект на **Hugo + Tailwind CSS**.

## Быстрый старт
```bash
# 1) Установите зависимости
npm install

# 2) Запуск dev-сервера
npm run dev
# откроется http://localhost:1313

# 3) Билд (c минификацией)
npm run build
```

Проект использует **Hugo Pipes + PostCSS**: стили собираются из `assets/css/input.css` и подключаются в `layouts/_default/baseof.html`.

## Структура
```
layouts/         # baseof, partials, шаблоны
assets/css/      # Tailwind input.css
content/         # контент (главная страница)
```

## Деплой на GitHub Pages
1. Создайте публичный репозиторий и загрузите файлы проекта.
2. Выполните `npm ci && npm run build` — статический сайт окажется в папке `public/`.
3. Включите GitHub Pages для ветки с содержимым `public` (например, `gh-pages`).

## Что демонстрируется
- Частичные шаблоны (header/footer), `baseof.html`
- Tailwind‑компоненты и адаптивность
- OpenGraph и JSON‑LD (schema.org)
