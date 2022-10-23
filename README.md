В данном репозитории представлены примеры моих работ. Некоторые были выполнены в рамках тестовых заданий, некоторые в рамках решения задач на текущей работе (с обезличиванием данных и конфиденциальных деталей).

## case_1
В рамках тестового задания необходимо было описать/нарисовать схему взаимодействия Заемщика, ПО (ЛК) и Mandarin Pay (Открытое API Mandarin: http://docs.mandarinbank.com/api_v2.html#intro). 

Задача - внедрить в Личных кабинет заемщика возможность оплаты займа (прием платежа) онлайн через платежную систему Mandarin. Авторизация запросов к API Mandarinpay осуществляется через HTTP Basic Auth. 
В папке представлен:
- описанный сценарий использования (1_Use_case)
- диаграмма последовательности в нотации UML (2_Sequence_diagram)

## case_2
Задача от заказчика - реализовать расширенную функциональную ролевую модель, для того чтобы пользователи относящиеся к разным опциям (геология/инфраструктура/геолого-насосное оборудование или ГНО) могли проводить экспертизу скважин-кандидатов на геолого-технические мероприятия.Пользователи с ролями "геология" и "инфраструктура" должны иметь возможность проводить экспертизу параллельно, пользователи с ролью "ГНО" - только после окончания экспертизы по "геологии" и "инфраструктуре".

Данные обезличены, приведены несколько примеров в виде выгрузок формата .pdf из Confluence, где велась работа над описанием бизнес-требований от заказчиков и постановкой технических требований для команды разработки.

## case_3
В данной папке приведен пример работы над общим бизнес-процессом, реализованным в системе, и ее отдельными подпроцессами, для каждого из которых требовалось оформление ТЗ, диаграмм и макетов:
- главный процесс бизнес-логики в в формате нотации BPMN (1. Главный бизнес-процесс). Красным прямоугольником обозначен свернутый подпроцесс, описание которого приведено также в данной папке для примера.
- пример описания одного из свернутых подпроцессов в формате диаграммы последовательности в нотации UML (2. Пример описания для одного из подпроцессов в виде SD UML)
- пример описания ТЗ для свернутого подпроцесса с макетом интерфейса и формулами для расчета (3. ТЗ для подпроцесса).
Контекст: бизнес-процесс проведения пользовательской экспертизы скважин-кандидатов на геолого-технические мероприятия в системе.

## case_4
В данной папке приложены примеры разработки прототипов интерфейса, выполненные в рамках учебного курса "OTUS. Системный аналитик. Advanced". 
Контекст: разработка требований к системе бронирования столиков в ресторанах. Представителями ресторанов в проекте являются только юридические лица.

В данной папке приложены:
- пользовательский путь (task flow) регистрации ЮЛ в системе
- карта диалогов (dialog flow)
- макеты интерфейса (wireframes)
