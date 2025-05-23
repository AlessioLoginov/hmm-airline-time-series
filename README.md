# HMM-анализ временного ряда авиаперевозок

## 📌 Описание

В этом проекте проведён анализ временного ряда количества международных авиапассажиров (1949–1960 гг.) с помощью **Скрытой Марковской модели (HMM)**.  
Цель — сегментировать ряд на скрытые состояния и построить **наивный прогноз**, опираясь на средние значения внутри каждого состояния.

## 📁 Содержание репозитория

- `HMM-Airline-Passengers-Analysis.ipynb` — основной Colab-ноутбук с пошаговой реализацией;
- `international-airline-passengers.csv` — временной ряд пассажиропотока;
- `README.md` — описание проекта.

## 🚀 Что реализовано

- Загрузка и очистка временного ряда из CSV;
- Обучение `GaussianHMM` (3 состояния);
- Визуализация скрытых состояний HMM;
- Прогнозирование по средним значениям состояний (наивный прогноз);
- Оценка точности прогноза с помощью RMSE.

## 📊 Результаты

- HMM выявила три скрытых состояния, отражающие фазы роста пассажиропотока;
- Наивный прогноз построен как кусочно-постоянная функция по состояниям;
- **RMSE наивного прогноза: 66.87**

## 📎 Зависимости

- `pandas`, `matplotlib`, `numpy`
- `hmmlearn`
- `scikit-learn`


