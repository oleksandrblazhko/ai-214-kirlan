### Словник атрибутів об’єктів
|Об'єкт|Атрибут|Короткий опис|Тип|Обмеження|
|:-----:|:-----:|:-----|:-----|:-----|
|ПП|Користувачі|Масив користувачів|user[]|об'єкти < 20|
|-----|-----|-----|-----|-----|
|Проведення аналізу безпеки|Параметри|Параметри безпеки|args[]|елементи < 100|
|Проведення аналізу безпеки|Дата|Дата проаедення аналізу|дата|значення > 0|
|-----|-----|-----|-----|-----|
|Звіт з безпеки|Дані|Дані для формування звіту|словник|елементи < 100|
|Звіт з безпеки|Параметри діаграми|Параметри побудови діаграми|plot|елементи < 20|
|-----|-----|-----|-----|-----|
|Створення пакету підтримки|Параметри|Параметри формування пакету|args[]|елементи < 100|
|Створення пакету підтримки|Дата|Дата створення пакету підтримки|Дата|значення > 0|
|-----|-----|-----|-----|-----|
|Пакет пвдтримки|Інструкції|Інструкції, якими наповнюється пакет|Рядок|символів < 1000|
|Пакет пілтримки|Макет документа|Параметри за якими формується документ|Рядок|символів < 1000|