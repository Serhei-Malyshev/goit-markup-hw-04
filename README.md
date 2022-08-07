# goit-markup-hw-04

https://www.figma.com/file/1ehrLBauvVFu4mVhxsHzyZ/Web-Studio-(Version-2.1)?node-id=1%3A493

1. Вставил фон, указл путь к файлу background-image: url(../img/toweb/hero/Hero_bg.jpg);

2. убрал повтор background-repeat: no-repeat;

3. Растянул по всей секции background-size: cover;

4. центрировал background-position: center;

5. Задал максимальную ширину 1600px; max-width: 1600px;

6. Расположил по центру margin: 0 auto;

ставлю иконки соцсетей в секции TEAM

1. формирую структуру html для иконок: создаю список ul и создаю класс team-soc_icon-formation;

2. убираю маркеры в ul и создаю класс для формирования кнопок: <ul class="list team-soc_icon-formation">;

3. создал 4 li сделал ссылками и убирал подчеркивание <li class=""><a href="" class="link"></a></li>;

4. создал стили li и ссылкам <li class="team-soc_icon-decor"><a href="" class="link team-soc_icon-link_formation"></a></li>

5. создаю временный фон для иконок в team-soc_icon-link: width: 44px; height: 44px; border-radius: 50%; background-color: #429e3f; display: block;

6. Работаю с ul, задаю праметр в team-soc_icon-formation: display: flex;

7. Размещаю иконнки по центру в team-soc_icon-formation: justify-content: center;

8. задаю всем одинаковые отступы в team-soc_icon-formation: gap: 10px;

9. качаю иконки в формате SVG и оптимизирую в сервисе: https://jakearchibald.github.io/svgomg/

10. Создаю спрайт в https://icomoon.io/

11. Вставляю созданый спрайт в каталог с иконками

12. Оптимизирую спрайт повторно в svgomg с включеной функцыей Prettify murkup

13. Внутри ссылки с иконкой создаю тег svg <li class="team-soc_icon-decor"><a href="" class="link team-soc_icon-link_formation"><svg></svg></a></li>

14. Внутри svg создаю стиль <svg class="team-soc_icon-svg_style"></svg>

15. создаю ссылку на спрайт <use href="../img/toweb/icon/soc_icon.svg"></use>

16. Обворачиваю тегом svg ссылку на спрайт <svg class="team-soc_icon-svg_style"><use href="../img/toweb/icon/soc_icon.svg"></use></svg>

17. Добавил путь на иконку в спрайте <use href="../img/toweb/icon/soc_icon.svg#icon-instagram_icon">

18. Убрал цвет у иконок в спрайте, удалил атрибуты fill и style в спрайте

19. Задал размер в svg <svg class="team-soc_icon-svg_style" width="20" height="20"><use href="../img/toweb/icon/soc_icon.svg#icon-instagram_icon"></use></svg></a>

20. Меняю иконку в team-soc_icon-link_formation с display: block; на display: flex;

21. Центрирую иконку по горизонтальной оси justify-content: center; и вертикальной оси align-items: center;

22. Меняю цвет иконки в css: team-soc_icon-svg_style тегом fill: #ffffff;

23. Меняю фон иконки при наведении курсора, создаю :hover для team-soc_icon-link_formation: создаю .team-soc_icon-link_formation:hover с параметром background-color: var(--inter-color);

24. Добавляю смену цвета фона при фокусе: .team-soc_icon-link_formation:focus

25. Добавляю смену цвета иконки при ховере тегом fill: .team-soc_icon-link_formation:hover .team-soc_icon-svg_style с параметром fill: rgb(224, 194, 93);

26. Добавляю смену цвета иконки при фокусе тегом fill: .team-soc_icon-link_formation:focus .team-soc_icon-svg_style с параметром fill: rgb(224, 194, 93);

27. Применил стили ко всем иконкам

Секция "ПОСТІЙНІ КЛІЄНТИ"

1. Выкачиваю иконки с макета

2. Оптимизирую в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

3. Создаю спрайт в https://icomoon.io/

4. Оптимизирую спрайт в https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

5. Убрал цвета в иконках delete fill and style

6. Создаю секцию

7. Формирую секцию - добавляю class="container"

8. Создаю заголовок "Постійні клієнти" <h2>

