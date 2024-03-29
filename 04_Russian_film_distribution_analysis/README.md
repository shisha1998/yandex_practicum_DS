#  Исследование рынка российского кинопроката


## Данные

В наличии были следующие данные с сервиса Кинопоиск:
- название фильма;
- номер прокатного удостоверения;
- дата премьеры фильма;
- тип фильма;
- студия-производитель;
- страна-производитель;
- режиссёр;
- продюсер;
- возрастная категория;
- объём возвратных средств государственной поддержки;
- объём невозвратных средств государственной поддержки;
- источник государственного финансирования;
- общий бюджет фильма;
- рейтинг фильма на КиноПоиске;
- жанр фильма.
- сборы в рублях.

## Задача

Нужно изучить рынок российского кинопроката и выявить текущие тренды, а также сделать анализ насколько фильмы, которые получили государственную поддержку, интересны зрителю. 

## Используемые библиотеки
*pandas*

## Итоги исследования

- Наибольшее количество фильмов, выпущенных при финансовой поддержке государства, выщло в прока в 2015 году, наименьшее - в 2013. До 2013 года государство поддерку не оказывало.

- Доля поддержки по годам примерно одинаковая и колеблется в районе 50% от суммы бюджета фильма. Наибольшая суммарная поддержка оказана в 2019 году, тогда же фильмы имели наибольший суммарный бюджет. Наименьшая поддержка оказана в 2010 году, тогда же фильмф имели наименьший суммарный бюджет.

- Чем больше поддержка государства, тем больше бюджет фильмов.

- Наибольшая поддержка оказывается художественным фильмам, наименьшая - документальным.

- Больше всего поддржки государство оказывает студии ООО"Нон-Стоп Продакшн", при этом наибольшие кассовые сборы обеспечивает студия ООО"Студия "ТРИТЭ" Никиты Михалкова", при этом она же получает больше прибыли после возврата возмещаемой части поддержки. Получают поддержку, но не могут ее возместить из-за отсутствия кассовых сборов ООО"Арт Пикчерс Студия" и ООО"Водород 2011".

- Больше всего денег государство выделяет на съемки фильмов категории 12+, меньше всего на фильмы 0+.

- Чаще всего фильмы финансирует Фонд кино, реже - Министерство культуры. Совместное финансирование Министерства культуры и Фонда кино получают меньше всего фильмов.

- Финасируемые государством фильмы чаще всего имеют рейтинг 5,8 - 6,6.

- Зависимости между объемом финансовой поддержки и величиной кассовых сборов не наблюдается.

- Чаще всего оказывают поддержку фильмам в жанрах драма, комедия и мультфильмам.