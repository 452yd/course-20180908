## Управление рисками при разработке ПО

[Источник](http://citforum.ru/SE/project/arkhipenkov_lectures/10.shtml)

### Основные риски разработки ПО

* Требования заказчика отсутствуют/не полны/подвержены частым изменениям.
* Отсутствие необходимых ресурсов и опыта.
* Отсутствие рабочего взаимодействия с заказчиком.
* Неполнота планирования. «Забытые работы».
* Ошибки в оценках трудоемкостей и сроков работ.

# Методы реагирования на риски

1. ﻿Уклонение от риска предполагает изменение плана управления проектом таким образом, чтобы исключить угрозу, вызванную негативным риском, оградить цели проекта от последствий риска или ослабить цели, находящиеся под угрозой (например, уменьшить содержание проекта). Некоторые риски, возникающие на ранних стадиях проекта, можно избежать при помощи уточнения требований, получения дополнительной информации или проведения экспертизы. Например, уклониться от риска можно, если отказаться от реализации рискованного функционального требования или самостоятельно разработать необходимый программный компонент, вместо ожидания поставок продукта от субподрядчика.
2. ﻿Передача риска подразумевает переложение негативных последствий угрозы с ответственностью за реагирование на риск на третью сторону. Передача риска просто переносит ответственность за его управление другой стороне, но риск при этом никуда не девается. Передача риска практически всегда предполагает выплату премии за риск стороне, принимающей на себя риск. Например, заказ на стороне разработки рискованного компонента по фиксированной цене. В IT часто приходится формулировать риски в виде допущений, тем самым передавая его заказчику. Например, оценивая проект внедрения, мы можем записать допущение о том, что производитель не изменит стоимость лицензий на базовое ПО.
3. ﻿Снижение рисков предполагает понижение вероятности и/или последствий негативного рискованного события до приемлемых пределов. Принятие предупредительных мер по снижению вероятности наступления риска или его последствий часто оказываются более эффективными, нежели усилия по устранению негативных последствий, предпринимаемые после наступления события риска. Например, раннее разрешение архитектурных рисков снижает потери при досрочном закрытии проекта. Или регулярная ревизия поставок заказчиком может снизить вероятность риска его неудовлетворенности конечным результатом. Если в проектной команде высока вероятность увольнения сотрудников, то введение на начальной стадии в проект дополнительных (избыточных) людских ресурсов снижает потери при увольнении членов команды, поскольку не будет затрат на «въезд» в проектный контекст новых участников.
4. ﻿Принятие риска означает, что команда проекта осознанно приняла  решение не изменять план управления проектом в связи с риском или не  нашла подходящей стратегии реагирования. Мы вынуждены принимать все  «неизвестные риски». 
   Принятие это то, что всегда происходит, когда мы вообще не  управляем рисками. Если же мы управляем рисками, то мы можем страховать  риски, закладывая резерв в оценки срока завершения и/или трудозатрат.  Проактивное отношение к принятым рискам может состоять в разработке план  реагирования на риски. Этот план может быть введен в действие только  при заранее определенных условиях, если есть уверенность и достаточное  количество признаков того, что данный план будет успешно выполнен.

﻿Важно помнить о вторичных рисках (Secondary Risks), возникающих в результате применения реагирования на риски, которые тоже должны быть идентифицированы, проанализированы и при необходимости включены в список управляемых рисков.

### Риски учёта требований

﻿К часто упускаемым требованиям можно отнести: 

* Функциональные
* Программы установки, настройки, конфигурации.
* Миграция данных.
* Интерфейсы с внешними системами.
* Справочная система.
* Общесистемные
* Производительность.
* Надежность.
* Открытость.
* Масштабируемость.
* Безопасность.
* Кросплатформенность.
* Эргономичность.

﻿Если вероятность изменений требований проекта высока, то возможны следующие подходы для реагирования на данный риск: 

* Переоценка проекта каждый раз, когда требования добавляются / изменяются (уклонение).
* Итерационная разработка. Контракт с компенсацией затрат на основе «Time & Materials» (передача риска Заказчику).
* Учет в оценках трудоемкости и сроков возможности роста требований, например, на 50% (резервирование риска).

### Риски планирования

﻿При планировании работ по проекту часто «забывают»: 

* Обучение.
* Координация работ.
* Уточнение требований.
* Управление конфигурациями.
* Разработка и поддержка скриптов автосборки.
* Разработка тестов.
* Создание тестовых данных.
* Обработка запросов на изменения.

### Риски управления ресурсами

В силу особенностей вовлечения сотрудников в деятельность компании, их задействование в рамках проекта часто оказывается неполной. Распространёнными причинами этого являются:

* Сопровождение действующих систем.
* Повышение квалификации.
* Участие в подготовке технико-коммерческих предложений.
* Участие в презентациях.
* Административная работа.
* Отпуска, праздники, больничные.

### Литература

* Том ДеМарко, Тимоти Листер, «Вальсируя с Медведями. Управление рисками в проектах по разработке программного обеспечения», М., Компания p.m.Office, 2005.
* «Microsoft Solutions Framework. Дисциплина управления рисками MSF», вер. 1.1, 2002
* «PMBOK. Руководство к Своду знаний по управлению проектами», 3-е изд., PMI, 2004.
* С.Макконнелл, «Сколько стоит программный проект», «Питер», 2007.
* Ньюэл М.В., «Управление проектами для профессионалов. Руководство по подготовке к сдаче сертификационного экзамена PMP», КУДИЦ-Образ, 2006.
