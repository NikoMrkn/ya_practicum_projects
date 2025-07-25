# HR. Предсказание уровня удовлетворенности сотрудника и предсказание уволится ли сотрудник или нет


## Данные
- **id** — уникальный идентификатор сотрудника;
- **dept** — отдел, в котором работает сотрудник;
- **level** — уровень занимаемой должности;
- **workload** — уровень загруженности сотрудника;
- **employment_years** — длительность работы в компании (в годах);
- **last_year_promo** — показывает, было ли повышение за последний год;
- **last_year_violations** — показывает, нарушал ли сотрудник трудовой договор за последний год;
- **supervisor_evaluation** — оценка качества работы сотрудника, которую дал руководитель;
- **salary** — ежемесячная зарплата сотрудника;
- **job_satisfaction_rate** — уровень удовлетворённости сотрудника работой в компании, целевой признак.


## Задача 
**Описание проекта:** Компания предоставила данные с характеристиками сотрудников компании. Среди них — уровень удовлетворённости сотрудника работой в компании. Эту информацию получили из форм обратной связи: сотрудники заполняют тест-опросник, и по его результатам рассчитывается доля их удовлетворённости от 0 до 1, где 0 — совершенно неудовлетворён, 1 — полностью удовлетворён.  
Имеется несколько задач: 
- Первая — построить модель, которая сможет предсказать уровень удовлетворённости сотрудника на основе данных заказчика. 
Почему бизнесу это важно: удовлетворённость работой напрямую влияет на отток сотрудников. А предсказание оттока — одна из важнейших задач HR-аналитиков. Внезапные увольнения несут в себе риски для компании, особенно если уходит важный сотрудник.
- Вторая задача — построить модель, которая сможет на основе данных заказчика предсказать то, что сотрудник уволится из компании.

**Цель исследования:** Провести анализ сотрудников в компании «Работа с заботой». Обучить и выбрать лучшие модели для задач регресиии и классификации.

**Ход исследования:**
- загрузка и предобработка данных: загрузка и первоначальный осмотр датасетов. преобразование датафреймов по необходимости
- исследовательский анализ данных
- подготовка данных с помощью пайплайна и обучение моделей:
    - для регрессии: LinearRegression, SVR, RandomForestRegressor, DecisionTreeRegressor
    - для классификации: SVC, KneighborsClassifier, RandomForestClassifier
- анализ важности признаков для лучших моделей
- вывод и рекомендации заказчику

**Общий вывод:** резюмирование полученных результатов, формулировка ключевых выводов и рекомендаций.

## Используемые библиотеки
*pandas*, *seaborn*, *numpy*, *scikit-learn*, *shap*, *optuna*