9. Задаю стили заголовку <h2 class="clients-title">Постійні клієнти</h2>

10. Создаю стили заголовку в css - добавляю параметры, расчитываю множитель, удаляю лишнее

11. Центрирую заголовок text-align: center;

12. Создаю список ul на 6 li в котором буду размещать иконки создал 4 li

13. Убрал маркеры в ul <ul class="list">

14. Cделал li ссылками и убрал подчеркивание <li class=""><a href="" class="link"></a></li>;

15. Создаю кейсы для логотипов в html: <li class=""><a href="#" class="link clients-logo-logo_casing"></a>

16. Создаю кейс в css: .clients-logo-logo_casing и задаю параметр блочных элементов display: block;

17. Создаю параметры кейса для лого по макету в css: width: 170px; height: 92px; border: 1px solid #afb1b8; border-radius: 4px;

18. Внутри ссылки с иконкой создаю тег svg <li class=""><a href="" class="link clients-logo-logo_casing"><svg></svg></a>

19. Формирую расположение элементов <ul class="list clients-logo-formation">

20. Центрирую кейсы в контейнере: justify-content: center;

21. Задаю внешний отступ кейсам от заголовка margin-top: 50px;

22. Cоздаю ссылку на спрайт с логотипами <use href="./img/toweb/clients/logoclients.svg"></use> и вставляю в <svg></svg>

23. Добавляю путь к лого из спрайта в ссылку <use href="./img/toweb/clients/logoclients.svg#icon-Logoclients1">

24. Задаю размеры лого в html разметке <a href="" class="link clients-logo-logo_casing"><svg width="106" height="60"><use href="./img/toweb/clients/logoclients.svg#icon-Logoclients1"></use></svg></a>

25. Создаю внутренние отступы в кейсах для лого padding: 16px 32px;

26. Меняю цвет логотипам: создаю в css .clients-logo-style с параметром fill: rgba(175, 177, 184, 1) в html: <a href="" class="link clients-logo-logo_casing"><svg class="clients-logo-style" width="106" height="60"><use href="./img/toweb/clients/logoclients.svg#icon-Logoclients1"></use></svg></a>

27. Меняю цвет рамки при наведении курсора: .clients-logo-logo_casing:hover, .clients-logo-logo_casing:hover {border: 1px solid var(--inter-color);}

28. Меняю цвет лого при наведении курсора: .clients-logo-logo_casing:hover .clients-logo-style {fill: var(--inter-color);}

