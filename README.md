# OOP_EXAM

1. **Основные достоинства и недостатки ООП. Понятия класса, объекта, свойства, поведения.**
   - **Достоинства ООП:**
     - Инкапсуляция данных, что обеспечивает контроль доступа и сокрытие деталей реализации.
     - Наследование позволяет создавать новые классы на основе существующих.
     - Полиморфизм позволяет работать с объектами разных классов через общий интерфейс.

   - **Недостатки ООП:**
     - Увеличенное потребление памяти и производительности из-за дополнительных абстракций.
     - Сложность при проектировании и анализе системы.
     - Возможны проблемы с производительностью в некоторых случаях.

   - **Понятия:**
     - **Класс:** Абстрактный шаблон для создания объектов. Описывает свойства и методы, которые объекты будут иметь.
     - **Объект:** Конкретный экземпляр класса, обладающий свойствами и методами, определенными в классе.
     - **Свойства:** Характеристики объекта, описывающие его состояние.
     - **Поведение:** Методы класса, определяющие, как объекты этого класса взаимодействуют и что они могут делать.

2. **Способы взаимодействия объектов. Понятие сообщения и его отличие от вызова метода.**
   - Способы взаимодействия включают вызов методов и передачу сообщений между объектами.
   - **Сообщение:** Это запрос на выполнение действия объектом. Объект, получивший сообщение, решает, как обработать это сообщение и какой метод вызвать.
   - **Вызов метода:** Это конкретное исполнение метода объектом в ответ на сообщение. Методы определены в классе и могут быть вызваны, когда объект получает соответствующее сообщение.

3. **Что такое инкапсуляция и абстракция и для чего они применяются в ООП?**
   - **Инкапсуляция:** Это принцип ООП, который заключается в объединении данных и методов, работающих с этими данными, в единый объект (класс). Инкапсуляция скрывает детали реализации и предоставляет интерфейс для взаимодействия с объектом.

   - **Абстракция:** Это процесс выделения общих характеристик объектов и игнорирования ненужных деталей. Абстракция позволяет создавать абстрактные классы и интерфейсы, которые определяют общий интерфейс для классов.

4. **Что такое наследование? Отношения типа IS-A и HAS-A. Типы наследования. Особенности применения наследования. Правило изменений и правило полиморфизма.**
   - **Наследование:** Это механизм, позволяющий классу (подклассу) наследовать свойства и методы другого класса (родительского класса). Отношение IS-A указывает на то, что подкласс является типом родительского класса.

   - **Отношение HAS-A:** Это отношение, при котором объект класса содержит или имеет ссылку на объект другого класса. Например, автомобиль HAS-A двигатель.

   - **Типы наследования:** Есть единичное (single) и множественное (multiple) наследование. Единичное наследование означает, что класс может наследовать только от одного родителя, а множественное — от нескольких.

   - **Особенности применения наследования:** Наследование позволяет повторно использовать код, способствует созданию иерархии классов, но может вести к сложностям при изменении родительских классов.

   - **Правило изменений (Liskov Substitution Principle - LSP):** Подклассы должны быть взаимозаменяемыми с родительскими классами без изменения желаемых свойств программы.

   - **Правило полиморфизма:** Объекты разных классов могут быть обработаны общим способом, если они реализуют общий интерфейс.

5. **Множественное наследование и реализация интерфейсов.**
   - **Множественное наследование:** Это возможность класса наследовать свойства и методы от нескольких родительских классов. Некоторые языки поддерживают множественное наследование, но оно может вызывать проблемы с конфликтами и читаемостью кода.

   - **Реализация интерфейсов:** Вместо множественного наследования, классы могут реализовывать интерфейсы, которые определяют об

щий набор методов без реализации. Это позволяет классам поддерживать гибкий полиморфизм.

