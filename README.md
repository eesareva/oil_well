<h1> Выбор локации для скважины </h1>

Допустим, вы работаете в добывающей компании «ГлавРосГосНефть». Нужно решить, где бурить новую скважину.

Вам предоставлены пробы нефти в трёх регионах: в каждом 10 000 месторождений, где измерили качество нефти и объём её запасов. Постройте модель машинного обучения, которая поможет определить регион, где добыча принесёт наибольшую прибыль. Проанализируйте возможную прибыль и риски техникой Bootstrap.

**Шаги для выбора локации:**

- В избранном регионе ищут месторождения, для каждого определяют значения признаков;
- Строят модель и оценивают объём запасов;
- Выбирают месторождения с самым высокими оценками значений. Количество месторождений зависит от бюджета компании и стоимости разработки одной скважины;
- Прибыль равна суммарной прибыли отобранных месторождений.
  
<h2>Цель исследования</h2>

Определить, где бурить новую скважину

<h2>Задачи исследования</h2>

Построить модель для определения региона, где добыча принесёт наибольшую прибыль

<h2>Инструменты решения задачи</h2>

- pandas 
- matplotlib
- seaborn
- numpy 
- phik
- sklearn.model_selection.train_test_split
- sklearn.linear_model.LinearRegression
- sklearn.preprocessing.StandardScaler
- sklearn.metrics.mean_squared_error

<h2>Исходные данные</h2>

Данные геологоразведки трёх регионов находятся в файлах:

- /datasets/geo_data_0.csv

- /datasets/geo_data_1.csv

- /datasets/geo_data_2.csv

id — уникальный идентификатор скважины;

f0, f1, f2 — три признака точек

product — объём запасов в скважине (тыс. баррелей).

<h2>Вывод по итогам исследования</h2>

- Выполнила предобработку данных и исследовательский анализ.
- Провела корреляционный анализ
- Обучила модель линейной регрессии для каждого региона
- Подготовила расчёт прибыли и рисков
