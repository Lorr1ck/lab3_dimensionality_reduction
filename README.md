# Лабораторная работа №3: Понижение размерности

## Описание
Исследование методов снижения размерности: PCA (с нуля и sklearn), t-SNE, UMAP. Анализ геометрии данных, интерпретация главных компонент, оценка ошибки восстановления.

## Датасет
Titanic (числовые признаки)

## Структура
- `data/titanic.csv` – исходные данные
- `notebooks/03_dimensionality_reduction.ipynb` – основной ноутбук
- `report/dim_reduction_report.md` – отчёт

## Запуск
```bash
git clone https://github.com/Lorr1ck/lab3_dimensionality_reduction.git
cd lab3_dimensionality_reduction
pip install pandas numpy matplotlib seaborn scikit-learn umap-learn
jupyter notebook notebooks/03_dimensionality_reduction.ipynb
