# Ускорение вычислений scikit-learn за счёт использования инструментария daal4py

На примере задачи предсказания наличия или отсутствия сердечно-сосудистых заболеваний 
у человека по датасету **Cardiovascular Disease dataset**, рассмотрены возможности 
библиотеки daal4py по расширению возможностей аналитики данных scikit-learn, 
посредством ускоренных матричных преобразований.

Реализован ensamble из моделей KNeighbors, Random Forest, Logistic Regression

&nbsp;

---

Необходимо предварительно установить пакеты:
 - **numpy, pandas** для работы с датасетом
 - **matplotlib, seaborn** для отрисовки графиков
 - **sklearn, daal4py** для реализации алгоритмов Machine Learning

&nbsp;

---
 
`ML_challenge.ipynb` - jupyter notebook с описанием работы

`Dataset/cardio.csv` - датасет Cardiovascular Disease dataset

`Result/my_result.csv` - файл с результатом обучения разработчика

`Result/result_v1.csv` - файл с результатом обучения после вашего запуска(появится после запуска)

&nbsp;

---
Cardiovascular Disease dataset:

https://www.kaggle.com/sulianova/cardiovascular-disease-dataset


Документация Daal4py:
 
 https://intelpython.github.io/daal4py
 
 https://github.com/IntelPython/daal4py