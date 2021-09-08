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





