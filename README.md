# The Simplest Browser Geoloc: Custom UI
Данный скрипт изменяет пользовательский интерфейс и упрощает некоторые действия.  
Игра находится на ранней стадии разработки, в ней регулярно происходят изменения. Используйте скрипт на свой страх и риск.

## Перечень изменений
* Различные правки пользовательского интерфейса
* Автоматическая очистка инвентаря, когда свободное место заканчивается. Можно настроить количество каждого предмета, которое должно оставаться после очистки.
* Автоматический выбор наименьшего, наибольшего или следующего по уровню ядра при апгрейде и деплое. Позволяет апгрейдить "лесенкой" для получения наибольшего количества опыта.
* Автоматический выбор самого мощного или последнего использованного катализатора при атаке.
* Зарядка точек из вкладки рефов в инвентаре без перехода к ним.
* Возможность записать свою текущую статистику и впоследствии сравнить её с актуальной.
* Список избранных точек. Можно наблюдать оставшееся количество дискаверов до выгорания или кулдаун до остывания точки.
* Уведомления об остывании избранных точек.
* Сортировка рефов в инвентаре по дистанции, заряду, команде и прочим параметрам.
* Подсветка точек на карте. На каждой точке может отображаться по два маркера, означающих, например, наличие рефа в инвентаре или то, была ли уже захвачена эта точка.
* Дополнительные опции кнопки дискавер: без получения предметов (только рефы) и без получения рефов (только предметы).
* Тонирование интерфейса браузера (адресной строки) в цвет команды при просмотре профиля или в цвет уровня при просмотре точки. Может потребоваться включить эту возможность в настройках браузера.
* ~~Удаление рефов с карточки точки.~~

*Зачёркнутые позиции были введены в игру.*


## Установка: Android
1. Установить Яндекс.Браузер: [ссылка](https://play.google.com/store/apps/details?id=com.yandex.browser&hl=ru&gl=US). Либо его модифицированную версию, где вырезано всё лишнее: [ссылка](https://4pda.to/forum/index.php?showtopic=473341&view=findpost&p=113472644). 
2. Установить Tampermonkey: [ссылка](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo). Ссылку открывать в Яндекс.Браузере. 
3. В списке каталога дополнений выдать Tampermonkey разрешение открывать файлы по ссылкам. 
4. В браузере нажать на иконку плагина Tampermonkey и перейти в Dashboard. 
5. На открывшейся странице плагина перейти справа во вкладку “Utilities”. 
6. Внизу в поле “Import from URL” вставить ссылку на скрипт нажать “Install”: https://nicko-v.github.io/sbg-cui/index.min.js
7. После открытия окна с кодом скрипта повторно нажать “Install”. 
8. Обновить страницу с игрой. Скрипт должен запуститься и внести изменения.  

Обновление скрипта осуществляется путём нажатия иконки Tampermonkey в адресной строке и выбора “Utilities -> Check for userscripts updates”.  
Видео по установке: [ссылка](https://t.me/sbg_forum/36282/36447).

## Установка: iOS
1. Установить Userscripts: [ссылка](https://apps.apple.com/app/id1463298887).
2. Установить Shortcuts/Команды: [ссылка](https://apps.apple.com/app/id1462947752).
3. Сохранить Команду загрузки последней версии скрипта: [ссылка](https://www.icloud.com/shortcuts/5b5bafaed7d142229989785d7b92d97c).
4. Запустить Команду. Выдать в процессе все запрашиваемые разрешения. Должно появиться уведомление “Загружена версия x.y.z”.
5. Открыть приложение Userscripts, нажать “Set Userscripts Directory”, выбрать путь iPhone/Userscripts/. В этой папке у вас уже должен быть скрипт, полученный в п. 4.
6. Открыть Safari, нажать кнопку aA в левой части адресной строки. Выбрать “Управлять расширениями”, включить расширение Userscripts.
7. Повторно нажать aA в адресной строке, в этом меню появится пункт “Userscripts”. Нажать на него и выдать постоянное разрешение на доступ к сайту.
8. Обновить страницу с игрой. Скрипт должен запуститься и внести изменения.  

Обновление скрипта осуществляется путём запуска Команды Update SBG CUI.

## Обратная связь
Обсудить работу скрипта, предложить свои идеи или пожаловаться на баги можно в соответствующей ветке игрового форума в Телеграм: [ссылка](https://t.me/sbg_forum/36282).
