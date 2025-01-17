# Тестовое задание

## Задача
Необходимо сделать проект в котором выводится список компаний, при клике на компанию, выводится карточка компании, в карточке компании есть кнопка редактировать которая открывает форму редактирования полей и кнопкой сохранить, при клике сохранить нужно просто выводить снизу карточку компании с новыми данными (без бекенда). компания содержит в себе след. поля
- ID
- Имя
- ОГРН
- Тип компании (ИП, ООО)
- Дату регистрации
- Активен или нет

## Что нужно сделать:
   - Компонент список компаний (внутри могут и другие компоненты, тут не ограничений)
   - Компонент карточки компании 
   - Компонент для редактирования компании
       - Имя, ОГРН - текстовое поле
       - Тип компании - выпадающий список из ООО, ИП
       - Дата регистрации - использовать какой нибудь datepicker
       - Активен или нет (чекбокс)
   - При открытии сайта показывается список, при клике роут меняется на /company/{ID}, при редактировании /company/edit/{ID}
   - Верстка не интересна, не тратье на это свое время, пусть все будет минималистично.
   
## В качестве инструментария (стек React-Redux)
  - использовать [react](https://reactjs.org/), [redux](https://redux.js.org/)
  - отдавать предпочтение функциональным компонентам + желательно использовать [typescript]
  - сборка на [webpack](https://webpack.js.org/)
  - сделать доменную прослойку (предпочтительно redux-saga), в качестве вызова api использовать [axios](https://github.com/axios/axios), чтобы запросы не падали сделать мокирование запросов
  - для обработки данных формы использовать [react-hook-form] (https://react-hook-form.com/)
  - роутинг [react-router v4](https://github.com/ReactTraining/react-router)
  
## Результат
  - Отправить в телеграмм ссылку на проект в github с пометкой "тестовое задание"
  - Приложить мини-инструкцию по запуску проекта в readme
