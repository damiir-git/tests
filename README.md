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
   - При открытии сайт показывается список, при клике роут меняется на /company/{ID}, при редактировании /company/edit/{ID}
   - Верстка не интересна, не тратье на это свое время, пусть все будет минималистично.
   
## В качестве инструментария
  - использовать [react](https://reactjs.org/), [mobx](https://github.com/mobxjs/mobx)
  - сборка на [webpack](https://webpack.js.org/)
  - сделать отдельную прослойку в приложении которая работает с бекендом, использовать [axios](https://github.com/axios/axios), чтобы запросы не падали сделать мокирование запросов либой [axios-mock-adapter](https://github.com/ctimmerm/axios-mock-adapter)
  - в качестве конструктора формы использовать библиотеку [mobx-react-form](https://github.com/foxhound87/mobx-react-form)
  - роутинг [react-router v4](https://github.com/ReactTraining/react-router)
  
## Результат
  - Форкнуть репозиторий, сделать подпапку с вашим логином и после выполнения задания сделать пулл-реквест в этот репозиторий
  - Приложить мини-инструкцию по запуску проекта в readme в вашей папке

