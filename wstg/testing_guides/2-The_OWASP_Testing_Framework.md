Фаза 1 перед началом разработки
Этап 1.1 Определение SDLC
Перед началом разработки приложения необходимо определить соответствующий SDLC, обеспечивающий безопасность на каждом этапе.

Этап 1.2 Обзор политик и стандартов
Убедитесь, что существуют соответствующие политики, стандарты и документация. Документация чрезвычайно важна, поскольку она дает командам разработчиков руководящие принципы и политики, которым они могут следовать. Люди могут поступать правильно, только если они знают, что правильно.

Если приложение должно быть разработано на Java, важно, чтобы существовал стандарт безопасного кодирования Java. Если приложение должно использовать криптографию, важно наличие стандарта криптографии. Никакие политики или стандарты не могут охватить все ситуации, с которыми столкнется команда разработчиков. За счет документирования общих и предсказуемых проблем в процессе разработки будет приниматься меньше решений.

Этап 1.3 Разработка критериев измерения и показателей и обеспечение прослеживаемости
Перед началом разработки спланируйте программу измерений. Определяя критерии, которые необходимо измерить, он обеспечивает видимость дефектов как в процессе, так и в продукте. Важно определить метрики до начала разработки, так как может потребоваться изменить процесс для сбора данных.

Фаза 2 во время определения и проектирования
Этап 2.1 Проверка требований безопасности
Требования безопасности определяют, как приложение работает с точки зрения безопасности. Очень важно проверить требования безопасности. Тестирование в этом случае означает тестирование предположений, сделанных в требованиях, и тестирование, чтобы увидеть, есть ли пробелы в определениях требований.

Например, если существует требование безопасности, которое гласит, что пользователи должны быть зарегистрированы, прежде чем они смогут получить доступ к разделу технических документов веб-сайта, означает ли это, что пользователь должен быть зарегистрирован в системе или он должен быть аутентифицирован? Убедитесь, что требования максимально однозначны.

При поиске пробелов в требованиях обратите внимание на такие механизмы безопасности, как:

Управление пользователями
Аутентификация
Авторизация
Конфиденциальность данных
Честность
Подотчетность
Управление сессией
Транспортная безопасность
Разделение многоуровневой системы
Соответствие законодательству и стандартам (включая стандарты конфиденциальности, государственные и отраслевые стандарты)
Этап 2.2 Обзор дизайна и архитектуры
Приложения должны иметь документированный дизайн и архитектуру. Эта документация может включать модели, текстовые документы и другие подобные артефакты. Эти артефакты необходимо протестировать, чтобы убедиться, что дизайн и архитектура обеспечивают соответствующий уровень безопасности, как определено в требованиях.

Выявление недостатков безопасности на этапе проектирования - это не только одно из самых экономичных способов выявления недостатков, но и одно из наиболее эффективных мест для внесения изменений. Например, если определено, что проект требует принятия решений об авторизации в нескольких местах, может быть целесообразно рассмотреть центральный компонент авторизации. Если приложение выполняет проверку данных в нескольких местах, может оказаться целесообразным разработать центральную структуру проверки (т. Е. Фиксация проверки ввода в одном месте, а не в сотнях мест, намного дешевле).

Если обнаруживаются слабые места, их следует передать системному архитектору для альтернативных подходов.

Этап 2.3 Создание и просмотр моделей UML
После завершения проектирования и архитектуры создайте модели Unified Modeling Language (UML), описывающие, как работает приложение. В некоторых случаях они уже могут быть доступны. Используйте эти модели, чтобы подтвердить у разработчиков систем точное понимание того, как работает приложение. Если обнаруживаются слабые места, их следует передать системному архитектору для альтернативных подходов.

Этап 2.4 Создание и просмотр моделей угроз
Вооружившись обзорами дизайна и архитектуры, а также моделями UML, объясняющими, как именно работает система, выполните упражнение по моделированию угроз. Разработайте реалистичные сценарии угроз. Проанализируйте дизайн и архитектуру, чтобы убедиться, что эти угрозы устранены, приняты бизнесом или переданы третьей стороне, например страховой фирме. Если у выявленных угроз нет стратегий смягчения, пересмотрите дизайн и архитектуру вместе с системным архитектором, чтобы изменить дизайн.