6. **Что такое полиморфизм? Полиморфизм включения, параметрический полиморфизм и перегрузка функций.**
   - **Полиморфизм:** Это способность объектов разных классов реагировать на одинаковые сообщения или методы в соответствии с их собственным поведением.

   - **Полиморфизм включения (Inclusion Polymorphism):** Это способность объектов подклассов быть использованными вместо объектов родительского класса. Это достигается через наследование и переопределение методов.

   - **Параметрический полиморфизм (Generics):** Это способность работы с типами и структурами данных, не зависящими от конкретных типов данных. Примером являются шаблоны (generics) в языках программирования.

   - **Перегрузка функций (Function Overloading):** Это возможность определить несколько функций с одинаковым именем в одном классе, но с разными параметрами. Выбор метода выполняется на основе параметров, переданных при вызове функции.

7. **Возможные отношения между объектами. Отношение зависимости и ассоциации.**
   - **Отношение зависимости:** Это отношение, при котором объект одного класса (называемого клиентом) использует услуги другого класса (называемого поставщиком), но не имеет жесткой связи с ним. Это обычно выражается через параметры методов или создание экземпляра класса внутри другого класса.

   - **Ассоциация:** Это отношение, при котором объекты двух классов связаны между собой. Ассоциации могут быть однонаправленными или двунаправленными и могут иметь разную силу связи.

8. **Отношение простой и квалифицированной ассоциации. Ограничения. Отношения агрегации и композиции. Класс ассоциаций.**
   - **Простая ассоциация:** Это отношение, при котором объекты двух классов связаны между собой, но без дополнительных атрибутов или метаданных.

   - **Квалифицированная ассоциация:** Это ассоциация, которая имеет дополнительные атрибуты, которые называются квалификаторами, и позволяют точнее определить отношение между объектами.

   - **Агрегация:** Это отношение, при котором один объект является частью другого объекта. Он имеет жизненный цикл, не зависящий от жизненного цикла контейнера.

   - **Композиция:** Это более сильная форма агрегации, при которой объект является частью другого объекта и не может существовать вне него. Если контейнер уничтожается, то и его части также уничтожаются.

   - **Класс ассоциаций:** Это специальный класс, который описывает отношение между объектами и может иметь атрибуты, методы и метаданные, связанные с этим отношением.

9. **Отношение обобщения/специализации. Отношение реализации.**
   - **Обобщение/специализация:** Это отношение, при котором один класс (родительский) обобщает другой класс (подкласс) и определяет его общую структуру. Подклассы специализируются на более конкретных аспектах.

   - **Отношение реализации:** Это отношение, при котором класс реализует интерфейс, определенный другим классом или интерфейсом.

10. **Назначение и правила построения диаграмм классов и объектов.**
    - **Диаграмма классов:** Используется для визуализации классов, их свойств, методов и отношений между ними. Помогает в проектировании системы и понимании ее структуры. Правила построения включают классы, свойства, методы, ассоциации, наследование и интерфейсы.

    - **Диаграмма объектов:** Используется для визуализации конкретных объектов и их состояния во времени. Помогает в анализе конкретных сценариев выполнения программы. Правила включают объекты, их состояния и связи между ними.

   Эти диаграммы являются частью стандарта UML (Unified Modeling Language) и используются при проектировании программных систем.

11. **Определение деятельности. Назначение и состав диаграммы деятельностей. Плавательные дорожки и потоки объектов на диаграммах деятельностей.**
    - **Деятельность:** В контексте ООП - это выполнение действий или операций над объектами. Диаграмма деятельностей используется для визуализации последовательности действий или процессов в системе.

    - **Диаграмма деятельностей:** Это графический инструмент для моделирования процессов, состоящих из действий и решений. Она включает в себя действия, плавательные дорожки (логические группы действий) и потоки объектов, которые представляют перемещение данных между действиями.

12. **Назначение и правила построения диаграмм взаимодействий.**
    - **Диаграмма взаимодействий:** Используется для моделирования взаимодействия между объектами или компонентами системы. Она включает в себя объекты, сообщения, временные события и фрагменты диаграммы.

    - **Правила построения:** Диаграмма взаимодействий может быть представлена в двух формах: диаграмма последовательности (Sequence Diagram) и диаграмма кооперации (Collaboration Diagram). В ней показываются объекты, сообщения между объектами, фазы выполнения и множество других элементов.

