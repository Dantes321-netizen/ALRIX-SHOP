# ALRIX STORE

## Открыть в VS Code
1. Распакуйте архив.
2. В VS Code выберите File → Open Folder и папку ALRIX-STORE.
3. Можно сразу открыть index.html в браузере.
4. Для удобного редактирования установите расширение Live Server, нажмите правой кнопкой на index.html и выберите Open with Live Server.

## Файлы
- index.html — разметка сайта.
- styles.css — цвета, размеры и оформление.
- script.js — товары, поиск, корзина и ссылка на Telegram-бота.
- assets/ — обложки, favicon и созданный логотип logo.png.

## Изменить товары и цены
В script.js найдите массив products. Поля name, price, platform, desc и image отвечают за название, цену в MDL, платформу, описание и обложку. Значения cat: games, subs, top.

## Telegram
Ссылка на бота: https://t.me/arlix_shop_bot. Корзина передаёт компактный список ID товаров и количества через параметр start вида cart_1x2_4x1. Сервер бота должен отдельно обработать этот параметр. Сам сервер Telegram-бота в этот архив не входит: он ещё не был создан и подключён.
Для Mini App нужен опубликованный HTTPS-адрес сайта, настроенный через /setmenubutton в BotFather. Локальный адрес Live Server не подходит для покупателей. Интернет нужен для загрузки Telegram SDK.

## Текущий статус
Это демонстрационный каталог. Реальные платежи Stars, проверка оплаты, хранение заказов и выдача товаров не подключены. Цены и наличие — примеры. Токенов и секретов в проекте нет.

Логотип сохранён отдельно в assets/logo.png; шапка сохраняет текстовый знак текущего сайта.

## Изображения
Обложки принадлежат правообладателям. Перед коммерческим запуском проверьте право их использования.
Источники:
- Red Dead Redemption 2: https://owp.klarna.com/product/640x640/1911909895/Red-Dead-Redemption-II-%28PC%29.jpg?ph=true
- Minecraft: https://ethlan.fr/img/jeux/121.jpg
- Cyberpunk 2077: https://i5-mx.walmartimages.com/mg/gm/3pp/asr/6e7f323f-932c-4de4-a797-33a57da7c1e6.4b1b5987b6b39fd444b86d844ecc4fd1.jpeg
