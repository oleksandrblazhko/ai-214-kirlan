|FR id|TC id|Опис кроків тестового сценарію|Опис очікуваних результатів|
|:-----:|:-----:|:-----|:-----:|
|FR1.1|TC 1.1|Початкові умови: користувач ввів коректні дані<br> Кроки сценарію:<br> email = kirlan@gmail.com <br> старий пароль = 1234qwerty <br> новий пароль = 5678qwerty|Результат = 1|
|FR1.1|TC 1.2|Початкові умови: відсутні<br> Кроки сценарію:<br> email = kirlangmailcom <br> старий пароль = 1234qwerty <br> новий пароль = 5678qwerty|Результат = -1|
|FR1.1|TC 1.3|Початкові умови: відсутні<br> Кроки сценарію:<br> email = kirlan@gmail.com <br> старий пароль =  <br> новий пароль = 5678qwerty|Результат = -2|
|FR1.1|TC 1.4|Початкові умови: відсутні<br> Кроки сценарію:<br> email = kirlan@gmail.com <br> старий пароль = 1234qwerty <br> новий пароль = |Результат = -3|
|FR1.1|TC 1.5|Початкові умови: відсутні<br> Кроки сценарію:<br> email = kirlan@gmail.com <br> старий пароль = 1234qwerty <br> новий пароль = 1234qwerty|Результат = -3|