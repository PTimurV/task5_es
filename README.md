Фильмы захардкожены и лежат в сторе filmSlice, также каждому фильму добавлены по одному комментарию commentSlice (просто чтоб красивее было)

Страница популярных фильмов:
Выводятся все фильмы (потому что их всего 10) реализована сортировка по рейтингу по убыванию и возрастанию, также отключение сортировки, и реализована фильтрация по категориям фильмов.
Фильмы выводятся в виде карточек на которых есть краткая информация. А также иконки часов/звезды с возможностью добавления в Посмотреть позже/Избранное
(у фильма 1+1 для примера захардкожены эти значения в True).
По клику на названия фильма на любой из карточек вы попадете на детальную страницу фильма

Детальная страница фильма:
Отображается картинка фильма (хранятся в папке img) но из за этого динамического импорта в консоли разработчика выходят предупреждения но я не понял как это можно сделать лучше. Также выводится детальная информация о фильме, похожие фильмы (реализованы таким же компонентом как на главной странице) и форма добавления и просмотра комментариев, сделана стандартным html.
С этой страницы можно сразу перейти на поиск фильмов.

Поиск фильмов: строка поиска - поиск происходит по каждому клику, поиск по категориям - реализован обычными чекбоксами.
Фильмы выводятся в виде все тех же компонентов а значит сохраняется возможность перейти к фильму при клике на название, или добавить его в избранное или посмотреть позже.

Все компоненты лежат в своих папках, при надобности в соответствующих папках лежат css.

Для хранения state использовал Redux toolkit

Вроде все по основным заданиям реализовал, проблемы возникли только с этими динамическими импортами картинок.
