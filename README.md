# Programming Dictionary

## Базовые понятия

- [Абстракция / Abstraction](https://github.com/HowProgrammingWorks/Abstractions)
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
  - переменная предоставляет возможностью менять значение (а для некоторых
  языков и тип)
  - `let cityName = 'Beijing';`
- [Константа / Constant](https://github.com/HowProgrammingWorks/DataTypes)
  - имя (идентификатор), с которым связано не изменяемое значение и тип
  - `const WATCH_TIMEOUT = 5000;`
- [Типы данных / Data Types](https://github.com/HowProgrammingWorks/DataTypes)
  - тип - это множесво значений и операции, определенные на этом множестве
  - `[5, 'Kiev', true, { city: 'Beijing' }, a => ++a ].map(x => typeof(x));`
- [Скалярные типы / Scalar Types](https://github.com/HowProgrammingWorks/DataTypes)
  - примитивные типа данных, передаваемые по значению, а не по ссылке
  - Наверно: `Number, String, Boolean`
- [Ссылочные типы / Reference](https://github.com/HowProgrammingWorks/DataTypes)
  - типы данных, передаваемые по ссылке, а не по значению
  - Наверно: `Object, Function, Array`
- [Объект / Object](https://github.com/HowProgrammingWorks/DataTypes)
  - структура данных, содержащая состояние и методы, связанные с этим состоянием
  - объект может быть создан как литерал `{}` или экземпляр класса
  `new ClassName()` или как экземпляр прототипа `new PrototypeConstructor()` или
  возвращен из фабрики
  - `const person = { name: 'Marcus', city: 'Roma', born: 121 };`
  - `const person = new Person('Marcus', 'Roma', 121);`
- Инстанциирование / Instantiation
  - создание объекта (экземпляра) или выделение памяти для структуры данных
  - `const rect = new Rectangle(-50, -50, 100, 150);`
  - `const rect = { a: { x: -50, y: -50}, b: { x: 100, y: 150 } };`
  - `const cities = new Array(1000);`
  - `const cities = ['Tehran', 'Kiev', 'Yalta', 'Beijing', 'Potsdam', 'London'];`
- Класс / Class *
  - программная абстракция, обобщающая свойства и методы, состояние и поведение
  своих экземпляров
  - `class Point { constructor(x, y) { this.x = x; this.y = y; } }`
- [Прототип / Prototype](https://github.com/HowProgrammingWorks/Prototype)
  - специальный объект, на который ссылаются его экземпляры, и свойства
  которого становятся видны у наследников, если эти свойства не переопределены
  у наследников (формируется цепочка прототипов, по которой последовательно
  ищутся свойства, пока не будут найдены или пока не будет достигнут конец)
  - шаблон, который клонируется во время инстанциирования
- Флаг / Flag
  - `let flagName = false;`
  - Логическое значение, определяющее состояние чего-либо, например, признак
  закрытия соединения, признак завершения поиска по структуре данных и т.д.
- [Cтруктуры данных](https://github.com/HowProgrammingWorks/DataStructures)
- Массив / Array
  - коллекция эллементов, доступ к которым осуществляется по индексам
  - `const cities = ['Tehran', 'Yalta', 'Potsdam'];`
- [Функция](https://github.com/HowProgrammingWorks/Function)
  - Определения
    - Функциональное программирование: отображение или преобразование, элементов
    одного множества в элементы другого множества
    - Императивное программирование: ссылка на блок операторов (не обяхательно
    именованный), реализующий последовательность действий
    - Обобщенное определение: выражение или блок операторов имеющий имя или
    анонимный, преобразующий аргументы в результаты или изменяющий состояние
    контекстов или объектов
  - [Контекст](https://github.com/HowProgrammingWorks/Function)
  - [Область видимости / Scope](https://github.com/HowProgrammingWorks/Function)
  - Объявление функции / Function definition
    - `function max(a, b) { return a + b; }`
  - Функциональное выражение / Function expression
    - Функциональное выражение с именованной функцией / Named function expression
      - `const max = function max(a, b) { return a + b; };`
    - Анонимное функциональное выражение / Anonymous function expression
      - `const max = function(a, b) { return a + b; };`
    - Лямбда функция / Lambda function
      - `const max = (a, b) => { return a + b; };`
    - Лябмда выражение, Функция-стрелка / Lambda expression, Arrow function
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
    - если `f` возвращает `g`, то говорят, что экземпляр `g` замкнут контекст `f`
    - способ, позволяющий связать функцияю с контекстом (с данными или
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
    - Если функция только в аргументах, то это колбек
    - Если функция только в результате, то это фабрика функций
      - !!! Если в аргументах f, результат f, но не обертка
    - Если функция в аргументах и в результате, то это обертка
    - !!! фабрика конструкторов
  - Функциональное наследование / Functional Inheritance
    - При помощи: замыканий, ч.п., какрирования, лямбд
- [Метод / Method](https://github.com/HowProgrammingWorks/Function)
  - `{ a: 10, b: 10, sum() { return this.a + this.b; } }`
  - Функция, связанная с объектным контекстом или программным интерфейсом
- [Обертка / Wrapper](https://github.com/HowProgrammingWorks/Wrapper)
  - функция, которая оборачивает другую функцию (иногда объект, интерфейс или
  функциональный объект), добавляя ему дополнительное поведение
  - можно обернуть целый API интерфейс и даже асинхронную функцию вместе с
  колбеками (если известен контракт)
- Интерфейс / Interface
  - Набор методов (функций) объединенных или общим объектным контекстом или
  применением к структурам данных одной предметной области т.е. смыслом (API)
  - Способ спецификации контракта, по которому связаны программные компоненты
  - Набор методов с их именами, аргументами и типами аргументов
- Программный интерфейс / Application Interface, API
  - Интерфейс программных компонентов: модулей, слоев абстракции, приложений
- [Синглтон / Singleton](https://github.com/HowProgrammingWorks/Singleton) *
  - Шаблон проектирования, предполагающий, что в одном пространстве имен
  (процессе, приложении, базе данных) будет только один экземпляр класса
  (или просто один подобный объект) к которому можно обратиться по определенному
  (известному) имени
- [Функция обратного вызова, колбек / Callback](https://github.com/HowProgrammingWorks/Callbacks)
  - Функция передаваемая в качестве аргумента в другую функцию (или метод)
  для того, чтобы быть вызванной для возврата значения, ошибки или уведомления
  - Функции обратного вызова имеют подтипы:
    - Один раз вызываемые (чаще всего)
    - [Событие / Event](https://github.com/HowProgrammingWorks/Callbacks)
    - [Лисенер / Listener](https://github.com/HowProgrammingWorks/Callbacks)
- [Итерирование / Iteration](https://github.com/HowProgrammingWorks/Iteration)
  - Многократное повторение одного блока кода или одной функции над различными
  данными: элементами массивов, множдеств, списков, коллекций и различными
  значениями переменной цикла
- [Итератор / Iterator](https://github.com/HowProgrammingWorks/Iteration)
  - Интерфейс доступа к элементам коллекции: массива, множества, списка
- [Цикл / Loop](https://github.com/HowProgrammingWorks/Iteration)
  - Многократное исполнение блока операторов
- [Условие / Conditional statements](https://github.com/HowProgrammingWorks/Conditional)
  - Синтаксическая конструкция, позволяющая выполнить разные действия или
  возвращающая разные значения (тернарный оператор) в зависимости от логического
  выражения (возвращающего true или false)
- [Строка / String](https://github.com/HowProgrammingWorks/String)
  - Последовательность символов (в большинстве языков к каждому символу можно
  обратиться через синтаксис доступа к элементам массива, например, квадратные
  скобки)
- [Коллекция / Collection](https://github.com/HowProgrammingWorks/Collections) *
  - Структура данных, служащая для хранения набора значений и предоставляющая
  доступ к ним по индексам или ключам
- [Множество / Set](https://github.com/HowProgrammingWorks/Set) *
  - Структура данных, реализующая математическое "множество"
  - Структура данных, служащая для хранения одногодного набора значений, которые
  не имеют индексов или ключей (но внутри структуры данных они должны иметь
  порядок, например, индекс в массиве, однако, множество абстрагирует нас от
  этой особенности реализации)
- [Ключ-значение, Хешмап / Map, Key-value](https://github.com/HowProgrammingWorks/KeyValue)
- [Список / List](https://github.com/HowProgrammingWorks/LinkedList) *
- [Дерево](https://github.com/HowProgrammingWorks/TreeNode) *
- [Граф / Graph](https://github.com/HowProgrammingWorks/DirectedGraph) *
- [Файл / File](https://github.com/HowProgrammingWorks/Files) *
- [Поток, Файловый поток / Stream, File Stream](https://github.com/HowProgrammingWorks/Streams) *
- [Буфер / Buffer](https://github.com/HowProgrammingWorks/Buffers) *
- [Сокет / Socket](https://github.com/HowProgrammingWorks/Socket) *
- [Дескриптор / Descriptor](https://github.com/HowProgrammingWorks/Files) *
- Состояние / State *
- Кэш, Кэширование / Cache *
- Хэш, Хэширование / Hashing *
- [Функциональный объект](https://github.com/HowProgrammingWorks/Functor)
  - [Функтор / Functor](https://github.com/HowProgrammingWorks/Functor)
    - Рекурсивное замыкание / Recursive closure
    - Объект функционального типа, хранящий в себе защищенное значение и
    позволяющий отобразить это значение в другой функтор через функцию
  - [Аппликативный функтор](https://github.com/HowProgrammingWorks/Functor) *
  - Монада / Monad *
- [Мемоизация / Memoization](https://github.com/HowProgrammingWorks/Memoization) *
- [Примесь / Mixin](https://github.com/HowProgrammingWorks/Mixin) *
  - Добавление свойств, методов или поведения к объекту после его
  инстанциирования (создания)
- Декоратор / Decorator *
- [Наследование / Inheritance](https://github.com/HowProgrammingWorks/Function) *
- Множественное наследование / Multiple Inheritance *
- Непрямое наследование / Indirect Inheritance *
- [Генератор / Generator](https://github.com/HowProgrammingWorks/Generator) *
- [Синхронные операции](https://github.com/HowProgrammingWorks/AsynchronousProgramming) *
- [Асинхронные операции](https://github.com/HowProgrammingWorks/AsynchronousProgramming) *
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
- [Сериализация / Serialization](https://github.com/HowProgrammingWorks/Serialization) *
  - преобразование структуры данных (развернутую в памяти) в битовую
  последовательность, обычно в последовательность байтов: бинарная сериализация
  или в строку - текстовая сериализация
- [Десериализация / Deserialization](https://github.com/HowProgrammingWorks/Serialization) *
  - операция обратная сериализации, т.е. восстановление структуры данных
  из последовательности битов (чаще байтов или строки)
- Парсинг / Parsing
  - синтаксический анализ текста, результатом чего может явзяться:
    - для формальной граматики - AST-дерево *
    - для слабоструктурированного документа - структура данных, имеющая
    четкую структуру, в которую частично перенесены данные из слабой структуры
    - для других естественных или искуственных языков - информационные модели,
    им соответствующие
- [Регулярные выражения / Regular Expressions](https://github.com/HowProgrammingWorks/RegExp) *
  - синтаксическая конструкция, паттерн, формальный язык, определяющий
  порядок парсинга другой синтаксической конструкции
- [Модуль, модульность](https://github.com/HowProgrammingWorks/Modularity) *
  - целостный, функционально полный, независимый компонент программной системы
  имеющий имя, интерфейс, реализацию
  - модульность повышает переиспользование кода, упрощает интеграцию компонентов,
  улучшает компоновку и тестирование программ по частям
  - ограничения: модули не должны использовать глобальные переменные или
  модифицировать базовые классы/прототипы/функции языка программирования,
  платформы и/или фреймворка; модули должны быть слабо связаны, взаимодействовать
  друг с другом только через внешнее API (предпочтительно) или шину событий
  (если система построена на событийной модели, подписке или модели акторов)
- [Зависимость / Dependency](https://github.com/HowProgrammingWorks/Project) *
  - связанность программных компонентов, при которой один компонент (зависимый)
  "знает" другой; это значит, что в нем помещен вызов метода (реализация которого
  содержится в другом) или он слушает событие, которое генерирует другой или
  он "знает" структуры данных, которые могут быть переданы из другого компонента
- [Линтер / Linter](https://github.com/HowProgrammingWorks/Tools)
  - статический анализатор кода (без запуска), который может определить и
  предложить стилистические, грамматические или оптимизационное улучшение или
  просто выявить проблему (а иногда и исправить ее автоматически)
- Декомпозиция / Decomposition
  - разделение программного компонента на части по принципу функциональности,
  при этом, каждая часть будет решать подзадачу и появится часть кода, которая
  определяет порядок связи всех частей (композицию)
- [Ленивость / Lazy](https://github.com/HowProgrammingWorks/Lazy)
- [Обработка ошибок / Error handling](https://github.com/HowProgrammingWorks/Errors)
- Фабрика / Factory

## Расширенные понятия

- [Сборка мусора / Garbage Collection](https://github.com/HowProgrammingWorks/GarbageCollection)
- [Прокси / Proxy](https://github.com/HowProgrammingWorks/Proxy)
- [Символ / Symbol](https://github.com/HowProgrammingWorks/Symbol)
- [Дифер / Deferred](https://github.com/HowProgrammingWorks/Callbacks)
- [Промис / Promise](https://github.com/HowProgrammingWorks/Promise)
- [Фьючер / Future](https://github.com/HowProgrammingWorks/Callbacks)
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
- Сервер приложений / Application Server
- Тонкий клиент
- Толстый клиент
- [Проекция данных / Projection](https://github.com/HowProgrammingWorks/Projection)
- [Измерение производительности / Benchmarking](https://github.com/HowProgrammingWorks/Benchmark)
- [Интерфейс командной строки / CLI, Command Line Interface and Console](https://github.com/HowProgrammingWorks/CommandLine)
- [Мониторинг файловой системы / File System Watching](https://github.com/HowProgrammingWorks/Files)
- Метаданные
- Протокол

## Парадигмы программирования

- [Императивное программирование / Imperative Programming](https://github.com/HowProgrammingWorks/ImperativeProgramming)
  - Неструктурное программирование / Non-structured
  - Структурное программирование / Structured Programming
  - Процедурное программирование / Procedural Programming
  - [Object-oriented programming](https://github.com/HowProgrammingWorks/ObjectOrientedProgramming)
  - [Prototype-oriented programming](https://github.com/HowProgrammingWorks/PrototypeOrientedProgramming)
- [Функциональное программирование / Functional Programming](https://github.com/HowProgrammingWorks/FunctionalProgramming)
- [Логическое программирование / Logical Programming]
- [Декларативное программирование / Declarative Programming]
- [Программирование управляемое данными / Data-driven Programming](https://github.com/HowProgrammingWorks/DataDrivenProgramming)
- Техники программирования
  - [Асинхронное программирование / Asynchronous Programming]
  - [Реактивное программирование / Reactive Programming]
- [Событийное программирование / Event-driven Programming](https://github.com/HowProgrammingWorks/EventDrivenProgramming)
- [Метапрограммирование / Metaprogramming](https://github.com/HowProgrammingWorks/Metaprogramming)