13. **Необходимость моделирования и основные принципы моделирования.**
    - **Необходимость моделирования:** Моделирование позволяет абстрагировать сложные системы, упрощать их анализ и проектирование, а также обеспечивать ясное понимание и коммуникацию между разработчиками.

    - **Основные принципы моделирования:** Включают в себя абстракцию (выделение ключевых характеристик), уточнение (добавление деталей при необходимости), упрощение (сокращение сложности), формализацию (представление системы в форме моделей) и коммуникацию (использование моделей для обмена информацией).

14. **Назначение и состав языка UML.**
    - **UML (Unified Modeling Language):** Это стандартный язык моделирования, используемый для визуализации, проектирования и документирования систем. UML включает различные виды диаграмм, такие как диаграммы классов, диаграммы взаимодействия, диаграммы состояний и другие, и предоставляет стандартизированный набор символов и правил для моделирования.

15. **Понятие архитектуры программной системы и основные виды на архитектуру, рекомендуемые RUP.**
    - **Архитектура программной системы:** Это общая структура и организация системы, включая компоненты, их взаимосвязи и принципы проектирования, которые определяют ее поведение и структуру.

    - **Виды архитектур:** Включают в себя однослойную (monolithic), двухслойную (two-tier), трехслойную (three-tier), многослойную (n-tier), архитектуру «гексагон» (hexagonal architecture) и другие.

    - **Рекомендуемые RUP:** RUP (Rational Unified Process) рекомендует использовать трехслойную архитектуру, которая разделяет систему на слои для легкости управления, поддержки и изменений.

16. **Понятие объекта и задач построения ИС с точки зрения объектов. Назначение и структура CRC-карточек.**
    - **Объект:** В контексте ООП, объект представляет конкретный экземпляр класса и обладает свойствами и методами, определенными в этом классе.

    - **Построение ИС с точки зрения объектов:** Подход, при котором система разрабатывается с учетом объектов и их взаимодействия. Моделирование объектов и их взаимодействия помогает проектировать систему более структурированно и гибко.

    - **CRC-карточки (Class-Responsibility-Collaboration):** Это инструмент для описания классов в системе. Карточка включает в себя имя класса, его обязанности (responsibility) и с кем он сотрудничает (collaboration). CRC-карточки помогают определить структуру классов и их взаимодействие.

17. **Понятие шаблона проектирования и структура шаблонов GRASP.**
    - **Шаблон проектирования:** Это повторяемое решение проблемы, которое может быть использовано в разных контекстах и для разных задач. Шаблоны проектирования помогают решать типичные проблемы в проектировании ПО.

    - **GRASP (General Responsibility Assignment Software Patterns):** Это набор принципов и шаблонов проектирования, которые помогают выделить ответственности (responsibilities) в системе и назначить их объектам

. Принципы GRASP включают в себя принцип единственности ответственности и другие.

18. **Назначение, состав и правила построения диаграмм вариантов использования.**
    - **Диаграмма вариантов использования (Use Case Diagram):** Используется для визуализации функциональных требований системы и ее взаимодействия с акторами (пользователями или другими системами).

    - **Состав:** Включает акторов, варианты использования (use cases), и связи между ними.

    - **Правила построения:** Акторы представляют роли пользователей или внешних систем, варианты использования описывают функциональность системы, а связи между ними показывают, какие варианты использования могут быть выполнены акторами.

19. **Правила построения и шаблоны сценариев вариантов использования.**
    - **Сценарий варианта использования:** Это конкретный путь выполнения варианта использования. Он описывает шаги, которые пользователь или система выполняют для достижения определенной цели.

    - **Правила построения:** Сценарии включают описание шагов, включая действия и альтернативы, связанные с вариантом использования.

    - **Шаблоны сценариев:** Это общие структуры или шаблоны для описания сценариев, такие как "основной сценарий" и "альтернативные сценарии", которые помогают структурировать описание.

20. **Определение состояния. Назначение, состав и правила построения диаграммы состояний.**
    - **Состояние:** Состояние объекта определяет его текущее поведение и характеристики в определенный момент времени.

    - **Диаграмма состояний (State Diagram):** Используется для моделирования различных состояний объекта и переходов между ними в зависимости от событий.

    - **Правила построения:** Диаграмма состояний включает в себя состояния, переходы между ними, события, действия и начальное/конечное состояния.

