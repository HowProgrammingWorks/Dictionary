# Словарь-индекс понятий со ссылками

Оглавление:
- [Базовые понятия](https://github.com/HowProgrammingWorks/Dictionary#Базовые-понятия)
- [Основные понятия](https://github.com/HowProgrammingWorks/Dictionary#Основные-понятия)
- [Вспомогательные материалы](https://github.com/HowProgrammingWorks/Dictionary#Вспомогательные-материалы)
- [Структуры данных](https://github.com/HowProgrammingWorks/Dictionary#Структуры-данных)
- [Расширенные понятия](https://github.com/HowProgrammingWorks/Dictionary#Расширенные-понятия)
- [Примеры кода и комплексного использования технологий](https://github.com/HowProgrammingWorks/Dictionary#Примеры-кода-и-комплексного-использования-технологий)
- [Парадигмы программирования](https://github.com/HowProgrammingWorks/Dictionary#Парадигмы-программирования)

## Базовые понятия

- [Абстракция / Abstraction](https://github.com/HowProgrammingWorks/Reusable) и повторное использование
  - обобщенное решение задачи, в отличие от конкретного решения, подходящее для
  широкого круга задач
  - модель реального объекта (множества объектов), являющаяся приближением к
  реальности, обобщением
  - множество свойств объекта, относящиеся к определенному его аспекту
  - [Слои абстракций / Abstraction Layer](https://github.com/HowProgrammingWorks/AbstractionLayers)
- Парадигма программирования / Programming Paradigm
  - подход к решению задач на ЭВМ, характеризующийся стилем, набором приемов,
  допущений и ограничений
  - совокупность идей и понятий, применяемых для написания программного кода
- [Переменная / Variable](https://github.com/HowProgrammingWorks/DataTypes)
  - именованная область памяти, имеющая тип данных, адрес и значение
  - имя (идентификатор), с которым связано значение и тип данных
  - переменная предоставляет возможность менять значение (а для некоторых
  языков и тип)
  - `let cityName = 'Beijing';`
- [Константа / Constant](https://github.com/HowProgrammingWorks/DataTypes)
  - имя (идентификатор), с которым связано неизменяемое значение и тип
  - `const WATCH_TIMEOUT = 5000;`
- [Типы данных / Data Types](https://github.com/HowProgrammingWorks/DataTypes)
  - тип - это множество значений и операции, определенные на этом множестве
  - `[5, 'Kiev', true, { city: 'Beijing' }, a => ++a ].map(x => typeof x);`
- Примитивные или [скалярные типы / Scalar Types](https://github.com/HowProgrammingWorks/DataTypes)
  - примитивные типы имеют одно значение, а не несколько структурированных
  значений и передаются по значению (копирование значения), а не по ссылке
  - например: `Number, String, Boolean`
- [Структурные типы / Composed types](https://github.com/HowProgrammingWorks/DataTypes)
  - композитные типы или структуры состоят из нескольких скалярных значений,
  объедиенных в одно таким образом, чтоб над этим объединенным значением можно
  было выполнять набор операций
  - например: объект, массив, множество, кортеж
- [Ссылочные типы / Reference](https://github.com/HowProgrammingWorks/DataTypes)
  - типы данных, передаваемые по ссылке, а не по значению
  - например: `Object, Function, Array`
  - [примеры кода по массивам и объектам](https://github.com/HowProgrammingWorks/DataStructures)
- [Перечислимые типы / Enumerated types](https://github.com/HowProgrammingWorks/Enum)
- Флаг / Flag
  - Логическое значение, определяющее состояние чего-либо, например, признак
  закрытия соединения, признак завершения поиска по структуре данных и т.д.
  - `let flagName = false;`
- Массив / Array
  - коллекция эллементов, доступ к которым осуществляется по индексам
  - `const cities = ['Tehran', 'Yalta', 'Potsdam'];`
- [Цикл / Loop](https://github.com/HowProgrammingWorks/Iteration)
  - многократное исполнение блока операторов
- [Условие / Conditional statements](https://github.com/HowProgrammingWorks/Conditional)
  - синтаксическая конструкция, позволяющая выполнить разные действия или
  возвращающая разные значения (тернарный оператор) в зависимости от логического
  выражения (возвращающего true или false)
- [Строка / String](https://github.com/HowProgrammingWorks/String)
  - последовательность символов (в большинстве языков к каждому символу можно
  обратиться через синтаксис доступа к элементам массива, например, квадратные
  скобки)

Видео:
- [Карта специальности инженер-программист (осень 2018)](https://www.youtube.com/watch?v=SE5aXH-yf0I&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Базовый синтаксис Javascript (осень 2018)](https://www.youtube.com/watch?v=xJn3k1f4BiM&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Базовый синтаксис Javascript, продолжение (осень 2018)](https://www.youtube.com/watch?v=qa-XleqA0JU&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [JavaScript как ассемблер нашего времени (лето 2017)](https://www.youtube.com/watch?v=ZnZg_lf3b94&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Работа со строками, шаблонами и юникодом (осень 2018)](https://www.youtube.com/watch?v=GcopcHQkA8M&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)

## Основные понятия

- [Объект / Object](https://github.com/HowProgrammingWorks/DataTypes)
  - структура данных, содержащая состояние и методы, связанные с этим состоянием
  - объект может быть создан как литерал `{}` или экземпляр класса (прототипа)
  `new ClassName()` или как экземпляр прототипа `new PrototypeConstructor()` или
  возвращен из фабрики
  - `const person = { name: 'Marcus', city: 'Roma', born: 121 };`
  - `const person = new Person('Marcus', 'Roma', 121);`
- Инстанциирование / Instantiation
  - создание объекта (экземпляра) или выделение памяти для структуры данных
  - `const rect = new Rectangle(-50, -50, 100, 150);`
  - `const rect = { a: { x: -50, y: -50 }, b: { x: 100, y: 150 } };`
  - `const cities = new Array(1000);`
  - `const cities = ['Tehran', 'Kiev', 'Yalta', 'Beijing', 'Potsdam', 'London'];`
- Класс / Class
  - программная абстракция, обобщающая свойства и методы, состояние и поведение
  своих экземпляров
  - `class Point { constructor(x, y) { this.x = x; this.y = y; } }`
- [Прототип / Prototype](https://github.com/HowProgrammingWorks/Prototype)
  - специальный объект, на который ссылаются его экземпляры, и свойства
  которого становятся видны у наследников, если эти свойства не переопределены
  у наследников (формируется цепочка прототипов, по которой последовательно
  ищутся свойства, пока не будут найдены или пока не будет достигнут конец)
  - шаблон, который клонируется во время инстанциирования
- [Функция](https://github.com/HowProgrammingWorks/Function)
  - определения
    - функциональное программирование: отображение или преобразование элементов
    одного множества в элементы другого множества
    - императивное программирование: ссылка на блок операторов (не обязательно
    именованный), реализующий последовательность действий
    - обобщенное определение: выражение или блок операторов, имеющий имя или
    анонимный, преобразующий аргументы в результаты, или изменяющий состояние
    контекстов или объектов
  - [Контекст](https://github.com/HowProgrammingWorks/Function)
  - [Область видимости / Scope](https://github.com/HowProgrammingWorks/Function)
  - Объявление функции / Function definition
    - `function max(a, b) { return a + b; }`
  - Функциональное выражение / Function expression
    - функциональное выражение с именованной функцией / Named function expression
      - `const max = function max(a, b) { return a + b; };`
    - анонимное функциональное выражение / Anonymous function expression
      - `const max = function(a, b) { return a + b; };`
    - лямбда-функция / Lambda function
      - `const max = (a, b) => { return a + b; };`
    - лябмда-выражение, Функция-стрелка / Lambda expression, Arrow function
      - `const max = (a, b) => (a + b);`
  - [Чистая функция / Pure Function](https://github.com/HowProgrammingWorks/Function)
    - функция, вычисляющая результат только на основе аргументов, не имеющая
    состояния и не обращающаяся к операциям ввода-вывода
    - функция, результат которой всегда детерминированный, т.е. для любого
    аргумента всегда будет один и тот же результат
    - функция, не имеющая побочных эффектов (см. побочный эффект)
  - [Замыкание / Closure](https://github.com/HowProgrammingWorks/Closure)
    - если вернуть функцию `g` из функции `f`, то `g` будет видеть контекст
    функции `f`, так же, как и свои аргументы
    - если `f` возвращает `g`, то говорят, что экземпляр `g` замкнул контекст `f`
    - способ, позволяющий связать функцию с контекстом (с данными или
    переменными контекста)
    - замыкание является аналогом свойств в ООП, тоже связывающие свойства с
    методами через объект, по сути объект в ООП сам является контекстом
    связывания
    - при помощи замыкания можно реализовать функциональное наследование
    - `const add = a => b => a + b;`
    - `const hash = (data = {}) => (key, value) => (data[key] = value, data);`
  - [Суперпозиция / Superposition](https://github.com/HowProgrammingWorks/Composition)
    - объединение вызова функций в выражения таким образом, что результат одних
    функций становится аргументами других функций
    - `const expr2 = add(pow(mul(5, 8), 2), div(inc(sqrt(20)), log(2, 7)));`
  - [Композиция / Composition](https://github.com/HowProgrammingWorks/Composition)
    - `const compose = (f1, f2) => x => f2(f1(x));`
    - `const compose = (...funcs) => (...args) => (funcs.reduce((args, fn) => [fn(...args)], args));`
  - [Частичное применение / Partial application](https://github.com/HowProgrammingWorks/PartialApplication)
    - `const partial = (fn, x) => (...args) => fn(x, ...args);`
  - [Каррирование / Currying](https://github.com/HowProgrammingWorks/PartialApplication)
    - `const result = curry((a, b, c) => (a + b + c))(1, 2)(3);`
  - [Побочные эффекты / Side effects](https://github.com/HowProgrammingWorks/Function)
  - [Функция высшего порядка / Higher-order Function](https://github.com/HowProgrammingWorks/HigherOrderFunction)
    - если функция только в аргументах, то это колбек
    - если функция только в результате, то это фабрика функций на замыканиях
    - если возвращаемая функция имеет тот же смысл, что и получаемая в
    аргументах (+ дополнительное поведение), то это обертка
    - очень редко бывает, что возвращаемая функция не связана с функцией из
    аргументов (но пока ни кто не нашел вразумительного примера, где это
    реально нужно)
    - если на выходе класс или функция-конструктор, то это фабрики классов и
    прототипов соответсвенно
  - Функциональное наследование / Functional Inheritance
    - при помощи замыканий, ч.п., каррирования, лямбд
- [Метод / Method](https://github.com/HowProgrammingWorks/Function)
  - функция, связанная с объектным контекстом или программным интерфейсом
  - `{ a: 10, b: 10, sum() { return this.a + this.b; } }`
- [Обертка / Wrapper](https://github.com/HowProgrammingWorks/Wrapper)
  - функция, которая оборачивает другую функцию (иногда объект, интерфейс или
  функциональный объект), добавляя ему дополнительное поведение
  - можно обернуть целый API интерфейс и даже асинхронную функцию вместе с
  колбеками (если известен контракт)
- Интерфейс / Interface
  - набор методов (функций) объединенных или общим объектным контекстом или
  применением к структурам данных одной предметной области т.е. смыслом (API)
  - способ определения (спецификации) контракта, по которому связаны
  программные компоненты
  - Набор методов с их именами, аргументами и типами аргументов
- Программный интерфейс / Application Interface, API
  - интерфейс программных компонентов: модулей, слоев абстракции, приложений
- [Синглтон / Singleton](https://github.com/HowProgrammingWorks/Singleton)
  - шаблон проектирования, предполагающий, что в одном пространстве имен
  (процессе, приложении, базе данных) будет только один экземпляр класса
  (или просто один подобный объект) к которому можно обратиться по определенному
  (известному) имени
- [Функция обратного вызова, колбек / Callback](https://github.com/HowProgrammingWorks/Callbacks)
  - функция передаваемая в качестве аргумента в другую функцию (или метод)
  для того, чтобы быть вызванной для возврата значения, ошибки или уведомления
  - функции обратного вызова имеют подтипы:
    - один раз вызываемые (чаще всего)
    - [Событие / Event](https://github.com/HowProgrammingWorks/Callbacks)
    - [Лисенер / Listener](https://github.com/HowProgrammingWorks/Callbacks)
- [Итерирование / Iteration](https://github.com/HowProgrammingWorks/Iteration)
  - многократное повторение одного блока кода или одной функции над различными
  данными: элементами массивов, множеств, списков, коллекций и различными
  значениями переменной цикла
- [Итератор / Iterator](https://github.com/HowProgrammingWorks/Iteration)
  - интерфейс доступа к элементам коллекции: массива, множества, списка
- [Файл / File](https://github.com/HowProgrammingWorks/Files)
- [Поток, Файловый поток / Stream, File Stream](https://github.com/HowProgrammingWorks/Streams)
- [Сокет / Socket](https://github.com/HowProgrammingWorks/Socket)
  - программный интерфейс (или абстракция) для обмена данными между процессами
- [Дескриптор / Handle](https://github.com/HowProgrammingWorks/Files)
  - уникальный идентификатор программного объекта (чаще всего объекта операционной
  системы): файла, сокета, окна, таймера, соединения и т.д.
- Состояние / State
  - совокупность данных программного компонента (переменных и структур данных),
  определяющие его поведение и реакцию на операции с ним
- Кэш, Кэширование / Cache
  - место временного хранения данных (буфер, коллекция, область памяти) для
  быстрого доступа и оптимизации
  - возможно кеширование операций чтения, вычислений, операций записи (когда
  запись не может быть поизведена достаточно быстро) или упрезжающее чтение в
  буфер (когда можно определить, какие данные будут запрошены с наибольшей
  вероятностью)
- Хэширование / Hashing
  - преобразование данных произвольной длины (буфера, массива, объекта или
  структуры данных) в последовательность битов определенной длины (хеш) при
  помощи хеш-функции (при изменении 1 бита в данных хеш меняется существенно)
- [Функциональный объект](https://github.com/HowProgrammingWorks/Functor)
  - [Функтор / Functor](https://github.com/HowProgrammingWorks/Functor)
    - функтор - это рекурсивное замыкание / recursive closure
    - объект функционального типа, хранящий в себе защищенное значение и
    позволяющий отобразить это значение в другой функтор через функцию
  - [Аппликативный функтор](https://github.com/HowProgrammingWorks/Functor)
  - Монада / Monad
- [Мемоизация / Memoization](https://github.com/HowProgrammingWorks/Memoization)
  - обертка функции, сохраняющая результаты выполнения функции для
  предотвращения повторных вычислений
- [Примесь / Mixin](https://github.com/HowProgrammingWorks/Mixin)
  - добавление свойств, методов или поведения к объекту после его
  инстанциирования (создания)
  - `Object.assign(target, { field1, field2 }, { field3 });`
- Декоратор / Decorator
  - шаблон оборачивания объектов или функций для добавления новой
  функциональности при помощи специального синтаксиса
- [Наследование / Inheritance](https://github.com/HowProgrammingWorks/Inheritance)
- [Множественное наследование / Multiple Inheritance](https://github.com/HowProgrammingWorks/Inheritance)
- [Непрямое наследование / Indirect Inheritance](https://github.com/HowProgrammingWorks/Inheritance)
- [Генератор / Generator](https://github.com/HowProgrammingWorks/Generator)
- [Синхронные операции](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
- [Асинхронные операции](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
- [Ввод/вывод / I/O, Input-output](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
  - операции, выходящие за рамки CPU и RAM (арифметико-логического устройства
  и памяти), т.е. операции с устройствами ввода вывода: сеть, диск, порты,
  консоль (клавиатура и экран), друге переферийные устройства (взаимодействие
  с которыми на порядки медленнее, чем внутренние операции а АЛУ и памяти)
- [EventEmitter](https://github.com/HowProgrammingWorks/EventEmitter)
  - универсальная абстракция для работы с событиями чере подписку (subscription:
  addListener, on, once) и отправку (emit)
- [Чеининг / Chaining](https://github.com/HowProgrammingWorks/Chaining)
  - цепочный синтаксис вызова функций `total(april)(may)(july)` или методов
  `array.filter(f1).reduce(f2)`
- [Сериализация / Serialization](https://github.com/HowProgrammingWorks/Serialization)
  - преобразование структуры данных (развернутой в памяти) в битовую
  последовательность, обычно в последовательность байтов (бинарная сериализация)
  или в строку (текстовая сериализация)
- [Десериализация / Deserialization](https://github.com/HowProgrammingWorks/Serialization)
  - операция, обратная сериализации, т.е. восстановление структуры данных
  из последовательности битов (чаще байтов или строки)
- Парсинг / Parsing
  - синтаксический анализ текста, результатом чего может являться:
    - для формальной граматики - AST-дерево
    - для слабоструктурированного документа - структура данных, имеющая
    четкую структуру, в которую частично перенесены данные из слабой структуры
    - для других естественных или искуственных языков - информационные модели,
    им соответствующие
- [Регулярные выражения / Regular Expressions](https://github.com/HowProgrammingWorks/RegExp)
  - синтаксическая конструкция, паттерн, формальный язык, определяющий
  порядок парсинга другой синтаксической конструкции
- [Модуль, модульность](https://github.com/HowProgrammingWorks/Modularity)
  - целостный, функционально полный, независимый компонент программной системы
  имеющий имя, интерфейс, реализацию
  - модульность повышает переиспользование кода, упрощает интеграцию компонентов,
  улучшает компоновку и тестирование программ по частям
  - ограничения: модули не должны использовать глобальные переменные или
  модифицировать базовые классы/прототипы/функции языка программирования,
  платформы и/или фреймворка; модули должны быть слабо связаны, взаимодействовать
  друг с другом только через внешнее API (предпочтительно) или шину событий
  (если система построена на событийной модели, подписке или модели акторов)
- [Зависимость / Dependency](https://github.com/HowProgrammingWorks/Project)
  - связанность программных компонентов, при которой один компонент (зависимый)
  "знает" другой; это значит, что в нем помещен вызов метода (реализация которого
  содержится в другом) или он слушает событие, которое генерирует другой или
  он "знает" структуры данных, которые могут быть переданы из другого компонента
- Декомпозиция / Decomposition
  - разделение программного компонента на части по принципу функциональности,
  при этом, каждая часть будет решать подзадачу и появится часть кода, которая
  определяет порядок связи всех частей (композицию)
- [Ленивость / Lazy](https://github.com/HowProgrammingWorks/Lazy)
- [Обработка ошибок / Error handling](https://github.com/HowProgrammingWorks/Errors)
- [Фабрика / Factory](https://github.com/HowProgrammingWorks/Factory)
  - функция или метод для инстациирования объектов, функций, структур данных и
  любых других программных абстракций, например, экземпляров класса в обход
  конструктора или функциональных объектов
- Объектный Пул / [Object Pool](https://github.com/HowProgrammingWorks/Pool)
  - Множество заранее инстанциированных объектов (или массивов, сокетов, буферов,
  структур данных и других программных абстракций) из которого мы можем их брать
  инициализированные экземпляры (вместо инстанциирования новых) и отдавать их
  после использования
- [Таймеры / Timers](https://github.com/HowProgrammingWorks/Timers)

Видео:
- [Массивы, объекты, классы, прототипы (осень 2018)](https://www.youtube.com/watch?v=VBMGnAPfmsY&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Функции, лямбды, контексты, замыкания (осень 2018)](https://www.youtube.com/watch?v=pn5myCmpV2U&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Композиция, каррирование, частичное применение (осень 2018)](https://www.youtube.com/watch?v=ND8KQ5xjk7o&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Функции высшего порядка, колбеки, события на JavaScript (осень 2018)](https://www.youtube.com/watch?v=1vqATwbGHnc&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Замыкания, примеси, обертки, функторы, события (лето 2017)](https://www.youtube.com/watch?v=AiHiJL-fvNI&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [OdessaJS 2018, часть 1](https://www.youtube.com/watch?v=wkdqpR2BJu4&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [OdessaJS 2018, часть 2](https://www.youtube.com/watch?v=8jAuwfNw9aE&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Асинхронное программирование на Node.js (осень 2018)](https://www.youtube.com/watch?v=hY6Z6qNYzmc&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Асинхронное программирование на JavaScript и Node.js (ХарьковJS 2017)](https://www.youtube.com/watch?v=VdRhAXnfrd0&list=PLHhi8ymDMrQY8settDxzdTGnnb1GZ_oQC)
- [Асинхронное программирование с библиотекой Metasync (OdessaJS 2017)](https://www.youtube.com/watch?v=XRSxsw0Kgms&list=PLHhi8ymDMrQY8settDxzdTGnnb1GZ_oQC)
- [Семинар и доклады на летней школе 2017](https://www.youtube.com/watch?v=pgOr3usXMXs&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Введение в Node.js (осень 2018)](https://www.youtube.com/watch?v=WBcHgaoHh1k&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Обзор Node.js API (осень 2018)](https://www.youtube.com/watch?v=sOkjR-N6IAs&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Файлы, потоки, буферы, сеть, сокеты, ошибки (лето 2017)](https://www.youtube.com/watch?v=Kqs_Qnodvj0&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Работа с файлами, буферами и файловыми потоками в Node.js (осень 2018)](https://www.youtube.com/watch?v=eQGBS15vUac&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Модули, слои, структура проекта, песочницы в JavaScript и Node.js (осень 2018)](https://www.youtube.com/watch?v=O7A9chb573E&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Исправление Keep Alive Timeout в NodeJS (OdessaJS 2015)](https://www.youtube.com/watch?v=Q8ohKdYrpRA&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Клиент-сервер на Node.js TCP и UDP, DNS (осень 2018)](https://www.youtube.com/watch?v=bHn-wTlTTR0&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [HTTP сервер на Node.js (осень 2018)](https://www.youtube.com/watch?v=7Ufxj0oTaUo&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Примеси, обертки, дектораторы, мемоизация (осень 2018)](https://www.youtube.com/watch?v=oRQ0kQr1N-U&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Консоль и командная строка (осень 2018)](https://www.youtube.com/watch?v=5aSZyKi5BmE&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Чеининг функций и объектов, обработка ошибок (осень 2018)](https://www.youtube.com/watch?v=PfuEfIiLX34&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Таймеры, таймауты, EventEmitter в JavaScript и Node.js(осень 2018)](https://www.youtube.com/watch?v=LK2jveAnRNg&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)

## Вспомогательные материалы

- [Линтер / Linter](https://github.com/HowProgrammingWorks/Tools)
  - статический анализатор кода (без запуска), который может определить и
  предложить стилистические, грамматические или оптимизационное улучшение или
  просто выявить проблему (а иногда и исправить ее автоматически)
- Система контроля версий
- Менеджер пакетов
- Непрерывная интеграция
- Тестирование

Видео:
- [Настройка среды: Node.js, npm, git, eslint (осень 2018)](https://www.youtube.com/watch?v=hSyA7tcNaCE&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)

## Структуры данных

- [Запись или структура / Struct or Record](https://github.com/HowProgrammingWorks/DataStructures)
- [Массив / Array](https://github.com/HowProgrammingWorks/DataStructures)
- [Буфер / Buffer](https://github.com/HowProgrammingWorks/Buffers)
- [Список / List](https://github.com/HowProgrammingWorks/LinkedList)
  - Односвязный, двусвязный, кольцевой, развернутый список (список массивов)
  - Реализация на объектах, массивах и замыканиях
  - Реализация на синтаксисе прототипов, классов и фабрик
  - Реализация на замыканиях и функциональных объектах
  - Реализация на одной и двух категориях (только узел или список и узел)
- [Стек, очередь, дек](https://github.com/HowProgrammingWorks/Dequeue)
  - Стек / Stack - Список, работающий про принципу LIFO
  - Очередь / Queue - Список, работающий про принципу FIFO
  - [Дек / Dequeue](https://github.com/HowProgrammingWorks/Dequeue)
  двухсторонняя очередь (одновременно LIFO и FIFO)
- [Дерево](https://github.com/HowProgrammingWorks/Trees)
- [Двоичное дерево](https://github.com/HowProgrammingWorks/Trees),
поисковое дерево, красно-черное дерево
- Куча / Heap - древовидная структура данных или область памяти для динамического
  распределения под хранение данных
- [Граф / Graph](https://github.com/HowProgrammingWorks/Graph)
- [Буфер / Buffer](https://github.com/HowProgrammingWorks/Buffers)
  - область памяти для хранения данных (обычно для операций ввода/вывода)
- Типизированные массивы
- [Коллекция / Collection](https://github.com/HowProgrammingWorks/Collections)
  - структура данных, служащая для хранения набора значений и предоставляющая
  доступ к ним по индексам или ключам
- [Множество / Set](https://github.com/HowProgrammingWorks/Set)
  - структура данных, реализующая математическое "множество"
  - структура данных, служащая для хранения однородного набора значений, которые
  не имеют индексов или ключей (но внутри структуры данных они должны иметь
  порядок, например, индекс в массиве, однако, множество абстрагирует нас от
  этой особенности реализации)
- [Ключ-значение, Хешмап / Map, Key-value](https://github.com/HowProgrammingWorks/KeyValue)
  - [класс `Map`](https://github.com/HowProgrammingWorks/Map)

## Расширенные понятия

- [Сборка мусора / Garbage Collection](https://github.com/HowProgrammingWorks/GarbageCollection)
- [Прокси / Proxy](https://github.com/HowProgrammingWorks/Proxy)
- [Символ / Symbol](https://github.com/HowProgrammingWorks/Symbol)
- [Дифер / Deferred](https://github.com/HowProgrammingWorks/Callbacks)
- [Промис / Promise](https://github.com/HowProgrammingWorks/Promise)
- [Фьючер / Future](https://github.com/HowProgrammingWorks/Callbacks)
- [Асинхронность при помощи async/await](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
- [Асинхронная композиция / Asynchronous Composition](https://github.com/metarhia/metasync/blob/master/lib/composition.js)
- [Коллекторы данных / Data and Key Collectors](https://github.com/metarhia/metasync/blob/master/lib/collector.js)
- Неизменяемые данные / Immutable Data
- Изменяемые данные / Mutable Data
- Интроспекция / Introspection
- Рефлексия / Reflection
- Скаффолдинг / Scaffolding
- [Инверсия управления / IoC, Inversion of Control](https://github.com/HowProgrammingWorks/InversionOfControl)
- [Внедрение зависимостей / DI, Dependency Injection](https://github.com/HowProgrammingWorks/DependencyInjection)
- [Межпроцессовое взаимодействие / IPC, Interprocess Communication](https://github.com/HowProgrammingWorks/InterProcessCommunication)
- [Песочница / Sandbox](https://github.com/HowProgrammingWorks/Sandboxes)
- Архитектура / Architecture
- Слой доступа к данным / Data Access Layer
- Курсор / Cursor
- Объектно-реляционное отображение / ORM, Object-relational Mapping
- [Сервер / Server](https://github.com/HowProgrammingWorks/NodeServer)
  - [Приклеивание по IP или идентификатору сессии / IP or Session Sticky](https://github.com/HowProgrammingWorks/NodeServer/tree/master/ip-sticky)
  - Кластеризация / Cluster mode
    - При помощи [cluster](https://github.com/HowProgrammingWorks/NodeServer/tree/master/native-cluster)
    - при помощи [child_process](https://github.com/HowProgrammingWorks/NodeServer/tree/master/native-cp)
- Сервер приложений / Application Server
- Тонкий клиент и толстый клиент
- [Проекция данных / Projection](https://github.com/HowProgrammingWorks/Projection)
- [Измерение производительности / Benchmarking](https://github.com/HowProgrammingWorks/Benchmark)
- [Интерфейс командной строки / CLI, Command Line Interface and Console](https://github.com/HowProgrammingWorks/CommandLine)
- [Мониторинг файловой системы / File System Watching](https://github.com/HowProgrammingWorks/FilesystemWatch)
- [Транзакционные объекты/Transaction](https://github.com/HowProgrammingWorks/Transaction)
- [Метаданные / Metadata](https://github.com/HowProgrammingWorks/Metaprogramming)
- [Протокол / Protocol](https://github.com/metarhia/metacom)
- [Динамическая загрузка модулей / Live Code Reload](https://github.com/HowProgrammingWorks/LiveReload)
- Http Request (HTTP, XMLHttpRequest, fetch): [примеры](https://github.com/HowProgrammingWorks/HttpRequest)
- [Неблокирующие итерации](https://github.com/HowProgrammingWorks/NonBlocking)

Видео:
- [Инверсия управления и внедрение зависимостей (осень 2018)](https://www.youtube.com/watch?v=Fz86Fdjz-LM&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Измерение производительности кода и оптимизация (осень 2018)](https://www.youtube.com/watch?v=sanq2X7Re8o&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [Межпроцессовое взаимодействие (осень 2018)](https://www.youtube.com/watch?v=2OXWZFMvfbc&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)

## Примеры кода и комплексного использования технологий

- [Живые электронные таблицы / Live Table](https://github.com/HowProgrammingWorks/LiveTable)
- [Чат на вебсокетах / Websocket Chat](https://github.com/HowProgrammingWorks/WebsocketChat)

Видео:
- [Высоконагруженные распределенные приложения на Node.js (JS Conference 2017)](https://www.youtube.com/watch?v=7tfZDABPvVs&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
- [WebSocket сервер на Node.js, электронные таблицы и чат (осень 2018)](https://www.youtube.com/watch?v=Sf7ln3n16ws&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)

## Парадигмы программирования

- [Императивное программирование / Imperative Programming](https://github.com/HowProgrammingWorks/ImperativeProgramming)
  - Неструктурное программирование / Non-structured
  - Структурное программирование / Structured Programming
  - Процедурное программирование / Procedural Programming
  - [Object-oriented programming](https://github.com/HowProgrammingWorks/ObjectOrientedProgramming)
  - [Prototype-oriented programming](https://github.com/HowProgrammingWorks/PrototypeOrientedProgramming)
- [Функциональное программирование / Functional Programming](https://github.com/HowProgrammingWorks/FunctionalProgramming)
  - [примеры разных стилей функционального кода](https://github.com/HowProgrammingWorks/Abstractions)
- Логическое программирование / Logical Programming
- Декларативное программирование / Declarative Programming
- [Программирование управляемое данными / Data-driven Programming](https://github.com/HowProgrammingWorks/DataDrivenProgramming)
- Техники программирования
  - [Асинхронное программирование / Asynchronous Programming](https://github.com/HowProgrammingWorks/AsynchronousProgramming)
  - Реактивное программирование / Reactive Programming
- [Событийное программирование / Event-driven Programming](https://github.com/HowProgrammingWorks/EventDrivenProgramming)
- [Метапрограммирование / Metaprogramming](https://github.com/HowProgrammingWorks/Metaprogramming)

Видео:
- [Архитектурный подход к программированию (осень 2018)](https://www.youtube.com/watch?v=d_vyO2CkiOc&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Архитектура приложений и метапрограммирование](https://www.youtube.com/watch?v=LXS0PqsQvx8&list=PLHhi8ymDMrQZad6JDh6HRzY1Wz5WB34w0)
- [Слои, связанность и связность кода (осень 2018)](https://www.youtube.com/watch?v=A3RpwNlVeyY&list=PLHhi8ymDMrQZmXEqIIlq2S9-Ibh9b_-rQ)
