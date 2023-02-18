Дана информация о сотрудниках некоторой компании. Необходимо распределить премию между сотрудниками по результатм успехов. Для анализа по каждой должности есть свой HR-менеджер, который сравнивает сотрудников друг с другом внутри одной должности.

Необходимо разработать дашборд, который будет решать следующие задачи:
Основная метрика для оценки сотрудников – performance rating (далее рейтинг), он может принимать значения от 1 до 4. 1 — плохая работа, 2 — в рамках ожиданий, 3 — выше ожиданий, 4 — превосходные результаты. По рейтингу вы определяете уровень, какой % от зарплаты будет выдан в качестве дополнительной премии. Если рейтинг сотрудника ниже среднего по его должности, то он получает 5-10%-ную премию от годового дохода, если выше среднего, то 10-20%. Сотрудники с рейтингом 1 не премируются, им предлагается бесплатное корпоративное обучение, которые может помочь им повысить свой перфоманс результат. Для точного определения процентов внутри диапазона используется анализ количества закрытых проектов за рабочий период (projects closed). Сотрудники выполнившие более 15 проектов получают 8-10% при перфоманс рейтинга ниже среднего и 15-20% при выше среднего. Проекты примерно равнозначны среди должностей, поэтому такое сравнение валидно.
Если проектов более 15 и рейтинг выше среднего, то процент уже 15-20%, а если менее 15 и рейтинг выше среднего, то 10-15%. Если проектов более 15 и рейтинг ниже среднего, то процент уже 8-10%, а если менее 15 и рейтинг ниже среднего, то 5-8%.
Финальные значения процентов определяет HR-менеджер индивидуально для каждого сотрудника. Поэтому для принятия решения о премии также во внимание берется самооценка сотрудником удовлетворенности работой, стаж работы и уровень зарплаты. Точно алгоритма определения нет, каждый HR-менеджер принимает решение сам.
Как руководитель, вы хотите понимать общее распределение рейтинга, количество людей с оценками меньше или больше среднего и их уровень заработной платы, чтобы оценить, скольким какая премия достанется. Чтобы в целом оценивать перфоманс сотрудников нужно некоторые овервью по количеству закрытых проектов по департамента и должностям. Ещё вам важно спрогнозировать бюджет на следующий год, поэтому важно посчитать общую сумму премии за текущий период по максимально возможной процентной ставке по правилам выше. Необходимо сделать калькулятор расчета бюджета премий при изменении границ премий в процентах.
Для менеджеров нужна детальная статистика по сотрудникам: их рейтинг, больше он или меньше среднего по должности, количество закрытых проектов, уровень удовлетворенности работой и зарплата. Менеджеры выкачивают детальную таблицу по своей профессии с предлагаемым процентом премии, а потом корректируют её в ручную в экселе и загружают результаты в систему выплат.
Этим дашбордом будут пользоваться руководитель финансового департамента и его подчиненные раз в квартал на компьютерах. Сейчас эта задача решается через аналитиков – они выгружают Эксель с показателями по сотрудникам и дальше фильтруют и ищут людей для премирования. Это занимает много времени и не все сотрудники быстро умеют строить сводные таблицы и графики.

Для визуализации данных разработан интерактивный дашборд (доступен по ссылке https://public.tableau.com/app/profile/sergei.romanov/viz/Lesson_3_project_16714457531340/Dashboard)

![HR analytics dashboard](https://user-images.githubusercontent.com/118465981/219854289-882129ba-9d81-4d66-b94f-d2d1e6444a5e.jpg)
