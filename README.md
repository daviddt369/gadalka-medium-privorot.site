# Зарина — gadalka-medium-privorot.site

Статический лендинг на шаблоне `privorot-gadanie-taro.site`.

- Имя: `Зарина`
- Телефон: `+7 778 968 42 10`
- WhatsApp: `77789684210`
- Домен: `gadalka-medium-privorot.site`

## Фото

- `media/hero.jpg` — главный экран и кнопка-виджет
- `media/about.jpg` — блок «Обо мне»
- `media/gallery/` — фотогалерея
- `media/certificates/` — сертификаты
- `media/og-image.jpg` — превью ссылки (WhatsApp / Telegram), 1200×630

## Защита от копирования

Подключена [site-copytrap](https://github.com/daviddt369/site-copytrap): inline-блок + `copytrap.js`.
Все `og:*`, `twitter:*` и фавиконки стоят выше скриптов защиты, а `<` в inline-блоке записаны как `\x3c` — иначе ломается превью ссылок.

## Локально

```bash
python -m http.server 8080
```

Открыть `http://localhost:8080/`.
