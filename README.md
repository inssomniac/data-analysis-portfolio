# Анализ данных

Домашние работы и мини-проекты курса «Анализ данных» (ИШ НГУ, 2025–2026).


---

## Содержание

| # | Тема | Датасет | Ноутбук |
|---|------|---------|---------|
| 1 | Pandas: основы работы с табличными данными | — | [hw_1](hw_1/) |
| 2 | Очистка и подготовка данных | Netflix Movies, Wine Reviews | [hw_2](hw_2/) |
| 3 | Разведочный анализ (EDA) | Wine Reviews | [hw_3](hw_3/) |
| 4 | Статическая визуализация, распределения | CDNOW (e-commerce) | [hw_4](hw_4/) |
| 5 | Динамическая визуализация, временные ряды | Акции 2021–2024 | [hw_5](hw_5/) |
| 6 | Данные в машинном обучении | Telco Churn, Mall Customers | [hw_6](hw_6/) |
| 7 | Инженерия признаков | Wine Quality, Insurance | [hw_7](hw_7/) |
| 8 | Понижение размерности (PCA, t-SNE, UMAP) | Wine Quality | [hw_8](hw_8/) |
| 9 | Токенизация текста | YouTube Comments | [hw_9](hw_9/) |
| 10 | Эмбеддинги (BoW, TF-IDF, Word2Vec, FastText, GloVe) | YouTube Comments | [hw_10](hw_10/) |
| 11 | Геоданные | NYC Taxi 2016 | [hw_11](hw_11/) |

---

## Стек

**Данные и анализ:** pandas, numpy  
**Визуализация:** matplotlib, seaborn, plotly, geopandas  
**Машинное обучение:** scikit-learn, CatBoost  
**NLP:** nltk, gensim  
**Временные ряды:** statsmodels  
**Геоданные:** geopandas, geopy  

---

## Детали по домашним работам

### hw_1 — Pandas
Основные структуры (`Series`, `DataFrame`), фильтрация и `.loc[]`, создание признаков, группировка и агрегация.

### hw_2 — Очистка данных
Диагностика датасета, работа с пропусками (NaN), дубликатами, выбросами. IQR-метод и Z-score. Нормализация текстовых полей.

>  `winemag-data-130k-v2.csv` в репозиторий не включён из-за размера (51 МБ). Скачать: [Kaggle — Wine Reviews](https://www.kaggle.com/datasets/zynicide/wine-reviews)

### hw_3 — EDA
Одномерный и двумерный анализ. Корреляции Пирсона и Спирмена, skewness, kurtosis. Работа с матрицей корреляций и pairplot.

### hw_4 — Статическая визуализация
Гистограммы, KDE, boxplot, scatter. Теоретические и эмпирические распределения через `scipy.stats`. BTYD-модель (геометрическое и экспоненциальное распределения).

### hw_5 — Временные ряды
Декомпозиция ряда (тренд, сезонность, резидуал), скользящее среднее. Финансовые графики (candlestick). Интерактивная визуализация через Plotly. MASE.

### hw_6 — ML: базовые задачи
Регрессия и классификация (SGDRegressor, LogisticRegression, RandomForest, CatBoost). Метрики: MAE, RMSE, R², F1, ROC-AUC, Confusion Matrix. Кластеризация K-Means с методом локтя и Silhouette Score. Работа с дисбалансом классов, порог классификации.

### hw_7 — Инженерия признаков
Train/Valid/Test split, стратификация, дрейф данных (KS-тест). Feature Engineering: бинаризация, взаимодействие, полиномиальные признаки. Feature Importance: статистическая, модельная, Lasso. k-Fold Cross-Validation.

### hw_8 — Понижение размерности
PCA (объяснённая дисперсия, метод локтя), t-SNE, UMAP. Сравнение методов: скорость, `transform()`, применение.

### hw_9 — Токенизация
Word-level, Char-level, BPE (Byte-Pair Encoding). OOV-проблема, стоп-слова, частотный анализ.

### hw_10 — Эмбеддинги
BoW, TF-IDF. Обучение Word2Vec и FastText на корпусе. Предобученные GloVe-векторы. Косинусное сходство.

### hw_11 — Геоданные
GeoDataFrame, геометрические типы (Point, Polygon). Spatial Join: точки такси → районы. Геодезические расстояния. Хороплет-карты.

> `yellow_tripdata_2016-03-01.csv` в репозиторий не включён из-за размера (46 МБ). Скачать: [NYC TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)

---

## Мои проекты

| Проект | Описание | Ноутбук |
|--------|----------|---------|
| Bike Sharing Demand | Прогноз спроса на велопрокат (Kaggle) | [ноутбук](my_projects/bike%20sharing%20demand/) |
| Palmer Penguins | Классификация пингвинов | [ноутбук](my_projects/palmer%20penguins/) |
| Tokenization Report | Отчёт-исследование по методам токенизации | [ноутбук](my_projects/tokenization_report/) |
