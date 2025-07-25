# Анализ рынка видеоигр


## Данные
- **name** — название игры
- **platform** — платформа
- **year_of_release** — год выпуска
- **genre** — жанр игры
- **na_sales** — продажи в Северной Америке (миллионы проданных копий)
- **eu_sales** — продажи в Европе (миллионы проданных копий)
- **jp_sales** — продажи в Японии (миллионы проданных копий)
- **other_sales** — продажи в других странах (миллионы проданных копий)
- **critic_score** — оценка критиков (максимум 100)
- **user_score** — оценка пользователей (максимум 10)
- **rating** — рейтинг от организации ESRB (англ. Entertainment Software Rating Board). Эта ассоциация определяет рейтинг компьютерных игр и присваивает им подходящую возрастную категорию.


## Задача 
**Описание проекта:**
Из открытых источников доступны исторические данные о продажах игр, оценки пользователей и экспертов, жанры и платформы (например, Xbox или PlayStation). Нужно выявить определяющие успешность игры закономерности. Это позволит сделать ставку на потенциально популярный продукт и спланировать рекламные кампании.
Перед вами данные до 2016 года. Представим, что сейчас декабрь 2016 г., и вы планируете кампанию на 2017-й. Нужно отработать принцип работы с данными. Неважно, прогнозируете ли вы продажи на 2017 год по данным 2016-го или же 2027-й — по данным 2026 года.
В наборе данных попадается аббревиатура ESRB (Entertainment Software Rating Board) — это ассоциация, определяющая возрастной рейтинг компьютерных игр. ESRB оценивает игровой контент и присваивает ему подходящую возрастную категорию, например, «Для взрослых», «Для детей младшего возраста» или «Для подростков».

**Цель исследования:** Проанализировать рынок видеоигр. Выделить характерный срок жизни платформы. Выявить перспективные платформы. Определить характерные отличия для пользователей разных регионов. Проверить гипотезы.

**Ход исследования:**
- Подготовка данных: загрузка и изучение общей информации из представленного датасета.
- Предобработка данных: преобразование данных в нужные типы, работа с пропусками и дубликатами, добавление нужных столбцов.
- Исследовательский анализ данных: построение и изучение распределения наиболее популярных платформ, определение потенциально прибыльных платформ, изучение диаграммы рассеяния и корреляции между отзывами и продажами
- Составление портрета пользователя каждого региона: выявление популярных платформ, жанров. Влияения рейтинга ESRB на продажи в отдельном регионе.
- Проверка гипотез: средние пользовательские рейтинги платформ Xbox One и PC одинаковые или нет. Средние пользовательские рейтинги жанров Action (англ. «действие», экшен-игры) и Sports (англ. «спортивные соревнования») разные

**Общий вывод:** резюмирование полученных результатов, формулировка ключевых выводов и рекомендаций.

С помощью данного исследования мы стремимся дать всесторонний анализ ранка видеоигр, что станет отправной точкой для дальнейших исследований и автоматизированных систем прогнозирования.

## Используемые библиотеки
*pandas*, *matplotlib*, *numpy*, *seaborn*, *scipy*