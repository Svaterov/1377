# 1377
Информационная архитектура (ИА) – это инструмент проектирования пользовательского опыта 
для решения поставленных перед проектом задач. 
Однако, информационная архитектура не подразумевает работу со структурой продукта. ИА определяется несколькими принципами:
1. Как контент будет организован?
2. Как контент будет идентифицирован (маркирован)?
3. Какую информацию ожидают найти пользователи, в каких объемах?
4. Какие ожидания пользователя касательно процесса навигации по сайту?
5. В каком виде пользователи ожидают получить искомую информацию? Как они будут взаимодействовать с ней?В титульном блоке будут расположены месседж 
компании и перечень основных услуг, а также «Целевое действие». На этой странице будет ссылка «Подключиться к сервису», на которой можно будет перейти к оформлению заявки (рис. 6).
На создание такой схемы было потрачено совсем 
немного времени. Однако, ее преимущество состоит в том, что команда сохранит драгоценное время 
на этапе проектирования и кодинга.
Первый – принцип раскрытия. Даже если 
информации очень много, разработчик оставит 
на странице ровно столько данных, сколько потребуется пользователю для осмысленного и быстрого 
выбора. Остальную информацию он сгруппирует 
на подстраницах и подкатегориях. 
Второй принцип – принцип примеров. Примеры заранее дают пользователю понять, что скрывается за категорией, пунктом, меню или кнопкой.
Третий принцип – принцип парадного входа. В последнее время значительно уменьшилось 
значение главной страницы. Это происходит потому, 
что поисковые системы сразу же переносят пользователя на релевантные поисковому запросу внутренние страницы. Пользователь должен понимать, куда 
он попал, и что может полезного извлечь из представленной информации.
Последний принцип – принцип множественной классификации. Можно найти необходимую информацию на сайте через поиск, список, 
или по определенным категориям. Все это возможно 
потому, что сейчас ОС придерживаются принципа 
множественной классификации. То есть, предоставляют возможность находить информацию несколькими способами.Первой (наиболее очевидной) моделью ИА является иерархическая древовидная модель. 
В данной модели информация распределена по категориям на разных уровнях сверху вниз. Пользователи 
сначала попадают на верхние уровни сайта, а далее, 
согласно собственным потребностям, углубляются 
в определенные категории контента. Этот тип подходит в качестве стандартной модели для больших 
по объему веб-сайтах.Плоская модель ИА состоит из линейно организованных списков, между которыми пользователь может перемещаться от категории к категории, затем – к 
подкатегориям и отдельным единицам контента.
Такая модель отлично подходит для экранов мобильных телефонов, помогая пользователю сфокусироваться на контенте, но затрудняя переходы между 
страницами.Модель hub-and-spoke («ромашка») основана 
на концепции центрального экрана, который служит 
отправной точкой для остальных. Каждая из страниц 
отделена от других и исключает возможность перехода на другие страницы, минуя стартовую. 
Данная модель идеально подходит для вебинтерфейсов, основанных на задачах (task-based), 
экономит место и устраняет необходимость глобальной навигации на каждом экране.Модель многомерной иерархии – это модель ИА, в которой вся краткая информация о ресурсе собрана на главном экране-дашборде. Пользователь всегда может перейти на следующую страницу 
для получения более детальной информации. В такой 
модели ИА представлено большое количество различных элементов навигации, и каждая страница доступна к переходу.Такая модель подходит для интерфейсов с большим количеством динамической информации и различными типами взаимодействия с пользователем. 
При проектировании интерфейса, в котором пользователю необходим доступ к различной агрегированной информации, такая модель приносит больше 
всего пользы.Существует несколько способов разделить контент по категориям, а категории – по приоритетам. 
Для этого можно использовать различные инструменты. В конце концов, ИА можно создать, используя 
обычный текстовый редактор Microsoft Word. 
Модель ИА – это не что иное, как структурированный план (рис. 22).
Зачастую маленькие веб-сайты не нуждаются 
ни в каких дополнительных функциях. Для разработки ИА малостраничных сайтов можно использовать 
обычный текстовый редактор.
Разрабатывая массивную ИА, в которой необходимо демонстрировать взаимосвязи между отдельными элементами, функционала текстового редактора 
может быть недостаточно. В таких случаях лучше использовать инструменты, с обширным функционалом 
для визуализации.
Самый быстрый способ проверить разработанный драфт – тестирование древовидным методом 
Tree testing. Тест помогает определить наличие критических ошибок в модели ИА. Суть теста состоит 
в анкетировании фокус-группы во время сортировки 
карточек. Отличие такого тестирования от юзабилити-тестирования в том, что пользователь не видит интерфейс, а видит только ИА, представленную в виде 
карточек. Как проходит тестирование:
1. Создаются индексные карты для каждого уровня 
категорий. Этот этап называется «Tree» (дерево).
2. Топ-категории составляют основные ветви дерева, а подкатегории – сучки и более мелкие ветви.
Например, первая индексная карта будет содержать следующие категории: одежда, электроника, бижутерия, музыка, спорт, игрушки, ювелирные украшения. Далее создаются подкатегории 
для каждой из этих топ-категорий, а также подкатегории для подкатегорий. Категория одежды может содержать подкатегории: мужская, женская, 
для мальчиков, для девочек, унисекс. 
3. Участникам тестирования дается задание: найти какой-либо товар. При этом участники видят 
только топ-категории и выстраивают сценарий 
действий с помощью карточек. 
Например, нужно найти новый пояс с пряжкой 
для мальчика 9 лет. Задача участника – использовать карточки в процессе поиска товара. ТаРисунок 23
ким образом участники проходят все категории 
и подкатегории (рис. 23).
4. Если искомый предмет не найден, можно вернуться 
на несколько уровней назад. Если выполнить задачу совсем не получается, либо же предмет найден, 
участник может приступить к следующему заданию.
5. Все сценарии поведения участников фиксируются, 
а также попутно они отвечают на ряд вопросов.
Прежде чем перейти к сортировке контента, стоит ответить на несколько вопросов: 
1. Кто будет создавать контент? Разработчик, клиент или третья сторона (копирайтер)?
2. Кто будет управлять контентом, упорядочивать 
его и обновлять? 
3. Какой контент представлен на сайтах конкурентов?
4. Будет ли контент ценным или полезным для пользователей?
5. Как пользователи смогут найти контент?
6. Какой контент будет представлен на сайте? 
7. Как визуально отображать виды контента? 
Как интегрируется каждый вид в ИА?
8. Как контент будет отображаться на разных 
устройствах?
Ответы на вышеперечисленные вопросы значительно упростят процесс разработки контент-стратегии и ИА веб-ресурса, а также помогут избежать 
трудностей на следующих этапах разработки. 
Понимание того, как создается контент и как им 
управлять, напрямую влияет на ИА, навигацию и выбор платформы для реализации веб-проекта. 
Как правило, посещая веб-сайт, пользователь 
знает, что ищет. У пользователя уже сформирована ментальная модель (pre-existing mental model) 
того, как сайт работает, как организован контент, 
как он маркирован, какая построена навигация и названы страницы.
Хорошая маркировка контента – это выбор подходящих меток (labels). Что входит в понятие подходящих меток:
1. Подбор понятных, емких слов и фраз.
Важна простота в высказываниях, точность и ясность мысли. Когда метки расплывчаты, пользователь 
будет нажимать ссылки и никогда не найдет то, за чем 
пришел. 
2. Приоритетными должны быть часто используемые слова.Также стоит избегать ситуаций, когда категории 
пересекаются. Например, категории «Solutions» (Решения) и «Support» (Поддержка) имеют одинаковую 
смысловую нагрузку, соответственно, пользователь 
может растеряться, увидев две разные категории с 
одинаковым смыслом. 
Первичная навигация – это навигация такого 
контента, в котором пользователь наиболее заинтересован. Это наиболее важные элементы для тех, кто 
посещает сайт.Первичная навигация–этото, чтопроизводится, продается и предоставляется через сервисы сайта.\
MVP


















[maxresdefault](https://github.com/user-attachments/assets/fb9f46da-fa0a-45c2-b5dc-9fb448e120ae)
()
