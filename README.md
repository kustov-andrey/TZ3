# TZ3

## Система доставки готовой еды из ресторанов.

> Все диаграммы представленны в двух видах. В основной папке репозитория представленны диаграммы в виде пнг файлов для более удобного ознакомления, тогда как в папке "UML_orig" все файлы представленны в исходном .drawio формате.

В данном ТЗ я хочу представить диаграммы, разработанные для системы доставки готовой еды из ресторанов и прочих заведений общественного питания. 

### Диаграмма вариантов использования (Use Case Diagram)

Данная система имеет в себе несколько акторов, таких как:

- Клиент
- Банк
- Ресторан
- Курьер
- Техническая поддержка

Диаграмма вариантов использования в UML используется для описания функциональности системы с точки зрения ее пользователей. Основная цель диаграммы вариантов использования - показать, как различные акторы (пользователи или другие системы) взаимодействуют с системой для достижения определенных целей. Все акторы описанные выше, представленны в моей диаграмме вариантов использования в файле под названием "UseCaseUML". Данные акторы непосредственно взаимодействуют между собой для успешного выполнения заказа и его оплаты.

### Диаграмма последовательности  (Sequence Diagram)

Диаграмма последовательностей использования в UML используется для визуализации взаимодействия объектов в рамках определенного сценария или последовательности действий. Она позволяет понять, как объекты обмениваются сообщениями и взаимодействуют друг с другом во времени.

На моем примере (файл с названием SequenceUML) можно наглядно изучить, как именно работает процесс доставки от регистрации клиента в приложении, до получения готового заказа.

### Диаграмма состояний для заказа (State Diagram)

Диаграмма состояний в UML используется для описания жизненного цикла объекта в системе. Она показывает, как объект переходит из одного состояния в другое в ответ на внешние события или внутренние условия.

В файле (StateUML) диаграмма состояний показывает, в каких состояниях может находиться статус заказа на протяжении всего процесса выполнения ордера.

### Диаграмма деятельности (Activity Diagram)

Диаграмма деятельности в UML используется для визуализации последовательности действий или процессов в системе. Она позволяет описать, какие действия выполняются, как они связаны между собой и какие условия или ветвления могут возникнуть в процессе.

В файле (ActivityDiagramUML) представлена диаграмма деятельности, в которой рассмотрены различные исходы событий, которые могут возникнуть во время исполнения заказа.

### Диаграмма классов (Class Diagram)

Диаграмма классов в UML используется для визуализации структуры классов в системе, их атрибутов, методов и отношений между классами. Она представляет собой одну из основных диаграмм, которая помогает разработчикам и аналитикам программного обеспечения лучше понять и описать структуру системы.

В файле (ClassUML) можно рассмотреть классы, используемые в системе, их атрибуты и отношения между друг другом.
