# Что такое ROS

## Robot Operating System \(ROS\)

Robot Operating System \(ROS\) - это гибкая платформа \(фреймворк\) для разработки программного обеспечения роботов. Это набор разнообразных инструментов, библиотек и определенных правил, целью которых является упрощение задач разработки ПО роботов.

Создание действительно надежного, универсального программного обеспечения для роботов чрезвычайно сложная задача. С точки зрения робота, проблемы, которые кажутся тривиальными для людей, часто требуют очень сложных технических решений. Часто разработка такого решения не под силу одному человеку.

ROS была создана, чтобы стимулировать совместную разработку программного обеспечения робототехники. Каждая отдельная команда может работать над одной конкретной задачей, но использование единой платформы, позволяет всему сообществу получить и использовать результат работы этой команды для своих проектов.

## Платформы \(фреймворки\) в робототехнике

В последнее время, в области робототехники особое внимание уделяется платформам. Понятие платформа обычно резделяют на программную платформу и аппаратную платформу. Программная платформа для роботов включает в себя набор инструментов, которые используются для разработки ПО роботов. Можно выделить типовые, задачи программной платформы: работа с низкоуровневыми устройствами, аппаратная абстракция и коммуникация, навигация, распознавание образов, управление и установка пакетов и зависимостей, подключение библиотек, инструменты для отладки и разработки.

Аппаратные платформы, включают в себя готовые исследовательские и образовательные устройства \(TurtleBot, TurtleBro\). А также готовые промышленные системы.

Важно отметить, что аппаратные платформы совместимы с программными платформами, что позволяет разрабатывать прикладные программы не имея опыта работы с оборудованием и не тратя время на его разработку. Совместимость интерфейсов и методов взаимодействия с оборудование, позволило огромному количеству разработчиков ПО внести свой вклад в развитие робототехники.

Унифицированные интерфейсы и методы работы с устройствами позволяют накапливать и обмениваться готовыми решениями всему сообществу заинтересованных людей в робототехнике.

### Наиболее активные платформы

| MSRDS10 | Microsoft Robotics Developer Studio, Microsoft - U.S. |
| :--- | :--- |
| ERSP11 | Evolution Robotics Software Platform, Evolution Robotics - Europe |
| ROS | Robot Operating System, Open Robotics12 - U.S. |
| OpenRTM | National Institute of Adv. Industrial Science and Technology \(AIST\) - Japan |
| OROCOS | Europe |
| OPRoS | ETRI, KIST, KITECH, Kangwon National University - South Korea |

## Почему стоит начать с ROS

В данный момент для целей изучения и погружения в робототехнику можно однозначно рекомендовать ROS. Важными критериями на этапе погружения в робототехнику, являются: активность сообщества, наличие различных библиотек, расширяемость и простота использования. По этим критериям в данный момент равных ROS нет.

Следует особо отметить, что сообщество ROS чрезвычайно активно. Когда вы сталкиваетесь с проблемой, найти решение и получить помощь становиться проще, не только от разработчика ROS \(компании Open Robotics\), но и от других энтузиастов и профессионалов.

## Что дает готовая платформа

1. **Повторное использование программных модулей**.  Разработанный программный модуль, легко запускается и переиспользуется в любом другом приложении. Вопросы установки зависимостей и других библиотек хорошо проработан и автоматизирован.
2. **Готовый протокол коммуникации**  Основная проблема комплексных робототехнических систем, это решение задач коммуникации в рамках одного приложения. Для решения этих задач ROS содержит все необходимые утилиты. Любой программных модуль может быть представлен как отдельный процесс, взаимодействующий с другими процессами по сетевому протоколу. Такой подход позволяет создавать независимые и простые в повторном использовании программные модули, которые возможно запустить/остановить/модифицировать на любом устройстве.
3. **Развитость средств разработки и отладки**  ROS предоставляет готовые инструменты для отладки, инструмент 2D-визуализации \(rqt\), и инструмент 3D-визуализации \(RViz\), инстумент 3D симуляции \(Gazebo\).  
4. **Активное и открытое сообщество** Сообщества разработчиков робототехники из академического мира и промышленности, были относительно закрытыми до последнего времени. Но сейчас мы видим активное, и главное открытое сотрудничество всех участников. В центре этого изменения -- программная платформа с открытым исходным кодом. В случае ROS существует более 5000 пакетов, которые были разработаны и выложены в общий доступ. Описание этих пакетов, инструкций и другой полезной информации -- превышает 18 000 Wiki страниц.  
5. **Собственная экосистема** Вокруг ROS сформирована собственная экосистема \(по аналогии с платформами Android и Apple\). В ней существуют разработчики аппаратных платформ, разработчики программных модулей, энтузиасты и компании производители промышленного оборудования, единое место распространения и хранения готовых модулей, тысячи станиц документации. Все участники взаимодействуют и работают в рамках единой платформы.

## Что такое ROS

{% hint style="info" %}
_ROS \(Robot Operating System\) обеспечивает разработчиков библиотеками и инструментами для создания приложений робототехники. ROS обеспечивает аппаратную абстракцию, предлагает драйверы устройств, библиотеки, визуализаторы, обмен сообщениями, менеджеры пакетов и многое другое. ROS выпускается в соответствии с условиями BSD лицензии и с открытым исходным кодом._

[www.ros.org](http://www.ros.org)
{% endhint %}

Аббревиатура ОС, обычно обозначает Операционная Система общего назначения \(linux, windows, iOS\). Можно ли при этом называть ROS операционной системой для роботов? Это не совсем верно. Более точно описать ROS можно определением мета-операционная система.

Мета-операционная система не похожа на обычную операционная систему, такие как Windows, Linux и Android. ROS работает "поверх" существующей операционной системы. Для работы ROS необходима базовая операционная система Linux \(например дистрибутив Ubuntu\). После завершения установки ROS на OC Linux можно использовать функции, предоставляемые обычной операционной системой. В дополнение к основным функциям, предоставляемым Linux, ROS обеспечивает дополнительный функционал, необходимый для роботов. Например: работа с библиотеками, передача / прием данных для разных устройств, планирование и обработка ошибок. Этот тип программного обеспечения также называется промежуточным программным обеспечением \(middleware \) или программным фреймворком.

