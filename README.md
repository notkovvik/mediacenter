# mediacenter

Домашний медиахаб, который не пытается быть Netflix. Каталог, плеер, загрузки — в одном окне, без подписок и облаков.

> Сайт: https://notkovvik.github.io/mediacenter/

## Стек

- Go (бэкенд)
- Vanilla JS + HTML/CSS (фронт, без фреймворков)
- SQLite (метаданные)

## Структура репозитория

```
.
├── index.html              # Главная
├── pages/
│   ├── features.html       # Что умеет
│   ├── download.html       # Установка
│   └── about.html          # О проекте
├── assets/
│   ├── css/style.css
│   └── js/                 # (будет)
└── README.md
```

## Запуск сайта локально

```bash
git clone https://github.com/notkovvik/mediacenter.git
cd mediacenter
python3 -m http.server 8080
# открой http://localhost:8080
```

## Лицензия

MIT
