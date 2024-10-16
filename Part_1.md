# Задание 1

### Что такое тестирование ПО?

Процесс в рамках жизненного цикла разработки программного обеспечения, который оценивает качество компонента или системы, а также связанных с ними рабочих продуктов и соответствие их требованиям.
Тестирование программного обеспечения является важной частью процесса разработки программного обеспечения. Это процесс оценки программной системы или приложения с целью выявления дефектов, ошибок или багов, а также проверки соответствия программного обеспечения его заявленным требованиям, степени готовности и корректности его работы. 

### Что такое качество ПО?
**Качество программного обеспечения** – комплекс характеристик программного продукта, определяющих способность выполнять возложенные на него функции.
В настоящий момент этот показатель регулируется международным стандартом ISO/IEC 25010:2011. 

### Когда начинать и заканчивать тестирование?
- **Начинать:** Сразу же, как только это становится возможным и имеет смысл в вашем контексте.
Один из 7 принципов тестирования (Раннее тестирование) гласит:
Чем ранее делается тестирование – тем лучше. 
(сдвигание влево (shift left) относительно SDCL на этапы разработки требований, дизайна, кода)
- **Заканчивать:** Когда с точки зрения бизнеса оно будет уже нецелесообразным.
Другими словами – когда дальнейшее тестирование будет стоить дороже, чем выгоды от него.
тут мы вспоминаем про еще один принцип тестирования:
Исчерпывающее тестирование невозможно.
Критерии окончания тестирования
1. Выполнение всех тестовых сценариев:
Все запланированные тестовые сценарии, включая функциональные, интеграционные, регрессионные, и другие виды тестов, должны быть выполнены.
2. Достигнуты целевые метрики покрытия тестами:
Целевое покрытие тестами, установленное в начале проекта, достигнуто (например, покрытие кода или функционала тестами не ниже 80%).
3. Минимальное количество открытых критичных дефектов:
Все критичные и блокирующие баги устранены.
Оставшиеся дефекты имеют низкий приоритет или незначительное влияние на основные функции системы.
4. Прохождение всех критических тестов:
Все тесты, которые проверяют критические для бизнеса или безопасности функции, успешно пройдены.
5. Соответствие требованиям качества:
Продукт соответствует заданным требованиям качества, включая производительность, стабильность, безопасность и удобство использования.
6. Отсутствие повторяющихся багов:
Повторно не проявляются дефекты, которые уже были ранее исправлены и проверены.
7. Уровень риска приемлем:
Остаточные риски после тестирования считаются допустимыми и не критичными для успешной работы системы.
8. Прохождение пользовательских/приёмочных тестов (UAT):
Продукт успешно прошёл пользовательское тестирование или приёмочные тесты заказчика, и получено одобрение на релиз.
9. Тестовая документация завершена:
Все тестовые отчёты, баг-репорты, матрицы трассировки, чек-листы и другая документация по тестированию завершены и предоставлены заинтересованным сторонам.
10. Выполнение сроков и бюджетов:
Тестирование завершено в пределах установленных сроков и бюджета проекта.
Эти критерии помогают установить контроль над процессом завершения тестирования и снизить риск выпуска некачественного продукта.

### Цели тестирования ПО
- Выявление дефектов до того, как их найдут пользователи, проверка соответствия ПО всем требованиям.
- Оценка рабочих продуктов, таких как требования, пользовательские истории, проекты и код.
- Провоцирование отказов и обнаружение дефектов.
- Обеспечение необходимого покрытия объекта тестирования.
- Снижение уровня риска ненадлежащего качества программного обеспечения.
- Проверка выполнения зафиксированных требований.
- Проверка того, что объект тестирования соответствует контрактным, юридическим и нормативным требованиям.
- Предоставление информации заинтересованным сторонам для принятия обоснованных решений.
- Создание уверенности в качестве объекта тестирования.
- Проверка того, завершен ли объект тестирования и работает ли он так, как ожидают заинтересованные стороны.

