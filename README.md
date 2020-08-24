# RoyaleEvent
Версия: 0.0.2
Плагин для Spigot, позволяющий запустить свой ивент с Battle Royale(как в Fortnite/PUBG и т.д.).<br>
Нативная версия Spigot: 1.12.2<br>
Возможно поддерживается 1.13+<br>
[Скачать](https://github.com/hevav/RoyaleEvent/releases)

## Установка
-   Скачайте и установите плагин по ссылке выше
-   Настройте режимы эйрдропа и зоны в config.yml (по умолчанию настроено на 20-40минут игры)
-   Настройте центр карты(автобус), используя /royalemiddle
-   По желанию выдайте право royaleevent.interact админам, чтобы позволить им играть с плагином.

## Использование
-   Запустите ивент через /royalestart
-   Ожидайте окончания ивента(1 человек в Gamemode Survival на карте) или принудительно остановите ивент через /royalestop

## Помощь
### Строительство
В плагине продуманная система строительства. Существует три вида блоков:
-   Дерево - добывается из дерева, любого деревянного предмета, кактусов или мертвых кустов
-   Кирпич - добывается из кирпича или любого кирпичного предмета
-   Железо - добывается из железа и железных прутьев

Эти блоки занимают слоты с 7 по 9
Так же сущетвует три вида структур, каждая тратит по 5 блоков:
-   Стена
-   Пол
-   Лестница

### Напитки
Существует 1 вид напитка - восстановитель хавки. Восстанавливает 10 единиц хавки.

### Гаджеты
Существует 2 вида гаджетов:
-   Костёр. Позволяет хилиться
-   Батут. Позволяет прыгать

### Оружия
Оружия имеют полностью разные настройки:
Оружие | Кол-во патронов | Время перезарядки | Скорость пули | Отдача | Урон | КД | Кол-во пулей
--- | --- | --- | --- | --- | --- | --- | ---
Дробовик | 6 | 12 | 6 | 4 | 45 | 1.5 | 3
Пистолет | 20 | 3 | 8 | 1 | 25 | 6.75 | 1
Автомат | 40 | 4 | 6 | 2 | 35 | 5.5 | 1
Винтовка | 1 | 18 | 15 | 10 | 60 | 5.5 | 1
ПП | 25 | 5 | 8 | 2 | 35 | 3.5 | 1

## Thanks to:
-   [Усику](https://vk.com/robot2284) и его команде строителей за то что пробовал скинуть плагин ФывФыву и за помощь с настройкой плагина
-   [rebalez](https://www.youtube.com/channel/UC3bTvS1RXc8wgwDmBdHiywQ) за настройку оружий и XXX_Fortnite
-   Fersept за [ресурспак](https://ws1.hevav.dev/cloud/fortnite.zip) и идею с Chunkable
-   [Митингеру](https://github.com/meetinger) за помощь с реализацией Chunkable
-   SkyHidden за то что мешала на тестах плагина :)