# goit-markup-hw-05

https://www.figma.com/file/1ehrLBauvVFu4mVhxsHzyZ/Web-Studio-(Version-2.1)?node-id=1%3A2125

BACKGROUND IMAGE HERO

1. Скачал фоновое изображение с макета

2. Создал стиль для фонового изображения: <section class="hero-content-formation">

3. Указал путь к фоновому изображению: .hero-content-formation: background-image: url(../img/toweb/hero/Hero_bg.jpg);

4. Убрал повтор: .hero-content-formation > background-repeat: no-repeat;

5. Растянул по всей секции: .hero-content-formation > background-size: cover;

6. Центрировал: .hero-content-formation > background-position: center;

7. Задал максимальную ширину: .hero-content-formation > max-width: 1600px;

8. Расположил по центру: .hero-content-formation > margin: 0 auto;

9. Добавил функцию градиента по макету (overlay) к фоновому изображению (Затемнил): .hero-content-formation > background-image: linear-gradient(rgba(47, 48, 58, 0.4), rgba(47, 48, 58, 0.4)), url(../img/toweb/hero/Hero_bg.jpg);

TEAM SOC ICON

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

25. Центрирую иконки > задаю иконке флекс параметр: .clients-logo-logo_casing > display: flex;

26. Центрирую иконки по горизонтальной оси: .clients-logo-logo_casing > justify-content: center;

27. Центрирую иконки по вертикальной оси: .clients-logo-logo_casing > align-items: center;

28. Меняю цвет логотипам: создаю в css .clients-logo-style с параметром fill: rgba(175, 177, 184, 1) в html: <a href="" class="link clients-logo-logo_casing"><svg class="clients-logo-style" width="106" height="60"><use href="./img/toweb/clients/logoclients.svg#icon-Logoclients1"></use></svg></a>

29. Меняю цвет рамки при наведении курсора: .clients-logo-logo_casing:hover, .clients-logo-logo_casing:hover {border: 1px solid var(--inter-color);}

30. Меняю цвет лого при наведении курсора: .clients-logo-logo_casing:hover .clients-logo-style {fill: var(--inter-color);}

31. Меняю цвет лого при фокусе: .clients-logo-logo_casing:focus .clients-logo-style {fill: var(--inter-color);

32. Создаю отступы через gap по макету 30px в css:

33. Задаю правильный размер кейсов .clients-logo_casing-basis_calc {flex-basis: calc((100% - 5 \* 30px) / 6);} в html:
<li class="clients-logo_casing-basis_calc">

34. Обворачиваю контейнер для внутрених отступов между секциями 94px в html: <section class="clients-wrap"> в css: padding: 94px 0;

FEATURES

1. Выкачиваю иконки с макета

2. Оптимизирую в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

3. Создаю спрайт в https://icomoon.io/

4. Оптимизирую спрайт в сервисе: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

5. Создаю кейс для логотипа <a href="#" class="link features-logo-logo_casing"></a>

6. Создаю параметры кейса для лого по макету в css: width: 270px; height: 120px; background: #F5F4FA; border-radius: 4px;

7. Задаю блочный параметр в .features-logo-logo_casing: display: block;

8. Ставлю иконку в кейс тегом svg и use, задаю размер по макету <a href="#" class="link features-logo-logo_casing"><svg width="70" height="70"><use href="./img/toweb/features/features_logo.svg#icon-antenna"></use></svg></a>

9. Центрирую иконки > задаю иконке флекс параметр: .features-logo-logo_casing > display: flex;

10. Центрирую иконки по горизонтальной оси: .features-logo-logo_casing > justify-content: center;

11. Центрирую иконки по вертикальной оси: .features-logo-logo_casing > align-items: center;

12. Центрирую кейс: .features-logo-logo_casing margin: 0 auto;

13. Создаю нижний отступ от кейса 30px в css: .features-logo-logo_casing margin-bottom: 30px;

14. Отключаю курсор при наведении в css: .features-logo-logo_casing: cursor: default;

HEADER ICON CONTACT

1. Скачал иконки с макета в фигме

2. Оптимизировал: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

3. Создал спрайт: https://icomoon.io/

4. Оптимизировал спрайт: https://jakearchibald.github.io/svgomg/ с включеной функцыей Prettify murkup

5. Создал ссылку на иконку <use href="./img/toweb/header/icon_contact.svg#icon-smartphone-1">

6. Изменл размер иконки <svg width="16" height="12">

7. Создал стиль для иконки: <svg class="header-contact-icon_contact_style">

8. Задаk отступ: .header-contact-icon_contact_style margin-right: 10px;

9. Наследовал стиль ссылки на иконку: .header-contact-icon_contact_style: fill: currentColor;

10. Центрировал иконку: .header-mail_link_style: display: flex; align-items: center; align-items: center;

FOOTER CONNECT SECTION

1. Обвернул уже созданый контент с лого и адрессом <div class="footer-logo_and_address-wrap">

2. Создал обвертку для нового контента <div class="footer-connect-wrap">

3. Флэксую оба кейса <div class="footer-logo_and_address_and_connect-flex">

4. Задал левый оступ 70px от кейса connect: .footer-connect-wrap: margin-left: 70px;

5. Выровнял кейсы по базовой линии их текстового содержимого: .footer-logo_and_address_and_connect-flex: align-items: baseline;

FOOTER CONNECT TITLE

1. Задал стиль тексту "Приєднуйтесь", указал важность текста <strong class="footer-connect-title_style">Приєднуйтесь</strong>

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

PORTFOLIO SHADOW ON HOVER

1. Обвернул карточки в ссылки <a href="" class="link">

2. Создал обвертку для тени в карточках: <div class="portfolio-card-shadow_hover_wrap">

3. Создал тень по макету: .portfolio-card-shadow_hover_wrap: box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06), 1px 4px 6px rgba(0, 0, 0, 0.16);

4. Задал тень при ховэре: .portfolio-card-shadow_hover_wrap:hover: box-shadow: 0px 1px 1px rgba(0, 0, 0, 0.12), 0px 4px 4px rgba(0, 0, 0, 0.06), 1px 4px 6px rgba(0, 0, 0, 0.16);

FILTER BUTTON SHASOW ON HOVER AND FOCUS

1. Убрал обводку при фокусе на кнопку: <button type="button" class="input">

2. Добавил тень при ховере и фокусе: .filter-button-mod:hover, .filter-button-mod:focus > box-shadow: 0px 3px 1px rgba(0, 0, 0, 0.1), 0px 1px 2px rgba(0, 0, 0, 0.08), 0px 2px 2px rgba(0, 0, 0, 0.12);

HEADER LINK UNDERLINING

1. Создал псевдоэлемент линиии подчеркивания: .header-nav_menu-link_underlining::after

2. Добавил класс линии подчеркивания каждой ссылке

3. Задал параметры линии подчеркивания по макету: .header-nav_menu-link_underlining::after display: block; width: 100%; height: 4px; border-radius: 2px; background-color: #2196f3; (можно растянуть линию подчеркивания на максимальное пространство: .header-nav_menu-link_underlining: flex-grow: 1;)

4. Задал параметр content: .header-nav_menu-link_underlining::after: content: "";

5. Задал абсолютное позиционирование: .header-nav_menu-link_underlining::after: position: absolute;

6. Задал relative блоку в котором будет позиционироваться нижние подчеркивание: .header-nav_menu_relative: position: relative;

7. Разместил подчеркивание снизу блока с ссылкой: bottom: 0;
