# ml-system-design-2024-spbsu

Курс читал [@noxoomo](https://github.com/noxoomo)

Лекция 0 --- вводная лекция:

- разница между ML System Design и MLOps
- специалисты, участвующие в разработке и реализации ML-системы

Лекция 1 --- обзор ML-системы:

- вопрос о необходимости ML-системы
- критерии качества ML-системы
- жизненный цикл ML-системы

Лекция 2 --- Data Engineering:

- устройства для хранения данных
- виды данных и выбор хранилища
- "тиры" хранящихся данных
- нормализация данных, эволюция схемы
- OLTP vs OLAP
- Single vs Multitenant

Лекция 3 --- Crowdsourcing Management:

- crowdsourcing как способ получения данных для обучения с учителем
- этапы crowdsourcing
- контроль стоимости и задержки
- достаточное количество данных
- смещения в данных, авторазметка

Лекция 4 --- Model Development:

- процесс разработки модели
- баланс между качеством и деньгами
- пример с обучением на нескольких таблицах
- невероятностное сэмплирование
- feature engineering для структурированных и неструктурированных данных
- утечки данных
- проведение экспериментов
- model training guidelines

Лекция 5 --- Model Training & Evaluation:

- задержка на чтении данных и логике обучения, ускорение моделеи
- устройство видеокарты, overhead на выполнение операций
- распределенное обучение
- оценка качества, иерархия метрик качества

Лекция 6 --- Model Deployment & Serving:

- способы раскатки модели, стадии раскатки
- сложности и задачи раскатки
- cloud vs edge computing
- способы взаимодействия с моделью
- балансировка, контейнеризация
- стратегии раскатки
- мониторинг

Лекция 7 --- Optimization:

- способы сжатия модели
- оптимизация для конечных устройств

Лекция 8 --- Model Monitoring & Maintenance:

- анализ качества и эффективности модели
- выбор метрик для мониторинга и их анализ
- операционные ошибки и ошибки машинного обучения
- виды ошибок машинного обучения, сдвиги в распределении
- ранжирование показателей мониторинга по простоте отслеживания и информативности
- способы расчета метрик
- встраивание мониторинга на примере Amazon Alexa

Лекция 9 --- Continual Learning:

- способы и виды обновления модели
- шаги непрерывного обучения
- способы тестирования при непрерывном обучении

Лекция 10 --- ML System Design Interview Framework:

- шаги собеседования по ML System Design
- основные пункты для каждого шага собеседования
- пример рассуждения на собеседовании
