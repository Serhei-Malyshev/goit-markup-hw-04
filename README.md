# goit-markup-hw-04

https://www.figma.com/file/1ehrLBauvVFu4mVhxsHzyZ/Web-Studio-(Version-2.1)?node-id=1%3A493

1. Вставил фон, указл путь к файлу background-image: url(../img/toweb/hero/Hero_bg.jpg);

2. убрал повтор background-repeat: no-repeat;

3. растянул по всей секции background-size: cover;

4. центрировал background-position: center;

5. Задал максимальную ширину 1600px;

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