29. Меняю цвет лого при фокусе: .clients-logo-logo_casing:focus .clients-logo-style {fill: var(--inter-color);

30. Создаю отступы через gap по макету 30px в css:

31. Задаю правильный размер кейсов .clients-logo_casing-basis_calc {flex-basis: calc((100% - 5 \* 30px) / 6);} в html:
<li class="clients-logo_casing-basis_calc">

32. Обворачиваю контейнер для внутрених отступов между секциями 94px в html: <section class="clients-wrap"> в css: padding: 94px 0;

FEATURES

1. Выкачиваю иконки с макета

2. Оптимизирую в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

3. Создаю спрайт в https://icomoon.io/

4. Оптимизирую спрайт в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

5. Создаю кейс для логотипа <a href="#" class="link features-logo-logo_casing"></a>

6. Создаю параметры кейса для лого по макету в css: width: 270px; height: 120px; background: #F5F4FA; border-radius: 4px;

7. Задаю блочный параметр в .features-logo-logo_casing: display: block;

8. Ставлю иконку в кейс тегом svg и use, задаю размер по макету <a href="#" class="link features-logo-logo_casing"><svg width="70" height="70"><use href="./img/toweb/features/features_logo.svg#icon-antenna"></use></svg></a>

9. Рзмещаю иконки в кейсе согласно макету в css .features-logo-logo_casing padding: 25px 100px;

10. Центрирую кейс в css: .features-logo-logo_casing margin: 0 auto;

11. Создаю нижний отступ от кейса 30px в css: .features-logo-logo_casing margin-bottom: 30px;

12. Отключаю курсор при наведении в css: .features-logo-logo_casing: cursor: default;

HEADER ICON CONTACT

1. Выкачиваю иконки с макета в фигме

2. Оптимизирую в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

3. Создаю спрайт в https://icomoon.io/

4. Оптимизирую спрайт в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

5. Создаю ссылку на иконку <svg><use href="./img/toweb/header/icon_contact.svg#icon-smartphone-1"></use></svg>

6. Изменяю размер иконки <a href="mailto:info@devstudio.com" target="_blank" class="header-mail_link_style header-contact-mod link"><svg width="16" height="12"><use href="./img/toweb/header/icon_contact.svg#icon-envelope-hover-1"></use></svg>info@devstudio.com</a>

7. Создаю стиль для иконки .header-contact-icon_contact_style и вставляю в html: <svg class="header-contact-icon_contact_style" width="10" height="16"><use href="./img/toweb/header/icon_contact.svg#icon-smartphone-1"></use></svg>+38 096 111 11 11</a>

8. Задаю отступ в css: .header-contact-icon_contact_style margin-right: 10px;

9. Применяю стиль ссылки к иконке в css: .header-contact-icon_contact_style fill: currentColor;

FOOTER CONNECT SECTION

1. Обвернул уже созданый контент с лого и адрессом <div class="footer-logo_and_address-wrap">

2. Создал обвертку для нового контента <div class="footer-connect-wrap">

3. Флэксую оба кейса <div class="footer-logo_and_address_and_connect-flex">

4. Задал левый оступ 70px от кейса connect: .footer-connect-wrap: margin-left: 70px;

5. Выровнял кейсы по базовой линии их текстового содержимого: .footer-logo_and_address_and_connect-flex: align-items: baseline;

FOOTER CONNECT TITLE

1. Задал стиль заголовку "Приєднуйтесь" <h3 class="footer-connect-title_style">Приєднуйтесь</h3>

2. Задал заголовку все большие буквы: .footer-connect-title_styletext-transform: uppercase;

3. Применил заголовку стили из макета фигмы, использовал множитель

CASING FOOTER CONNECT SOC ICON

1. Создал список ul на 4 li: ul>li\*4 (Emmet - быстрая верстка)

2. Убрал маркеры в ul и создал класс для формирования кнопок: <ul class="list">

3. Скачал иконки с макета

4. Оптимизировал иконки: https://jakearchibald.github.io/svgomg/ с включеной функцией Prettify murkup

5. Создал спрайт: https://icomoon.io/

6. Оптимизирвал спрайт: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

7. Удалил цвета и стили иконок в спрайте fill и style

8. Создал внутри li ссылку <li><a href="#"></a></li>

9. Внутри ссылки создал тег svg <li><a href="#"><svg></svg></a></li>

10. Внутри тега svg создал тег use <li><a href="#"><svg><use></use></svg></a></li>

11. Создал класс дэкора иконкам <a href="#" class="footer-connect-soc_icon_decor">

12. Создал окружность и фон для иконок .footer-connect-soc_icon_decor: Фон : fill: rgba(255, 255, 255, 1); Высота: height: 44px; Ширина: width: 44px; Окружность: border-radius: 50%;

13. Задал ширину и высоту иконок по макету <svg width="20" height="20">

14. Создал стили для иконок <svg class="footer-connect-soc_icon_style">

15. Применл стили по макету: .в css footer-connect-soc_icon_style: Цвет: fill: rgba(255, 255, 255, 1);

16. Создал класс для расположения иконок по горизонтали: <ul class="footer-connect-soc_icon-formation">

17. Задал параметры для расположения иконок по горизонтали: .footer-connect-soc_icon-formation: display: flex;

18. Указал путь иконки из спрайта <use href="./img/toweb/footer/connect_soc_icon.svg#icon-instagram1"></use>

19. Центрирую иконки: .footer-connect-soc_icon_decor: align-items: center; justify-content: center; и чтобы эти параметры сработали ставлю display: flex;

20. Задал верхний отступ в .footer-connect-soc_icon-formation: margin-top: 20px;

21. Создал отступы между иконками в .footer-connect-soc_icon-formation: gap: 10px;

22. Создал эффекты наведения курсора и фокуса для фона иконки: .footer-connect-soc_icon_decor:hover, .footer-connect-soc_icon_decor:focus: background: var(--inter-color);

23. Создал левый отступ от кейса connect: .footer-connect-wrap: margin-left: 70px;
