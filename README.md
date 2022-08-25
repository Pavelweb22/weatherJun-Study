Weather

Проект для работы с API Яндекс погоды - https://yastatic.net/weather

Стартовый экран UITableViewController с поиском и добавлением нового города.
При загрузке проекта отправляется GET запрос к Яндекс API. Полученные данные декодируются в структурру данных и выводятся в UITableView где в каждой 
ячейке заполняется:
- Город
- Погодное описание (ясно, пасмурно и т.д.)
- Температура

При клике на ячейку выполняется переход в экран города. Полученные данные выводятся на экран деталей:
верхний stackview: Город, погодное описание, температура.
нижний stackview: давление, скорость ветра, минимальная и максимальная температура днем.
Также запрашивается иконка погодного описания. 
NavigationController для возврата на предыдущий экран.

По свайпу влево реализовано удаление города из списка.

При нажатии на кнопку "+" появляется AlertController и можно добавить новый город в список.

Реализован поиск по городам.

<img width="415" alt="Снимок экрана 2022-08-24 в 22 21 18" src="https://user-images.githubusercontent.com/98170830/186505504-f93cb3f9-028a-46c7-a306-057f59089a77.png">
<img width="418" alt="Снимок экрана 2022-08-24 в 22 22 05" src="https://user-images.githubusercontent.com/98170830/186505549-fe15abc9-024f-4f62-aaae-0f952a4271de.png">
<img width="411" alt="Снимок экрана 2022-08-24 в 22 22 44" src="https://user-images.githubusercontent.com/98170830/186505582-f2bd9e2e-d33c-44f8-afba-ecd48a9f5686.png">
<img width="414" alt="Снимок экрана 2022-08-24 в 22 23 10" src="https://user-images.githubusercontent.com/98170830/186505606-9a847691-2b03-4ba1-a612-c6cf281887af.png">
<img width="420" alt="Снимок экрана 2022-08-24 в 22 23 26" src="https://user-images.githubusercontent.com/98170830/186505636-7715f4ed-a9d2-477d-ac3a-7c014948a347.png">
<img width="412" alt="Снимок экрана 2022-08-24 в 22 23 49" src="https://user-images.githubusercontent.com/98170830/186505648-407d625b-f184-4617-bffb-e49236fc51f3.png">