21. **Основные виды событий. Понятие сторожевого условия и действия.**
    - **Событие:** Это сигнал или действие, которое приводит к изменению состояния объекта или системы.

    - **Виды событий:** Включают в себя внешние события (события, инициированные внешними акторами), внутренние события (события, инициированные самой системой) и временные события (события, связанные с временем).

    - **Сторожевое условие (Guard Condition):** Это условие, которое определяет, должен ли быть выполнен определенный переход между состояниями.

    - **Действие (Action):** Это действие, которое выполняется при входе в состояние или при выполнении перехода.

22. **Правила построения диаграмм состояний.**
    - Правила включают в себя определение начального состояния, конечных состояний, переходов между состояниями, событий и сторожевых условий. Диаграмма должна быть понятной и легко читаемой.

23. **Шаблоны проектирования Expert, High Cohesion и Low Coupling.**
    - **Expert (Эксперт):** Шаблон, при котором задача делегируется объекту, обладающему необходимой информацией и функциональностью.

    - **High Cohesion (Высокая связность):** Принцип, при котором функционально схожие элементы должны быть внутри одного модуля или класса.

    - **Low Coupling (Низкая связность):** Принцип, при котором компоненты системы должны быть слабо связаны друг с другом, что обеспечивает более гибкую и поддерживаемую систему.

24. **Шаблоны проектирования Creator и Controller.**
    - **Creator (Создатель):** Шаблон, который определяет, что один класс (создатель) отвечает за создание экземпляров другого класса.

    - **Controller (Контроллер):** Шаблон, который определяет, что один класс (контроллер) управляет координацией действий между другими классами.

25. **Состав и назначение SOLID-принципов. Формулировка, назначение и примеры использования принципа наименьшего знания (PLK).**
    - **SOLID:** Это набор пяти основных принципов, которые способствуют созданию гибких, поддерживаемых и расширяемых систем.

    - **Принцип наименьшего знания (Law of Demeter или Least Knowledge - PLK):** Этот принцип гласит,

 что объект должен взаимодействовать только с ближайшими соседями и не должен иметь знания о внутренних деталях других объектов. Это уменьшает зависимости между объектами и делает систему более гибкой и изменяемой.

26. **Принцип открытости/закрытости (OCP) и его соответствие шаблонам полиморфизм и защита от изменений.**
    - **Принцип открытости/закрытости (Open/Closed Principle - OCP):** Этот принцип гласит, что классы должны быть открыты для расширения (новая функциональность может быть добавлена) и закрыты для модификации (существующий код не должен изменяться).

    - **Соответствие шаблонам полиморфизма и защита от изменений:** Применение OCP может быть достигнуто через использование полиморфизма, шаблонов проектирования и абстракций, что позволяет добавлять новую функциональность без изменения существующего кода.

27. **Формулировка и назначение принципа подстановки Liskov (LSV).**
    - **Принцип подстановки Лисков (Liskov Substitution Principle - LSP):** Этот принцип гласит, что объекты подклассов должны быть способны заменить объекты родительского класса без изменения желаемых свойств программы.

28. **Назначение и структура принципа разделения интерфейсов (ISP).**
    - **Принцип разделения интерфейсов (Interface Segregation Principle - ISP):** Этот принцип гласит, что клиенты не должны зависеть от интерфейсов, которые они не используют. Интерфейсы должны быть разделены на более мелкие и специфичные интерфейсы, чтобы избежать ненужных зависимостей.

29. **Понятие логического компонента, части системы, порта. Построение диаграмм составных частей компонентов.**
    - **Логический компонент:** Это часть системы, которая выполняет определенные функции и может быть выделена как независимый модуль.

    - **Части системы:** Это элементы, из которых состоит система, такие как классы, объекты, функции и др.

    - **Порт:** Это точка входа или выхода для взаимодействия между компонентами или системами.

    - **Диаграммы составных частей компонентов:** Используются для визуализации взаимосвязей между компонентами, их портами и связями.

