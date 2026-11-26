# Нова Детейлинг

Одностраничный сайт детейлинг-студии «Нова» (Новороссийск) на [Astro](https://docs.astro.build).

## Структура

```text
/
├── public/            # картинки, шрифты, фавиконки, site.webmanifest
├── src/
│   ├── components/    # секции страницы: Header, Hero, Advantages, Services,
│   │                  # Contacts, Reviews, Gallery, Footer
│   ├── layouts/       # Layout.astro — <head>, мета-теги, Header/Footer
│   ├── pages/         # index.astro — собирает страницу из секций
│   └── styles/        # reset.css, global.css, fonts.css
└── package.json
```

## Команды

Требуется Node.js 22.12 или новее.

| Команда           | Действие                                        |
| :---------------- | :---------------------------------------------- |
| `npm install`     | Установить зависимости                          |
| `npm run dev`     | Dev-сервер на `localhost:4321`                  |
| `npm run build`   | Собрать сайт в `./dist/`                        |
| `npm run preview` | Посмотреть собранную версию перед публикацией   |
