---

# 7. Прогнозирование оттока клиента Банка

---

`python` `pandas` `matplotlib` `scikit-learn` `numpy` `seaborn` `re` 

`train_test_split` `StandardScaler` `OneHotEncoder` `DecisionTreeClassifier` `RandomForestClassifier` `LogisticRegression` `LinearRegression` `accuracy_score` `confusion_matrix` `recall_score` `precision_score` `f1_score` `roc_curve` `roc_auc_score` `SMOTE` `RandomUnderSampler` `DummyClassifier`

---

**Описание проекта**

Из банка стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых. Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком.

**Задачи проекта**

На основе данных из банка определить клиент, который может уйти.

**Вывод**

В условиях дисбаланса модель, обученная методом DecisionTreeClassifier(), имеет значение метрики: F1-мера = 0.57.
Для метода RandomForestClassifier() F1-мера максимальная при глубине 16 и количестве деревьев 80 и составляет 0.61.
Худший показатель F1-меры у модели, обученной LogisticRegression(), 0.35. AUC-ROC составляет 0.86, что достаточно далеко от 1, но уже метрика лучше.

В условиях борьбы с несбалансированностью модели, наилучший показатель F1-меры у модели, обученной методом RandomForestClassifier() с количеством деревьев 70 и глубиной 9, сбалансированной методом RandomUnderSampler - 0.6177. AUC-ROC при этом составляет 0.86.

---
