
# Тестовое задание на позицию верстальщика

В этом тестовом задании Вам необходимо сделать на выбор одно задание из двух.

Выложите готовую вёрстку на публично доступный адрес ([github pages](https://pages.github.com/) или [vercel](https://vercel.com/)).
Результаты в виде ссылки на репозиторий и публично доступный адрес присылайте на почту i.sidash@tradernet.com c темой письма **"Тестовое задание на позицию верстальщика"**. 



## I. Верстка лендинга
  Ссылка на [макет](https://www.figma.com/file/9z9FOPCaPVozVPDUI2o6nQ/FF-Landing?node-id=2%3A2614)
  
  ### Технические требования:
  1. Адаптивная вёрстка. Поддерживаются как большие 4К дисплеи, так и телефоны. Главный критерий - работоспособность.
  2. Используйте пре/постпроцессоры для написания CSS.
  3. Не используйте CSS-фреймворки.
  4. Инспользуйте [normalize.css](https://necolas.github.io/normalize.css/) для нормализации стилей.


## II. Верстка формы регистрации

  Ссылка на [макет](https://www.figma.com/file/XLogxL9eYkORuxN4FFRSgY/FF-Registration?node-id=0%3A1) 
  
  ### Технические требования:
  1. Адаптивная вёрстка. Поддерживаются как большие 4К дисплеи, так и телефоны. Главный критерий - работоспособность.
  2. Используйте пре/постпроцессоры для написания CSS.
  3. Не используйте CSS-фреймворки.
  4. Используйте [normalize.css](https://necolas.github.io/normalize.css/) для нормализации стилей.
  5. Имплементируйте JS логику валидации формы.
    
  ### Логика формы регистрации:
  
  1. Валидация поля **ИНН** (только цифры, минимальная и максимальная длина - 12 символов).
  2. **Резиденство/Размер благосостояния** (не должно быть пустым).
  4. **Я не помню свой номер налогоплательщика** (если выбран, то блочим и не валидируем поле с **ИНН**).
  5. **Да/Нет** (должен быть выбран один из вариантов).
  6. Если пользователь выбирает **резидентсво США**, то рисуем ошибку и "дизейблим" поле **ИНН**.
