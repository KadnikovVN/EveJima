# EveJima
Tool for game Eve Online

﻿# WormholeLocator
Version 1.20

В одном из недавних патчей глубоко мною уважаемые CCP, по причинам, мне неизвестным (озвученные ими не вызывают никакого доверия, что, впрочем, не имеет никакого значения), тяжелым напильником выпилило IGB. Мне будет не хватать возможности смотреть картинки обнаженных блондинок, посылаемых мне моими сокорповцами, не переключаясь из игры, но с этим я мог бы смириться. То, что действительно мне мешает - это невозможность открыть свернутый IGB, нажать на уже открытой вкладке http://wh.pasta.gg на милые моей душе стрелочки и получить исчерпывающую информацию о том, у какую ВХ меня занесло и чего мне там ждать. Я житель ВХ и вы, как жители ВХ, должны меня понимать. Вместо двух действий - открытия IGB и обновления страницы я вынужден делать целую кучу действий. Во-первых я должен скопировать название ВХ-системы. Для этого мне нужно потянуть это название в чат и там выделить его. Во-вторых я должен альтабнуться и найти браузер с открытым сайтом-определителем ВХ. (это может быть как Pasta так и Superute, Ellatha или Dotlan. У меня, как правило, открыта целая куча браузров и табов в них. На открытом сайте я должен копипастнуть название ВХ, рефрешнуть страницу и ждать появления информации. Все это время я не контролирую подсках, грид и время своей инстантклоки, что меня чрезвычайно напрягает.

Существующее положение дело меня не устраивало и я написал EveJima.

Возможности программы:

1. В оконном и полнооконном форматах закрепленный WHL постоянно находится в топе (Overlay) и постоянно доступен для получения информации и использования.

1.1 В развернутом состоянии в режиме реального времени (получение данных от ССР по вашему местоположению происходит раз в две секунды)

![enter image description here](http://storage2.static.itmages.com/i/16/1202/h_1480719224_7002968_a3571be0a8.png)

1.2 В компактном состоянии так же постоянно обновляет информацию о текущей солнечной системе, вынесенное в заголовок окна WHL

![enter image description here](http://storage3.static.itmages.com/i/16/1202/h_1480719226_7151251_357ff50bc2.png)

1.3 Нажатие кнопок "Zkilboard" "Superpute" "Ellatha" "Dotlan" открывают во встроенном в WHL браузере (что означает что он так же Overlay для Евы) сайты с уже прописанной солнечной системой, в которой вы находитесь.

![enter image description here](http://storage9.static.itmages.com/i/16/1202/h_1480719220_4848729_25d4dafa7f.png)

![enter image description here](http://storage1.static.itmages.com/i/16/1202/h_1480719222_9547126_eff049aa92.png)

2. Информация о пилотах.

2.1 Вы можете выбрать пилотов из чата Евы (нажав Crl-A и потом Crl-C на списке пилотов любого чата) или ввести имя пилота вручную в поле "Selected Pilot".

![enter image description here](http://storage4.static.itmages.com/i/16/1202/h_1480719227_8303427_7525d52264.png)

2.2 Нажатие кнопки "Show Zkillboard" загружает во встроенный браузер информацию о выбранном пилоте с сайта https://zkillboard.com

![enter image description here](http://storage5.static.itmages.com/i/16/1202/h_1480719228_9488847_a5682351dc.png)

2.3 Нажатие кнопки "Show Eve Hant" загружает во встроенный браузер информацию о выбранном пилоте с сайта http://eve-hunt.net

![enter image description here](http://storage5.static.itmages.com/i/16/1202/h_1480719228_9415091_7550af5123.png)

2.4 Любой запуск поиска информации по пилоту сохраняет его в истории поиска и вы можете использовать ее повторно

![enter image description here](http://storage6.static.itmages.com/i/16/1202/h_1480719231_3625607_fff4ea08dc.png)

3. История координат и сигнатур. Как коренной житель ВХ я каждый день занимаюсь сканом сигнатур в домашней системе и за ее пределами. Каждый мой логин начинается с удаления координат, чьи сигнатуры исчезли с моего последнего логина, и высканиванием новых сигнатур. Я иду по списку кодов сигнатур в координатах и сверяю их со списком сигнатур. Занятие скучное. WHL позволил мне сократить эту операцию до двух кликов мышкой.

3.1 Копируем букмарки системы и выгружаем их нажав кнопку "Paste Location Bookmarks"

![enter image description here](http://storage6.static.itmages.com/i/16/1202/h_1480719230_2542242_d4255142e3.png)

3.2 Копируем сигнатуры и выгружаем их нажав кнопку "Paste Cosmic Signatures"

![enter image description here](http://storage7.static.itmages.com/i/16/1202/h_1480719231_1917116_8520c84b7e.png)

3.3 Нажатие кнопки "Clear"  оставляет в левой части координаты, которые нужно удалить, а в правой части сигнатуры, которые нужно высканить.

![enter image description here](http://storage8.static.itmages.com/i/16/1202/h_1480719232_2762097_7615a30df2.png)

4. Программа не требует у вас API ключей, или пароля с аккаунтом. Авторизация происходит на самом сайте ССР

![enter image description here](http://storage1.static.itmages.com/i/16/1202/h_1480719234_5454079_9817ccdfbf.png)

на который вы попадаете из программы WHL

![enter image description here](http://storage9.static.itmages.com/i/16/1202/h_1480719232_4240389_6cad6f58a9.png)

WHL не имеет доступа ни к чему из вашей приватной информации, кроме токена разрешающего получать данные о вашем местоположении в игре из системы EVE CREST

5. Проверка на вирусы
    https://www.virustotal.com/ru/file/841f205b0a7f1eb11b5be3050e788a91977b1eeca1f49d3e17e737d10eb6b1df/analysis/1480718662/


![enter image description here](http://storage8.static.itmages.com/i/16/1202/h_1480719232_6766386_45b6e253f1.png)

6. Ссылка для скачивания
    https://drive.google.com/open?id=0B-7rpbHZiUJ6LXZrX0xva3JPZHc


Делалось для своих, своими и пользуется. Если кому-то пригодится - буду рад.

С уважением.

