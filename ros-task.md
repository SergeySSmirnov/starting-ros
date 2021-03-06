# Назначение ROS

Целью создания ROS является создание "**среды разработки, которая позволяет разработчикам ПО для роботов сотрудничать на глобальном уровне**»

ROS сосредоточена на максимизации повторного использования кода при разработке. Основные характеристики позволяющие это реализовать:

**Распределенный процессы**: Структура ROS создана в виде минимальных единиц исполняемых процессов \(нод\), и каждый процесс выполняется изолированно. Взаимодействие разных нод происходит только на уровне обмена сообщениями.

**Управление пакетами**. Несколько процессов, имеющих общую задачу объединяются в пакет. Управление пакетами подразумевает набор утилит, позволяющие автоматический скачивать, устанавливать и удалять пакета. Пакетный менеджер гарантирует работоспособность и целостность установленные пакетов.

**Публичные репозитории и документация**: Каждый доступный пакет публикуется в публичном репозитории. Документация пакетов, публикуется в единой системе, которая упрощает поиск необходимых пакетов.

**Единое API**: При разработке программы, использующей ROS, вы получаете простое и легко встраиваемое API. В примерах программ вы увидите, что использование API не сильно отличается от языка \(C ++ или Python\). При этом нет разницы при использовании API на каком языке была написана программа.

**Поддержка различных языков программирования**: программа ROS предоставляет клиентскую библиотеки для поддержки различных языков программирования. Наиболее популярны Python, C ++, а также такие языки, как Lisp, JAVA, C \#, Lua и Ruby.

