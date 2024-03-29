# Переводы для модификаций XCOM 2 на русский

Здесь собраны все переводы модов XCOM 2, что я делал. Они здесь либо по причине того, что у мода не было перевода, либо что перевод мне не понравился.

Git (и как следствие, GitHub) не умеет работать с UTF-16 LE (BOM), поэтому они отображаются как бинарные. Я планирую в будущем сделать автоматическое конвертирование, чтобы было проще проще работать. Сейчас пока я обновляю файлы вручную.

## Структура

* **src** – файлы текста для работы с GitHub.
* **dist** – готовые файлы, сконвертированные в UTF-16 LE с BOM.

В каждой из этих папок моды разбиты по ID пакета, чтобы всё не слиплось. Единственное различие: в папке **src** файлы локализации хранятся в `<ID пакета>`, а в **dist** – в `<ID пакета>/Localization`, чтобы можно было её просто скопипастить.

## Как использовать перевод

1. [Скачиваете копию репозитория](https://github.com/RadRussianRus/xcom2-mods-ru/archive/master.zip).
2. Ищете нужный мод по ID пакета (можете использовать, к примеру, [Alternative Mod Launcher](https://github.com/X2CommunityCore/xcom2-launcher), чтобы быстро найти).
3. Копируете файлы из него в папку с вашим модом.

## Текущие переводы

* `AllEquipmentsinSkirmish` – [Skirmish Mode+](https://steamcommunity.com/sharedfiles/filedetails/?id=1535761480)
* `CinematicRapidFireW` – [[WOTC] Cinematic Rapid Fire (and other abilities)](https://steamcommunity.com/sharedfiles/filedetails/?id=1124794449)
* `LEBPortrait` – [WOTC - Configurable Headshots](https://steamcommunity.com/sharedfiles/filedetails/?id=1273848330)
* `ModConfigMenu` – [[WotC] Mod Config Menu](https://steamcommunity.com/sharedfiles/filedetails/?id=667104300)