### Quality Assurance
**Обеспечение качества** (quality assurance) – Это процесс, который включает в себя проверку, контроль и улучшение качества на всех этапах разработки программного обеспечения. Основная цель — предотвращение возникновения проблем и дефектов, а также обеспечение соответствия продукта требованиям и ожиданиям пользователей.
Методы:Планирование, проектирование и реализация стратегий и процессов QA.
### Quality Control 
**Контроль качества** (Quality Control) – это процесс, направленный на контроль и проверку качества продукта или услуги. В отличие от QA, QC сконцентрирован на конкретном этапе разработки или производства, когда продукт уже находится в конечной стадии или близок к ней. Цель QC состоит в том, чтобы проверить продукт на соответствие установленным стандартам качества и требованиям.
Методы:Тестирование, проверка и контроль качества продукта.
### Тестирование
**Тестирование** (testing) -конкретные действия для проверки качества продукта. 
Основные отличия процессов:
1. Контроль качества и тестирование (как его часть) направлены на продукт, а обеспечение качества на процесс. 
2. Тестирование и контроль качества являются контролирующими мерами, а обеспечение качества - превентивными, или предупреждающими. 
QA — это проактивный процесс, направленный на предотвращение дефектов.
QC — это реактивный процесс, направленный на выявление дефектов.
Тестирование — это конкретная деятельность в рамках QC, ориентированная на проверку функциональности и поиск багов.

### Принципы тестирования
- Тестирование демонстрирует наличие дефектов а не их отсутствие (Testing shows presence of defects)
- Исчерпывающее тестирование недостижимо (Exhaustive testing is not possible)
- Раннее тестирование (Early testing) 
- Тестирование на ранних этапах жизненного цикла разработки программного обеспечения помогает сократить или исключить дорогостоящие изменения. 
- Скопление/кластеризация дефектов (Defect clustering)
В таком случае обычно руководствуются частным случаем закона Паретто: в 20% модулей приложения сокрыто 80% всех дефектов.
- Парадокс пестицида (Pesticide paradox)
Если одни и те же тесты будут выполняться снова и снова, в конечном счете эти тесты больше не будут находить новых дефектов. Для обнаружения новых дефектов может потребоваться изменение существующих тестов и тестовых данных, а также написание новых тестов.
- Тестирование зависит от контекста (Testing is context dependent)
- Тестирование выполняется по-разному в зависимости от контекста. Например, программное обеспечение управления производством, в котором критически важна безопасность, тестируется иначе, чем мобильное приложение электронной коммерции.
- Заблуждение об отсутствии ошибок (Absence of errors fallacy)
Некоторые организации ожидают, что тестировщики смогут выполнить все возможные тесты и найти все возможные дефекты, но принципы 2 и 1, соответственно, говорят нам, что это невозможно.

### Верификация 
**Верификация в тестировании ПО** – процесс просмотра документации, дизайна, кода программы для того, чтобы проверить, было ли программное обеспечение создано в соответствии с требованиями или нет. 
Основная цель процесса верификации – обеспечить качество приложения, дизайна, архитектуры и т.д. Процесс верификации включает в себя статические методы проверки..
### Валидация
**Валидация в разработке ПО** – динамический механизм тестирования и проверки того, действительно ли программный продукт соответствует точным потребностям заказчика или нет. Процесс валидации включает в себя такие действия, как модульное тестирование, интеграционное тестирование, системное тестирование и пользовательское приемочное тестирование.
Ключевая разница:
-Процесс верификации включает в себя проверку документации, дизайна, кода программы, в то время как процесс валидации включает в себя тестирование и проверку самого продукта. -Верификация не требует исполнения кода, в то время как валидация требует.

### Характеристики качества ПО и их атрибуты

Принято выделять 6+2 основных характеристик качества ПО 
- **Функциональность (Functionality)**. 
Определяется способностью ПО решать задачи, которые соответствуют зафиксированным и предполагаемым потребностям пользователя. (Например, способность оплачивать товар несколькими способами и, если эта возможность отсутствует, вы уходите из магазина т.к. нет необходимой функциональности)
  - **Корректность (Correctness)** или Точность (accuracy): Этот атрибут означает, насколько правильно программа выполняет заданные функции. Например, если программе поручено сортировать данные, корректность подразумевает, что она сортирует их правильно.
  - **Полнота (Completeness)**: Полнота означает способность программы предоставлять все функции, заявленные в требованиях. Это означает, что программа не должна иметь недостающих функций.
- **Надежность (Reliability)**. 
Способность ПО выполнять требуемые задачи в обозначенных условиях на протяжении заданного промежутка времени или указанное количество операций. 
  - **Доступность (Availability):** Этот атрибут измеряет время, в течение которого система доступна для использования. Надежная система должна иметь высокую доступность, чтобы минимизировать простои.
  - **Отказоустойчивость (Fault Tolerance):** оценивает способность программы работать надежно, даже если возникают сбои или ошибки. Надежные программы могут продолжать функционировать, даже если произошел сбой.
  - **Устойчивость (Resilience):** Этот атрибут связан с способностью программы восстанавливаться после сбоев и неполадок. Восстановление может включать в себя восстановление данных или переключение на резервные ресурсы.
  - **Предсказуемость (Predictability):** Надежная система должна предсказуемо вести себя в различных ситуациях, что важно для пользователей и операторов системы.
