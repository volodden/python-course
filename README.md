# Python Cource(3.6)

<b>Об этом курсе</b>: Python – простой, гибкий и невероятно популярный язык, который используется практически во всех областях современной разработки. С его помощью можно создавать веб-приложения, писать игры, заниматься анализом данных, автоматизировать задачи системного администрирования и многое другое. “Программирование на Python” читают разработчики, применяющие Python в проектах, которыми ежедневно пользуются миллионы людей. Курс покрывает все необходимые для ежедневной работы программиста темы, а также рассказывает про многие особенности языка, которые часто опускают при его изучении.

<b>Курс рассчитан на </b> как на людей, которые уже имели опыт программирования на python, так и новичков в этом деле. Однако, в рамках курса предусмотрены только лекции и домашние задания. Основная среда работы: ipython notebook. В ходе курса не объясняется, как и что устанавливать. Предполагается, что слушатели разбираются с этим сами.

<b>Курс читается</b> на кафедре 1С, МФТИ.

## Программа курса

### Часть 1. Синтаксис.

<ul>
	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%201.%20intro-python/intro-python.pdf">Лекция 1. Python Введение. Основные структуры языка.</a><br><i>Описание</i>: на первой лекции разбираются основные конструкции языка, последовательности выполнения операций, циклы, переменные, объекты и их свойства (Identity, Type, Value). Garbage Collector. Изменяемые и неизменяемые объекты. Стандартные контейнеры. Функции. Библиотека collections.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%201/problems.ipynb">Задание</a>: знакомство со стандартными контейнерами. Пишем свой классификатор спама.</li>

	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%202.%20intro-python-2.%20strings%2C%20encodings%2C%20files/intro-python-2.%20strings%2C%20encodings%2C%20files.pdf">Лекция 2. Python. Введение. Строки, кодировки, файлы.</a><br><i>Описание</i>: на второй лекции разбиаются кодировки, строки в python (стандартные функции str). Как работает интерпретатор со строками. Частично затрагиваются менеджеры контекста. Разбираются потоки ввода, вывода и ошибок.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%202/problems%202.pdf">Задание</a>: Работа с разными кодировками. Создание классификатора языка текстов.<li>

	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%203.%20oop/oop.pdf">Лекция 3. Python. ООП.</a><br><i>Описание</i>: третья лекция включает разбор основных принципов ООП в питон. Классы и экземпляры. Наследование в питон и алгоритм MRO. Магические методы в питон. Объясняется как осуществляется доступ к атрибутам класса.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%203/problems%203.ipynb">Задание</a>: Знакомство с магическими функциями в питон. Реализация классов CounterGetter, Vector и Table.</li>

	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%204.%20scopes%2C%20closures%2C%20decorators/scopes%2C%20closures%2C%20decorators.pdf">Лекция 4. Области видимости. Замыкания. Декораторы.</a><br><i>Описание</i>: на лекции разбираются анонимные функции, области видимости переменных и контексты. Объяснение правила LEBG. Приводятся и объясняются сложные примеры замыканий с атрибутами и методами. Разбирается работа декораторов в питон. Стандартная библиотека functions. Классы декораторы и функции декораторы.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%204/problems%204.ipynb">Задание</a>: написать следующие декораторы - кэширования результатов функции (@cached), проверки типов аргументов функции (@checked) и декоратор логирования выполнения функции (@Logger).</li>

	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%205.%20exceptions%2C%20modules%2C%20regular%20expressions/exceptions%2C%20modules%2C%20regular%20expressions.pdf">Лекция 5. Исключения, модули, регулярные выражения.</a><br><i>Описание</i>: в рамках данное лекции рассматриваются типы ошибок в питон. Как наклабывать ограничения на работу программы и __DEBUG__ режим. Исключения и их обработка в питон. Создание собственных исключений. Стандартные библиотеки для работы с исключениями. Подробный разбор работы менеджеров контекста в питон. Создание и импорт модулей и пакетов. Дается базовое представление о регулярных выражениях и как с ними работать в питон (модуль re).<br><a href="https://github.com/king-menin/python-course/blob/master/problems%205/problems%205.ipynb">Задание</a>: реализуйте два менеджера контекстов: ContextTimer для отслеживания времени выполнения и Transaction для "безопасной" обработки данных. Напишите регулярное выражение для извлечения номеров.</li>

	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%206.%20iterators%20and%20generators/iterators%20and%20generators.pdf">Лекция 6. Итераторы и генераторы.</a><br><i>Описание</i>: на этой лекции мы узнаем, как работает цикл for, что такое итератор и протоколы итерирования. Как создавать собственные итераторы. Кратко будет рассмотрено такое свойство итеаторов как исчерпаемость. Объяснение устройства и работы генераторов. Встроенные генераторы map, filter, enumerate, zip. Стандартная библиотека для работы с генераторами itertools.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%206/problems%206.ipynb">Задание</a>: напишите генератор случайных диалогов (можно несвязных).</li>

	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%207.%20descriptors%20and%20metaclasses/oop%202.pdf">Лекция 7. Дескрипторы и мета классы.</a><br><i>Описание</i>: на этой лекции вы почувствуете все мощь питона (всю боль) и узнаете, как работают декораторы property, что такое дескриптор данных. Подробно будет рассмотрен алгоритм получения атрибутов в питон, как использовать собственные дескрипторы данных в своей программе. Во второй части лекци будут рассмотрены следующие вопросы: что такое type в питон, как создаются классы (что происходит, когда мы пишем <code>class SomeClass(object):</code>), что такое мета класс, применение мета классов. В том числе будет рассмотрен "хороший метод" (more power!) создания дескриптора с помощью мета класса.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%207/problems%207.ipynb">Задание</a>: напишите мета класс PropertyCreator для создания свойств класса. Напишите метакласс InstanceCountExeptioner, который будет следить за количеством экземпляров класса, использующих его. Напишите метакласс JSONClassCreator , который будет по json представлению строить новый класс и обратно. </li>