30. **Понятие компонента и интерфейса. Реализуемый и требуемый интерфейс. Диаграмма внутренней структуры с указанием способов соединения частей.**
    - **Компонент:** Это независимая и переиспользуемая часть системы, которая обычно имеет четкую границу и предоставляет определенную функциональность.

    - **Интерфейс:** Это контракт, который определяет, как компоненты или системы могут взаимодействовать друг с другом.

    - **Реализуемый интерфейс:** Это интерфейс, который компонент реализует, чтобы предоставить определенную функциональность.

    - **Требуемый интерфейс:** Это интерфейс, который компонент ожидает от другого компонента, чтобы взаимодействовать с ним.

    - **Диаграмма внутренней структуры:** Используется для визуализации внутренней структуры компонента, включая его части и связи между ними.

31. **Понятие физического компонента и правила построения диаграмм физических компонентов.**
    - **Физический компонент:** Это конкретная реализация компонента, которая может быть развернута и выполнена на физическом оборудовании или сервере.

    - **Правила построения диаграмм физических компонентов:** Диаграммы физических компонентов используются для визуализации физической архитектуры системы, включая серверы, сети, оборудование и взаимодействие между ними. Они должны быть четкими и информативными, чтобы облегчить развертывание и управление системой.

32. **Связь классов и компонентов. Виды физических компонентов.**
    - Классы и компоненты могут взаимодействовать через интерфейсы и порты. Физические компоненты представляют собой реализации компонентов на физическом оборудовании и могут быть серверами, базами данных, веб-серверами и т. д.

33. **Назначение и структура принципа инверсии зависимостей (DIP).**
    - **Принцип инверсии зависимостей (Dependency In

version Principle - DIP):** Этот принцип гласит, что высокоуровневые модули не должны зависеть от низкоуровневых модулей. Оба должны зависеть от абстракций. Абстракции не должны зависеть от деталей. Детали должны зависеть от абстракций.

34. **Принцип проектирования компонентов: Release Reuse Equivalency Principle REP.**
    - **Release Reuse Equivalency Principle (REP):** Этот принцип гласит, что компоненты должны быть разработаны и выпущены на уровне эквивалентности, чтобы обеспечить их повторное использование.

35. **Принцип проектирования компонентов: Common Closure Principle CCP.**
    - **Common Closure Principle (CCP):** Этот принцип гласит, что компоненты, которые изменяются вместе, должны находиться в одном и том же компоненте или модуле. Это способствует снижению зависимостей и упрощает управление изменениями.

36. **Принцип проектирования компонентов: Common Reuse Principle CRP.**
    - **Common Reuse Principle (CRP):** Этот принцип гласит, что компоненты не должны зависеть от того, что они не используют. Если компонент использует только часть другого компонента, то он не должен зависеть от всего этого компонента.

37. **Принцип проектирования компонентов: Acyclic Dependencies Principle ADP.**
    - **Acyclic Dependencies Principle (ADP):** Этот принцип гласит, что зависимости между компонентами не должны создавать циклические зависимости. Циклические зависимости между компонентами могут быть сложными и затруднять понимание и изменение системы.

38. **Принцип проектирования компонентов: Stable Dependencies Principle SDP.**
    - **Stable Dependencies Principle (SDP):** Этот принцип гласит, что более стабильные компоненты (которые редко меняются) должны зависеть от менее стабильных компонентов (которые часто меняются), чтобы минимизировать влияние изменений.

39. **Принцип проектирования компонентов: Stable Abstractions Principle SAP.**
    - **Stable Abstractions Principle (SAP):** Этот принцип гласит, что компоненты должны быть стабильными (мало подвержены изменениям) и абстрактными (предоставляющими абстракции), чтобы обеспечить гибкость и понимание системы.

40. **Шаблоны архитектуры для построения объектно-ориентированного приложения (трехслойная, трехслойная с DIP, с моделью предметной области, гексагональная).**
    - **Трехслойная архитектура:** Это архитектурный шаблон, который разделяет приложение на три уровня: представление (presentation), бизнес-логика (business logic) и хранилище данных (data storage). Это облегчает разделение ответственностей и поддерживает модульность.

    - **Трехслойная архитектура с DIP:** Это улучшенная версия трехслойной архитектуры, которая следует принципу инверсии зависимостей (DIP). Это позволяет сделать систему более гибкой и менее зависимой от конкретных реализаций.

    - **Архитектура "гексагон" (Hexagonal Architecture):** Это архитектурный шаблон, который разделяет систему на внешние (пользовательские) и внутренние (бизнес-логика) порты. Он позволяет легко заменять внешние компоненты и поддерживать независимость.

