# План тестирования формы заявки для записи на курс "Тестировщик ПО" сайта Netology.ru
## Вид тестирования: 
- Для данной задачи будет применено модульное тестирование.
## 1. Cценарии автоматизации тестирования:

### негативные сценарии:

-

В поле "Имя" ввести - одну букву

В поле телефона - например: +7(987)1234567

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем "Имя" появится сообщение "Должно быть не менее 2 букв"

-

В поле "Имя" ввести - буквы и цифры

В поле телефона - например: +7(987)1234567

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем "Имя" появится сообщение "Имя должно состоять из букв"

-

В поле "Имя" ввести - например Фе.дя

В поле телефона - например: +7(987)1234567

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем "Имя" появится сообщение "Имя должно состоять из букв"

-

В поле "Имя" ничего не писать

В поле телефона - например: +7(987)1234567

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем "Имя" появится сообщение "Обязательное поле"

-

В поле "Имя" ввести - например Федя

В поле телефона - например: 1234567

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем с номером телефона появится сообщение "Номер в формате +7 (999) 999-99-99"

-

В поле "Имя" ввести - например Федя

В поле телефона - например: +7(987)1234567891011

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем с номером телефона появится сообщение "Номер в формате +7 (999) 999-99-99"

-

В поле "Имя" ввести - например Федя

В поле телефона - ничего не писать

Нажать на кнопку "Записаться"

Ожидаемый результат: Под полем с номером телефона появится сообщение "Обязательное поле"


### позитивный сценарий:

-

В поле "Имя" ввести - например Федя

В поле телефона - например: +7(987)1234567

Нажать на кнопку "Записаться"

Ожидаемый результат: Появится всплывающая окно с надписью: "Ваша заявка отправлена, наш менеджер свяжется с вами в ближайшее время"


## Используемые инструменты:

- Intellij IDEA - итегрированная среда разработки программного обеспечения.
- Java JDK 11 - язык програмирования.
- Gradle - проект-менеджер автоматической сборки.
- Lombok - библиотека, которая сокращает количество написанного кода, улучшая читаемость.
- Faker - плагин для генерации случайных тестовых данных.
- JUnit 5 - фреймворк для автоматизации тестирования.
- Github Actions - сервис для автоматической проверки тестов.
- Allure - будет необходим для предоставления отчетности по тестированию.

## Необходимые разрешения/данные/доступы:

- Разрешение на проведение автоматизированного тестирования сайта Netology.ru
- Доступ к базе данных сайта Netology.ru
- Доступ к API сайта Netology.ru

##  Перечень и описание возможных рисков при автоматизации:

- При использовании реальных данных для логина - опасность утечки данных
- Возможные затруднения с поиском корректных CSS-селекторов элементов сайта
- Возможное изменение структуры сайта и его отдельных страниц при проведении тестирования
- Возможна обработка отделом продаж "ложных" заявок, отправленных в ходе тестирования

##  Перечень необходимых специалистов для автоматизации:

- Инженер по автоматизированному тестированию

##  Интервальная оценка с учётом рисков (в часах)

- Для написания тестов и тестирования, подготовки отчетности необходимо 35 часов рабочего времени.
