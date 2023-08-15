# XPath

## Кнопки

### Выбор полиса

1. Кнопка "Квартира"

//span[contains(text(), 'Квартира')]/ancestor::button

2. Кнопка "Дом"

//span[contains(text(), 'Дом')]/ancestor::button

3. Кнопка "Календарь"

//button[@aria-label="Open calendar"]

4. Кнопка "Да" в блоке "Сдаётся в аренду"

//*[@id="mat-button-toggle-22"]

5. Кнопка "Нет" в блоке "Сдаётся в аренду"

//*[@id="mat-button-toggle-23"]

6. Кнопка "Да" в блоке "Расположена на первом или последнем этаже"

//*[@id="mat-button-toggle-25"]

7. Кнопка "Нет" в блоке "Расположена на первом или последнем этаже"

//*[@id="mat-button-toggle-26"]

8. Кнопка "Да" в блоке "Установлена охранная сигнализация"

//*[@id="mat-button-toggle-28"]

9. Кнопка "Нет" в блоке "Установлена охранная сигнализация"

//*[@id="mat-button-toggle-29"]

10. Кнопка "Применить"

//span[contains(text(), 'Применить')]/ancestor::button

11. Кнопка "Оформить"

//span[contains(text(), 'Оформить')]/ancestor::button

___
### Оформление
1. Кнопка "Заполнить по СберID"

//span[contains(text(), 'Заполнить по Сбер ID')]/ancestor::button

2. Кнопка "Мужской"

//span[contains(text(), 'Мужской')]/ancestor::button

3. Кнопка "Женский"

//span[contains(text(), 'Женский')]/ancestor::button

4. Кнопка "Календарь" при выборе даты рождения

//div[contains(@class, 'birthday')]//button

5. Кнопка "Календарь" при выборе даты выдачи паспорта

//div[contains(@class, 'date')]//button

6. Кнопка "Вернуться"

//span[contains(text(), 'Вернуться')]/ancestor::button

7. Кнопка "Оформить"

//span[contains(text(), 'Оформить')]/ancestor::button

## Поля ввода текста

### Выбор полиса

1. Поле ввода "Регион проживания"

//*[@id="mat-input-0"]

2. Поле ввода "Дата начала"

//*[@id="mat-input-1"]

3. Поле ввода "Сумма"

//*[@id="mat-input-3"]

4. Поле ввода "Промокод"

//*[@id="mat-input-2"]

___

### Оформление

1. Поле ввода "Фамилия"

//input[contains(@data-placeholder, 'Фамилия')]

2. Поле ввода "Имя"

//input[contains(@data-placeholder, 'Имя')]

3. Поле ввода "Отчество"

//input[contains(@data-placeholder, 'Отчество')]

4. Поле ввода "Дата рождения"

//input[@formcontrolname="birthDate"]

5. Поле ввода "Серия"

//input[contains(@data-placeholder, 'Серия')]

6. Поле ввода "Номер"

//input[contains(@data-placeholder, 'Номер')]

7. Поле ввода "Дата выдачи"

//input[@formcontrolname="docDate"]

8. Поле ввода "Кем выдан"

//textarea[contains(@data-placeholder, 'Кем выдан')]

9. Поле ввода "Код подразделения"

//input[contains(@data-placeholder, 'Код подразделения')]

10. Поле ввода "Город или населенный пункт"

//input[contains(@data-placeholder, 'Город или населенный пункт')]

11. Поле ввода "Улица"

//input[contains(@data-placeholder, 'Улица')]

12. Поле ввода "Дом, литера, корпус, строение"

//input[contains(@data-placeholder, 'Дом, литера, корпус, строение')]

13. Поле ввода "Квартира"

//input[contains(@data-placeholder, 'Квартира')]

14. Поле ввода "Телефон"

//*[contains(@data-placeholder, 'Телефон')]

15. Поле ввода "Электронная почта"

//input[contains(@data-placeholder, 'Электронная почта')]

16. Поле ввода "Повтор электронной почты"

//input[contains(@data-placeholder, 'Повтор электронной почты')]

## Чекбоксы

1. Чекбокс "Отчество отсутствует"

//span[contains(text(), 'Отчество отсутствует')]/ancestor::mat-checkbox//input

2. Чекбокс "Улица отсутствует"

//span[contains(text(), 'Улица отсутствует')]/ancestor::mat-checkbox//input

## Датапикеры

1. Датапикер "Срок действия страхования"

//*[@id="mat-datepicker-3"]

2. Датапикер "Дата рождения" 

//*[@id="mat-datepicker-4"]

3. Датапикер "Дата выдачи"

//*[@id="mat-datepicker-5"]

## Остальное 

1. Логотип "СБЕР СТРАХОВАНИЕ"

//*[contains(@class, 'sber-logo')]

2. Слайдер в блоке выбора суммы

//*[@role="slider"]

3. Хедер "Что будет застраховано?"

//h4[contains(text(),'Что будет застраховано?')]

4. Текстовый блок "Мебель, техника и ваши вещи"

//div[contains(text(),'Мебель, техника и ваши вещи')]

5. Текстовый блок "Падение летательных аппаратов и их частей"

//div[contains(text(),'Падение летательных аппаратов и их частей')]

6. Колонки "Страховая защита включенная в программу"

- Колонка слева 

//div[text()='Залив']/ancestor::div[@class='sbi-form__col-2']

- Колонка справа

//div[text()='Пожар']/ancestor::div[@class='sbi-form__col-2']