Это каталоги, которые мы активно используем в разработке:

- [frontend/server/controllers](https://github.com/kylelobo/The-Documentation-Compendium/tree/master/frontend/server/controllers): Контроллеры выполняют бизнес-логику и предоставляют серверный API.
- [frontend/server/libs](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs): Библиотеки и утилиты.
- [frontend/server/libs/dao](https://github.com/The-Documentation-Compendium/tree/master/frontend/server/libs/dao): Data Access Objects [DAO] и Value Objects [VO]. Классы, используемые для представления схем базы данных и облегчения их использования контроллерами.
- [frontend/templates](https://github.com/The-Documentation-Compendium/tree/master/frontend/templates): Шаблоны  Smarty для создания HTML-кода, который отображается пользователям.
- [frontend/www](https://github.com/The-Documentation-Compendium/tree/master/frontend/www): Полное содержание Интернет-страницы.

### Фронтенд / www

Содержание:

- js /
- css /

#### js

Как следует из названия, здесь находятся все шрифты javascript и фреймворки javascript. Если вы хотите внести изменения, уменьшите javascript, а затем загрузите.

#### css

Как и в случае с js, тут уменьшенные файлы css.

### Фронтенд / сервер

Содержание:

- dao /
- контроллеры /

Ни один из этих модулей не должен быть доступен внешнему миру. Единственное, что может их вызвать — это пользовательский интерфейс. Вот почему они находятся в папке www.

#### DAO / VO

Папка *dao* содержит классы для уровня доступа к данным. Он должен знать 2 вещи: *data access objects* и *value objects*. *Value objects*(VO) — это не что иное, как классы, которые сопоставляются непосредственно с каждой таблицей в базе данных. Поэтому там есть как класс под названием Users, так и таблица с тем же именем. Этот класс имеет свои сеттеры и геттеры для каждого поля в базе данных. *&nbsp;Data access objects*(dao) — являются статическими классами для каждой из таблиц, они служат для получения и создания постоянных объектов *vo*.

[Вот больше информации об этой модели](http://www.ibm.com/developerworks/java/library/j-dao/)

#### Контроллеры

Контроллеры — это то место, где принимаются решения. Контроллер использует dao и vo для принятия решений и никогда не вызывает базу данных напрямую. Таким образом, мы избегаем использования отдельных контроллеров для каждого модуля проекта.
