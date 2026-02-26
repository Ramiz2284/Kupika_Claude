# Купика — Списки покупок

Простой статический проект на HTML/CSS/JS. Основной файл `kupika.html` содержит всю разметку и скрипты приложения.

## Подготовка к загрузке на GitHub

1. Инициализуйте репозиторий:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. Создайте удалённый репозиторий на GitHub и подключитесь:
   ```bash
   git remote add origin <URL-репозитория>
   git push -u origin main
   ```

## Развёртывание на Vercel

Файл `vercel.json` настроен для статического хоста, чтобы корень сайта (`/`) перенаправлялся на `kupika.html`.

1. Установите [Vercel CLI](https://vercel.com/docs/cli) (по желанию):
   ```bash
   npm install -g vercel
   ```
2. В папке проекта выполните:
   ```bash
   vercel  # следуйте инструкциям
   ```

Файл `kupika.html` будет служить основным документом; при желании можно переименовать его в `index.html`.

## Структура

```
kupika/
├── kupika.html        # главный HTML-файл приложения
├── README.md          # это описание
├── .gitignore         # файлы, исключаемые из репозитория
└── vercel.json        # конфигурация для Vercel
```

---

© 2026 Проект Купика
