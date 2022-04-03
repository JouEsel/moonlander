# Моя раскладка Moonlander
Это моя раскладка для клавиатуры Moonlander. Подробнее о Moonlander можно почитать в [статье от @optozorax](https://optozorax.github.io/p/my-keyboard-layout/).

Вследствие того, что я не умею кодить на C, мне пришлось изменять системные раскладки с помощью [MSKLC](https://optozorax.github.io/p/my-keyboard-layout/#kak-v-klaviaturu-zasunut-svoiu-bukvennuiu-i-prepinakovuiu-raskladku).

## Установка для Windows
-> [Моя раскладка на Oryx](https://configure.zsa.io/moonlander/layouts/OydL3/latest/0)

Скачиваем `.bin` файл прошивки и [программу для прошивки Wally](https://www.zsa.io/wally/).

Устанавливаем Wally, запускаем и выбираем `.bin` файл прошивки. Переводим клавиатуру в [режим загрузчика](https://docs.qmk.fm/#/newbs_flashing?id=put-your-keyboard-into-dfu-bootloader-mode) нажатием скрепкой по спрятанной кнопке RESET.

Скачиваем и устанавливаем [MSKLC](https://www.microsoft.com/en-us/download/details.aspx?id=102134).

Скачиваем из репозитория `.klc` файлы раскладок и загружаем в MSKLC. Во меню Project выбираем пункт Build DLL and Setup Package. Переходим в предложенную папку и устанавливаем раскладки файлами `setup.exe`.

Переходим в Параметры Windows -> Время и язык -> Язык -> Параметры языка (Русский / Английский) и удаляем старую раскладку, оставляя только раскладки "Русская - Custom". Перезагружаем систему.