41. **Назначение и состав диаграмм развертывания.**
    - **Диаграмма развертывания (Deployment Diagram):** Используется для моделирования физической архитектуры системы, включая серверы, клиентские устройства, сети и связи между ними.

    - **Состав:** Включает в себя узлы (nodes), компоненты, артефакты и связи между ними.

42. **Назначение логических и физических объектов. Логические и физические компоненты. Сервисы.**
    - **Логические объекты:** Это абстракции и сущности, которые представляют логическую модель системы, такие как классы, интерфейсы и др.

    - **Физические объекты:** Это конкретные реализации логических объектов, которые могут быть развернуты на физическом оборудовании.

    - **Логические компоненты:** Это абстракции функциональных частей системы, которые могут быть реализованы физическими компонентами.

    - **Физические компоненты:** Это реализации логических компонентов

 на физическом оборудовании или серверах.
    - **Сервисы:** Это компоненты или объекты, предоставляющие определенную функциональность или API для взаимодействия с системой.

43. **Назначение, классификация и состав специальных шаблонов проектирования.**
    - **Специальные шаблоны проектирования:** Это шаблоны, которые решают специфические проблемы или задачи в контексте определенных предметных областей или технологий.

    - **Классификация:** Включает в себя шаблоны для работы с базами данных (ORM), шаблоны для создания пользовательских интерфейсов (MVVM, MVC), шаблоны для многопоточности и другие.

44. **Проблема и решение шаблона Composite. Пример применения шаблона.**
    - **Проблема:** Как организовать объекты в древовидную структуру, чтобы они могли быть обращены как к единичным объектам, так и к группам объектов?

    - **Решение (шаблон Composite):** Создать абстрактный класс, который представляет как листовые объекты, так и контейнеры. Листовые объекты наследуются от этого класса, а контейнеры могут содержать другие объекты (и даже другие контейнеры).

    - **Пример применения:** Графический редактор, где фигуры могут быть составными и состоять из более мелких фигур.

45. **Проблема и решение шаблона Decorator. Пример применения шаблона.**
    - **Проблема:** Как добавить новую функциональность к объекту без изменения его структуры?

    - **Решение (шаблон Decorator):** Создать классы-декораторы, которые оборачивают базовый объект и добавляют к нему дополнительную функциональность, при этом сохраняя интерфейс базового объекта.

    - **Пример применения:** Фильтры изображений, где каждый фильтр может быть декоратором, добавляющим эффект к изображению.

46. **Проблема и решение шаблона Iterator. Пример применения шаблона.**
    - **Проблема:** Как обеспечить доступ к элементам коллекции без раскрытия ее внутренней структуры?

    - **Решение (шаблон Iterator):** Создать интерфейс итератора, который предоставляет методы для перебора элементов коллекции, а затем реализовать этот интерфейс для конкретных коллекций.

    - **Пример применения:** Перебор элементов списка, массива или дерева без знания о его внутренней структуре.

47. **Проблема и решение шаблона Bridge. Пример применения шаблона.**
    - **Проблема:** Как разделить абстракцию от ее реализации, чтобы они могли изменяться независимо?

    - **Решение (шаблон Bridge):** Создать две иерархии классов - одну для абстракции и одну для реализации. Затем связать их между собой, чтобы можно было изменять их независимо.

    - **Пример применения:** Графический интерфейс, где абстракция представляет элементы интерфейса (кнопки, окна), а реализация определяет, как они будут отображаться на разных платформах (Windows, macOS).

48. **Пакеты и правила построения диаграмм пакетов.**
    - **Пакет:** Это средство организации и структурирования элементов в UML-диаграмме, которые связаны общим функциональным назначением или темой.

    - **Правила построения диаграмм пакетов:** Диаграммы пакетов используются для группировки и организации элементов модели. Они могут содержать классы, компоненты, интерфейсы и другие элементы. Пакеты помогают упростить управление большими и сложными моделями, разделяя их на логические части.
