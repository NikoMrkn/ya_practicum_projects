**Модель предсказания оттока клиентов телекоммуникационной компании**


## Данные
- contract_new.csv
    - customerID
    - BeginDate
    - EndDate
    - Type
    - PaperlessBilling
    - PaymentMethod
    - MonthlyCharges
    - TotalCharges

- personal_new.csv
    - customerID
    - gender
    - SeniorCitizen
    - Partner
    - Dependents

- internet_new.csv
    - customerID
    - InternetService
    - OnlineSecurity
    - OnlineBackup
    - DeviceProtection
    - TechSupport
    - StreamingTV
    - StreamingMovies

- phone_new.csv
    - customerID
    - MultipleLines


**Описание проекта:** Оператор связи «ТелеДом» хочет бороться с оттоком клиентов. Для этого его сотрудники начнут предлагать промокоды и специальные условия всем, кто планирует отказаться от услуг связи. Чтобы заранее находить таких пользователей, «ТелеДому» нужна модель, которая будет предсказывать, разорвёт ли абонент договор. Команда оператора собрала персональные данные о некоторых клиентах, информацию об их тарифах и услугах.

**Задача:** Анализ и обработка датасетов. Обучение моделей бинарной классификации и выявление лучшей.

**Ход проекта:**
- загрузка и предоработка данных
- исследовательский анализ датафреймов
- объединеине датафреймов, более подробный анализ данных
- подготовка данных
- обучение моделей
- тестирование и анализ лучшей модели


## Используемые библиотеки
*pandas*, *seaborn*, *matplotlib*, *numpy*, *phik*, *shap*, *scikit-learn*, *optuna*, *catboost*, *numpy*