</ul>

### Часть 2. Приложения.

<ul>
	<li><a href="https://github.com/king-menin/python-course/blob/master/lecture%208.%20python%20and%20WEB/python%20and%20web.pdf">Лекция 8. Python и WEB.</a><br><i>Описание</i>: в первой части лекции вы узнаете об "устройстве интернета". Клиент-серверное взаимодейстие. Краткое описание протокола http. "Вводные" слова об HTML или как браузеры показывают веб-странички. Будут рассмотрены запросы методами get и post. Как создать свой клиент на питон, или как сделать запрос данных данных у википедии или гугла. Рассказано как майнить данные и парсить HTML в питон (lxml и BeautifulSoup). Как написать собственный сервер на питон (bottle). Во второй части лекции будет доклад о проекте 2kinopoisk.ru с примерами и алгоритмами реализации конкретных подзадач при создании сайта и проблем с этим связанных.<br><a href="https://github.com/king-menin/python-course/blob/master/problems%208/problems%208.ipynb">Задание</a>: предлагается создать сервер, который содержит в себе библиотеку книг. Также требуетсяпроверить гипотезу про статьи википедии.</li>
</ul>

## Authors

* **Антон Емельянов** - *МФТИ, кафедра АТП, аспирант 1 года* - *login-const@mail.ru*

## Литература и полезные ссылки

* [python docs](https://docs.python.org/3/)
* [.format](https://pyformat.info/)
* [импорт в питоне](http://asvetlov.blogspot.ru/2010/05/blog-post.html), [импорт в питоне ч.2](http://asvetlov.blogspot.ru/2010/05/blog-post.html)
* [регулярные выражения](https://developers.google.com/edu/python/regular-expressions), [модуль re](https://docs.python.org/3/library/re.html)
* [unit tests](http://asvetlov.blogspot.ru/2011/02/funny-unittests.html)
* [метаклассы](http://python-3-patterns-idioms-test.readthedocs.io/en/latest/Metaprogramming.html)
* [mro (advanced)](https://www.python.org/download/releases/2.3/mro/)
* [itertools](https://docs.python.org/2/library/itertools.html)

### книги:
* [(begginer level): dive into python](http://www.diveintopython3.net/)
* [(begginer level): a byte of python](https://python.swaroopch.com/)
