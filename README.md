# DLE-browser-selection

![Иллюстрация к проекту](https://tcse-cms.com/uploads/posts/2022-10/1666258808_browser-selection_02_20221020121237565.jpg)

Плагин **browser-selection by TCSE** это еще один хак для mobiledetect.class.php встроенного в DLE 15. 
Добавляем поддержку тегов для **мобильных веб-браузеров** Chrome, Mobile Safari, Firefox и Opera.
В шаблоны вашего сайта достаточно вставить указанные ниже теги, для гибкого вывода необходимой инфорации.

```
	[chrome] текст [/chrome]
```

выводят текст заключенных в них, в случае если устройство посетителя сайта использует веб-браузер Chrome

```
	[not-chrome] текст [/not-chrome]
```

выводят текст заключенных в них, в случае если устройство посетителя сайта не использует веб-браузер Chrome
```
	[safari] текст [/safari]
```

выводят текст заключенных в них, в случае если устройство посетителя сайта использует веб-браузер Mobile Safari
```
	[not-safari] текст [/not-safari]
```

выводят текст заключенных в них, в случае если устройство посетителя сайта не использует веб-браузер Mobile Safari
```
	[firefox] текст [/firefox]
```

отображает содержимое, если веб-браузер firefox
```
	[not-firefox] текст [/not-firefox]
```

отображает содержимое, если веб-браузер не firefox
```
	[opera] текст [/opera]
```

отображает содержимое, если веб-браузер opera
```
	[not-opera] текст [/not-opera]
```

отображает содержимое, если веб-браузер не opera


Пояснения по работе плагина на сайте https://tcse-cms.com/works/1438-browser-selection-by-tcse.html 


# DLE-browser-selection [![DLE Version](https://img.shields.io/badge/DLE-15%20to%2018.1-blue.svg)](https://dle-news.ru)

**Плагин для DLE (DataLife Engine)**, позволяющий показывать или скрывать контент в зависимости от веб-браузера пользователя. Полезен для таргетирования контента под Chrome, Firefox, Opera, Safari, **Яндекс.Браузер** и **Telegram-бот**.

> 🔧 Поддерживает **DLE 15.3 — 18.1**  
> 🧩 Работает через расширение `Mobile_Detect` (версия 4.8.x)  
> 📱 Требует включённую опцию: *Включить автоматическую поддержку смартфонов*

---

## 📌 Возможности

Плагин добавляет **условные теги** в шаблонизатор DLE. Вы можете использовать их в материалах, шаблонах и виджетах:

```html
[chrome]Текст для Chrome[/chrome]
[not-chrome]Не Chrome[/not-chrome]

[safari]Текст для Safari[/safari]
[not-safari]Не Safari[/not-safari]

[firefox]Текст для Firefox[/firefox]
[not-firefox]Не Firefox[/not-firefox]

[opera]Текст для Opera[/opera]
[not-opera]Не Opera[/not-opera]

[yandex-bro]Текст для Яндекс.Браузера (Android)[/yandex-bro]
[not-yandex-bro]Не Яндекс.Браузер[/not-yandex-bro]

[telegram-bot]Текст при открытии в Telegram[/telegram-bot]
[not-telegram-bot]Не в Telegram[/not-telegram-bot]
