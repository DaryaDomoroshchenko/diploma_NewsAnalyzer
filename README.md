# [NewsAnalyzer](https://daryadomoroshchenko.github.io/news_analyzer_diploma/)
## Яндекс.Практикум. Дипломный проект
### Используемый стек технологий: JS, CSS, HTML, GIT, Webpack
Данный проект представляет собой сервис для анализа происходящих в мире событий. Его задача - установить, насколько популярны новости на определенную тему.


_Как это работает?_


Пользователь вводит в строку поиска на главной странице ключевое слово, по которому хочет найти российские новости. По нажатию кнопки "Искать" осуществляется запрос к API, в локальное хранилище записываются последние 100 новостей, а на странице отображаются карточки с первыми тремя новостями. При нажатии кнопки "Показать еще" отрисовываются следующие три новости и тд.


На странице аналитики отображается диаграмма популярности новостей за последнюю неделю и статистика упоминаний ключевого слова в заголовках статей.


Страница "О проекте" содержит информацию о технологиях, примененных при создании проекта, а также слайдер с последними коммитами на GitHub.

### Для запуска проекта необходимо:
1. установить [Node.js](https://nodejs.org/en/)
2. `git clone git@github.com:DaryaDomoroshchenko/news_analyzer_diploma.git` - клонировать репозиторий
3. `npm i` - установить все необходимые зависимости проекта
4. `npm run build` - произвести сборку проекта
5. `npm run dev` - запустить проект на локальном сервере по адресу localhost:8080

Актуальная версия v0.0.9