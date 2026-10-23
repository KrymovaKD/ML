# Машинное обучение

Домашние задания по курсу «Машинное обучение».

## Задания

| № | Задание | Данные | Ноутбук |
|---|---|---|---|
| 1 | Предсказание рекомендации авиакомпании пассажиром на основе отзывов (бинарная классификация: kNN, логистическая регрессия, дерево решений, случайный лес, градиентный бустинг) | [Skytrax Airline Reviews](https://www.kaggle.com/datasets/efehandanisman/skytrax-airline-reviews) | [task1/airline_reviews_ml.ipynb](task1/airline_reviews_ml.ipynb) |

## Запуск

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
cd task1
jupyter notebook airline_reviews_ml.ipynb
```

### Данные

1. Скачайте датасет [Skytrax Airline Reviews с Kaggle](https://www.kaggle.com/datasets/efehandanisman/skytrax-airline-reviews).
2. Поместите файл `capstone_airline_reviews3.xlsx` в папку `task1`.
3. Откройте ноутбук и выполните ячейки по порядку.

### Используемые библиотеки

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