- **Удобство использования(Usability).** 
Степень удобства ПО для пользователей, его наглядность, легкость эксплуатации и изучения.
  - **Понимаемость (Understandability):** Понимаемость оценивает, насколько легко пользователи могут понять, как использовать программу. Простой и понятный интерфейс повышает удобство использования.
  - **Простота обучения (Learnability):** Этот атрибут связан с легкостью освоения программы новыми пользователями. Чем быстрее пользователи могут освоить программу, тем лучше.
  - **Ориентация на пользователя (User-Centered Design):**  Удовлетворение потребностей и ожиданий пользователей является ключевой составляющей удобства использования.
- **Эффективность (Efficiency).** 
Способность ПО обеспечивать требуемый уровень производительности в соответствие с выделенными ресурсами, временем и другими обозначенными условиями.
  - **Эффективность использования ресурсов (Resource Utilization):** Этот атрибут оценивает, насколько эффективно программа использует ресурсы, такие как память, процессорное время и сетевая пропускная способность. Высокая эффективность обеспечивает оптимальное использование ресурсов.
  - **Время отклика (Response Time):** Время отклика измеряет, сколько времени требуется программе для реагирования на запросы пользователя. Снижение времени отклика повышает удовлетворенность пользователей.
  - **Пропускная способность (Throughput):** Пропускная способность определяет, сколько операций программа может обработать за единицу времени. Высокая пропускная способность важна для приложений с большой нагрузкой.
  - **Соответствие стандартам производительности (efficiency compliance)**
- **Удобство сопровождения (Maintainability).** 
Легкость, с которой ПО может изменяться для исправления дефектов, для реализации новых требований, для облегчения дальнейшего обслуживания и адаптации к имеющемуся окружению.
  - **Модульность (Modularity):** Модульность оценивает способность программы быть разбитой на отдельные модули, что облегчает сопровождение и поддержку. Модульные системы позволяют быстрее вносить изменения и устранять ошибки.
  - **Изменяемость (Changeability):** Изменяемость определяет, насколько легко программа может подвергаться изменениям без существенных нарушений работы. Поддерживаемость связана с управлением изменениями в программе.
  - **Документация (Documentation):** Наличие подробной и актуальной документации для пользователей и разработчиков оказывает значительное влияние на поддерживаемость и сопровождаемость программы.
- **Портативность (Portability).** 
Характеризует ПО с точки зрения легкости его переноса из одного окружения (software/ hardware) в другое.
  - **Удобство установки (convenience of installation):** определяет, насколько легко и быстро программа может быть установлена на оборудование с различными характеристиками.
  - **Заменяемость (replaceability):**  относится к способности одной системы заменить другую систему с тем же назначением в том же окружении. Это может включать в себя замену одного или нескольких компонентов программы внутри программной системы.
- **Совместимость (Compatibility).** 
Способность программных компонентов взаимодействовать друг с другом.
  - **Совместимость с платформами (Platform Compatibility):** Этот атрибут оценивает способность программы работать на различных операционных системах и аппаратных платформах. Совместимость важна для программ, предназначенных для разных сред.
  - **Совместимость с другими программами (Software Interoperability):** Этот атрибут оценивает способность ПО взаимодействовать с другими программными продуктами, включая ПО от других производителей.
  - **Совместимость с операционными системами (Operating System Compatibility):** Этот атрибут оценивает способность программы работать на разных версиях операционных систем, что важно для пользователей с разными ОС.
- **Защищенность (Security).**
Способность минимизации угроз, связанных с несанкционированным чтением, изменением информации и т. д. Угрозы могут быть также связаны с некорректным использованием ПО, внешним воздействием со стороны посторонних лиц, выходом из строя технических средств.
  - **Конфиденциальность (Confidentiality):** Этот атрибут оценивает способность программы защищать конфиденциальные данные от несанкционированного доступа. Высокая конфиденциальность важна для систем, которые обрабатывают чувствительные данные.
  - **Целостность (Integrity):**  Способность программы обеспечивать целостность данных и защищать их от несанкционированных изменений. Например, если данные не должны быть подвергнуты изменениям без авторизации, целостность играет важную роль.
  - **Доступность (Availability):** Этот атрибут определяет способность программы оставаться доступной даже при атаках или сбоях. Надежные системы должны быть доступными для пользователей даже в условиях неполадок.
