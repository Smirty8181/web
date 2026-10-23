# Student Group Dashboard

<p align="center">
  <strong>Управление учебными группами и списками студентов</strong><br />
  Next.js-приложение с SQLite API, страницами групп и студентов и кешированием запросов.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Next.js-App%20Router-000000?logo=next.js&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/TypeScript-5-3178C6?logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/TanStack%20Query-Data%20Fetching-FF4154?logo=reactquery&logoColor=white" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?logo=sqlite&logoColor=white" alt="SQLite" />
</p>

## Возможности

- Просмотр групп и студентов.
- API-маршруты Next.js для чтения групп и студентов.
- Работа с SQLite и TanStack Query.
- Документация по маршрутизации, HTTP и модели данных в `docs/`.

## Технологии

Next.js, React, TypeScript, TanStack Query, SQLite, Sass.

## Быстрый запуск

Требуется Node.js. Установите зависимости и запустите dev-сервер:

```bash
npm ci
npm run dev
```

Откройте `http://localhost:3000`. Проверка API групп: `http://localhost:3000/api/groups`.

Другие команды:

```bash
npm run lint
npm run build
```

## Конфигурация и данные

Приложению нужна SQLite-база. Настройте переменные окружения для локальной разработки, указывая путь к собственной базе и API URL. Не публикуйте персональные данные и не используйте данные из репозитория в реальном развертывании.

**Внимание:** текущая база в репозитории содержит записи студентов. Перед распространением или повторным использованием замените ее синтетическими данными; для полноценной очистки опубликованной истории потребуется отдельная операция по переписыванию Git-истории.

## Структура

- `src/app/` — страницы и API-маршруты Next.js.
- `src/components/` — интерфейс групп и студентов.
- `src/db/` — запросы к SQLite.
- `docs/` — заметки по проекту и используемым технологиям.

