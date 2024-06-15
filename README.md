# Тест план
## Тест кейс №1 Отправка формы с валидными данными
### предусловия: 
* открыть сайт https://netology.ru/
* перейти во вкладку "програмирование"
* выбрать курс инженер по тестированию
### шаги:
1. в поле ввода имени ввести валидное имя например "Дмитрий"
2. в поле ввода номера телефона ввести валидный телефон например "+79290234567"
3. кликнуть кнопку "Записаться"
### ожидаемый результат:
1. в поле ввода имени отображается введённое имя
2. в поле ввода номера телефона отображается введённый номер
3. появляется сообщение об успешной отправке заявки
## Тест кейс №2 Отправка пустой формы
### предусловия:
* открыть сайт https://netology.ru/
* перейти во вкладку "програмирование"
* выбрать курс инженер по тестированию
* поля ввода не заполнены
### шаги:
1. кликнуть кнопку записаться 
### ожидаемый результат:
1. поля ввода окрашиваются в красный цвет, появляются подсказки "обязвтельное поле", кнопка записаться не кликабельна
## Тест кейс №3 поле ввода имени (состовные имена)
### предусловия:
* открыть сайт https://netology.ru/
* перейти во вкладку "програмирование"
* выбрать курс инженер по тестироанию
* поле ввода телефон заполнено валидным номером телефона например "+79290234567"
* ### шаги:
1. ввести имя через дефис например "Анна-Мария", кликнуть отправить
2. ввести имя через пробел например "Анна Мария", кликнуть отправить
### ожидаемый результат:
1. поле ввода принимает введённое имя, появляется сообщение об успешной отправке заявки 
2. поле ввода принимает введённое имя, появляется сообщение об успешной отправке заявки
## Тест кейс №4 поле ввода имени (невалидные значения)
### предусловия:
* открыть сайт https://netology.ru/
* перейти во вкладку "програмирование"
* выбрать курс инженер по тестироанию
* поле ввода телефон заполнено валидным номером телефона например "+79290234567"
### шаги:
1. в поле имя ввести цифры, кликнуть кнопку записаться
2. в поле имя ввести спец. символы например "%;?", кликнуть кнопку записаться
3. в поле имя ввести одну букву, кликнуть кнопку записаться
4. в поле имя ввести имя с маленькой буквы например "дмитрий", кликнуть кнопку записаться
5. в поле имя ввести несуществующее имя, кликнуть кнопку записаться
### ожидаемый результат:
1. поле ввода имя окрашивается в красный цвет, появляется подсказка "Должно состоять из букв", кнопка записаться не кликабельна
2. поле ввода имя окрашивается в красный цвет, появляется подсказка "Должно состоять из букв", кнопка записаться не кликабельна
3. поле ввода имя окрашивается в красный цвет, появляется подсказка "Должно быть не короче 2 символов", кнопка записаться не кликабельна
4. введённое имя подчеркивается красной волнистой линией, кнопка записаться не кликабельна
5. введённое имя подчеркивается красной волнистой линией, кнопка записаться не кликабельна
## Тест кейс №5 поле ввода номера телефона (дефис, пробел)
### предусловия:
* открыть сайт https://netology.ru/
* перейти во вкладку "програмирование"
* выбрать курс инженер по тестироанию
* поле ввода имени заполнено валидным именем например "Дмитрий"
### шаги: 
1. в поле ввода номера телефона ввести номер через дефис например "+79290-23-45-67", кликнуть отправить 
2. в поле ввода номера телефона ввести номер через пробел например "+7 9290234567", кликнуть отправить
### ожидаемый результат:
1. поле ввода номера телефона принимает введённый номер, заявка успешно отправляется.
2. поле ввода номера телефона принимает введённый номер, заявка успешно отправляется.
## Тест кейс №6 поле ввода номера телефона (невалидные значения)
### предусловия:
* открыть сайт https://netology.ru/
* перейти во вкладку "програмирование"
* выбрать курс инженер по тестироанию
* поле ввода имени заполнено валидным именем например "Дмитрий"
### шаги:
1. в поле ввода номера телефона ввести буквы, кликнуть кнопку записаться
2. в поле ввода номера телефона ввести спец. символы, кликнуть кнопку записаться
3. в поле ввода номера телефона ввести номер из 10 цифр, кликнуть кнопку записаться 
4. в поле ввода номера телефона ввести номер из 12 цифр, кликнуть кнопку записаться 
5. в поле ввода номера телефона ввести полный номер без префикса +7 например "89290234567", кликнуть кнопку записаться

### ожидаемый результат:
1. поле ввода номера телефона окрашивается в красный цвет, появляется подсказка "Неверный формат", кнопка записаться не кликабельна
2. поле ввода номера телефона окрашивается в красный цвет, появляется подсказка "Неверный формат", кнопка записаться не кликабельна
3. поле ввода номера телефона окрашивается в красный цвет, появляется подсказка "Неверный формат", кнопка записаться не кликабельна
4. поле ввода номера телефона окрашивается в красный цвет, появляется подсказка "Неверный формат", кнопка записаться не кликабельна
5. поле ввода номера телефона окрашивается в красный цвет, появляется подсказка "Неверный формат", кнопка записаться не кликабельна
# Перечень используемых инструментов
* IntelliJ IDEA Community Edition 2023.3.4 (среда разработки)
* java (язык программирования)
* gradle (для управления проектом)
* selenide (для автоматизации тестирования)
* faker (для гененрации данных)
* lombok (упростить написание кода)
* docker (для контейнерезации если понадобится поработать с б.д)
* gitHub (для работы с проектом в команде)
* postman (для работы с сервером)
* DBeaver (для работы с б.д)
# Перечень необходимых разрешений, данных и доступов.
* Разрешение на автоматизацию
* требования 
* описание API
# Перечень и описание возможных рисков при автоматизации.
* изменяться требования 
* измениться продукт (добавиться или измениться что то в сайте)
* недоступны инструменты для тестирования
* продукт плохо подготовлен к тестирования (например нет тестовых меток)
# Перечень необходимых специалистов для автоматизации.
* автотестировщики 
# Интервальная оценка с учётом рисков в часах. 
* 16 - 24 часов
