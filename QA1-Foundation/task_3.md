# 1.

### 1. Waterfall (Каскадная модель)
Линейная модель: анализ - дизайн - разработка - тестирование - внедрение. Без возврата к предыдущим этапам.

**Плюсы:**
- **Четкая структура и контроль**. Каждый этап (анализ, проектирование, разработка, тестирование, внедрение) завершается полностью перед переходом к следующему. Это обеспечивает строгий контроль и понятный прогресс.
- **Точная оценка сроков и бюджета**. Так как требования фиксируются в самом начале, проще спрогнозировать затраты и сроки реализации.
- **Хорошая документация**. На каждом этапе создаются подробные спецификации, что полезно для долгосрочной поддержки продукта.
- **Подходит для проектов с жесткими требованиями**. Идеален для областей, где изменения маловероятны (например, медицинское ПО, банковские системы).

**Минусы:**
- **Отсутствие гибкости**. Любые изменения требований в процессе разработки требуют дорогостоящих переделок и могут сорвать сроки.
- **Позднее тестирование**. Ошибки обнаруживаются только на финальных этапах, что делает их исправление сложным и затратным.
- **Риск устаревания продукта**.
Длительный цикл разработки может привести к тому, что выпущенный продукт уже не будет соответствовать текущим потребностям рынка.
- **Нет промежуточных результатов**. Клиент видит готовый продукт только в самом конце, что увеличивает риски несоответствия ожиданиям.

### 2. V-Model
Улучшенный Waterfall: каждому этапу разработки соответствует свой уровень тестирования (например, юнит-тесты для кода, системные тесты для архитектуры).

**Плюсы:**
- **Раннее тестирование**. Каждому этапу разработки соответствует свой уровень тестирования, что позволяет находить дефекты на ранних стадиях.
- **Снижение количества критических ошибок**. Благодаря параллельному тестированию, финальный продукт получается более надежным.
- **Четкая структура**. Как и в Waterfall, процесс предсказуем и хорошо документирован.
- **Подходит для высоконадежных систем**. Используется в областях, где важна безопасность (авиация, медицина, финансы).

**Минусы:**
- **Еще менее гибкая, чем Waterfall**. Внесение изменений после начала разработки крайне затруднено.
- **Высокие затраты на документацию**. Требуется детальная проработка спецификаций на всех этапах.
- **Длительный цикл разработки**. Как и Waterfall, не подходит для проектов, где требования могут меняться.

### 3. Incremental Model
Продукт создается частями (версиями). Каждая новая версия добавляет функционал к предыдущей.

**Плюсы:**
- **Ранний выпуск продукта**. Первая рабочая версия появляется быстро, что позволяет начать использование или тестирование.
- **Гибкость**. Можно корректировать следующие версии на основе обратной связи.
- **Снижение рисков**. Ошибки в одной части системы не блокируют весь проект.
- **Постепенная интеграция функций**. Позволяет равномерно распределять нагрузку на команду.

**Минусы:**
- **Сложность интеграции**. Новые модули могут конфликтовать с уже разработанными.
- **Требуется продуманная архитектура**. Без четкого планирования система может стать несогласованной.
- **Возможна избыточная функциональность**. Есть риск разрабатывать ненужные компоненты, если требования нечеткие.

### 4. Scrum
Работа ведется короткими итерациями (спринтами 2-4 недели). Каждый спринт — готовый кусок продукта. Ежедневные стендапы, планирование и ретроспективы.

**Плюсы:**
- **Гибкость и адаптивность**. Требования можно пересматривать в каждом спринте (2-4 недели).
- **Быстрая обратная связь**. Клиент регулярно видит рабочие версии продукта.
- **Улучшенная мотивация команды**. Самоорганизация и четкие цели повышают вовлеченность.
- **Раннее выявление проблем**. Регулярные ретроспективы помогают оперативно улучшать процесс.

**Минусы:**
- **Требует высокой дисциплины**. Без соблюдения правил процесс быстро теряет эффективность.
- **Сложность оценки общих сроков**. Гибкость может привести к затягиванию проекта.
- **Зависимость от Scrum Master**. Плохой координатор может разрушить процесс.
- **Не подходит для всех проектов**. Сложно применять в областях с жесткими требованиями (например, регулируемые отрасли).

### 5. Kanban
Гибкий поток задач. Работа визуализируется на доске (столбцы: "To Do", "In Progress", "Done"). Новые задачи добавляются по мере возможностей команды.

**Плюсы:**
- **Максимальная гибкость**. Задачи можно добавлять и менять в любой момент.
- **Прозрачность**. Доска Kanban дает наглядное представление о статусе работ.
- **Отсутствие жестких сроков**. Позволяет сосредоточиться на качестве, а не на скорости.
- **Подходит для поддержки и доработок**. Идеален для команд, работающих с текущими задачами.

**Минусы:**
- **Риск перегрузки**. Если не ограничивать количество задач в работе, команда может потерять эффективность.
- **Сложность планирования релизов**. Отсутствие временных рамок затрудняет прогнозирование.
- **Требует самодисциплины**. Без контроля может возникнуть хаос и прокрастинация.

# 2.

### 4 основные идеи «Agile-манифест»
- **Люди и взаимодействие важнее процессов и инструментов** - живое общение и доверие к людям лучше строгих правил и программ.
- **Работающий продукт важнее исчерпывающей документации** - перспективный и хорошо работающий продукт лучше удовлетворяющей требованиям законченная документация.
- **Сотрудничество с заказчиком важнее согласования условий контракта** - гибкость в переговорах ценнее жёсткого контракта.
- **Готовность к изменениям важнее следования первоначальному плану** - меняться под различные обстоятельства, которые могут привести к лучшему итогу лучше, чем слепо идти по изначальному плану.

### То есть не отрицая важности того, что справа, мы всё-таки больше ценим то, что слева
То есть главный приоритет это не только самые важные вещи, к примеру люди, продукт, сотрудничество, гибкость, но и более уходящие на второй план: процессы, документация, контракты, планы они тоже нужны и их не стоит ставить во главу угла.