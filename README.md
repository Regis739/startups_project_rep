# Создание модель машинного обучения для предсказании неудач стартапов

startups_project.ipynb

# Описание

Некоторые статистические данные утверждают, что процент неудач новых стартапов в настоящее время составляет 90%, https://explodingtopics.com/blog/startup-failure-stats. Поскольку речь идет о больших деньгах, было бы интересно предсказать неудачи стартапов.

# Навыки и Инструменты

- python
- pandas
- numpy
- pipeline
- RandomizedSearchCV
- SMOTETomek
- f1-score
- LogisticRegression
- BalancedRandomForestClassifier
- LGBMClassifier
- SHAP

# Вывод

Используя SMOTETomek для решения проблемы дисбаланса набора тренировочных данных (90-10), мы обучили несколько моделей и выбрали лучшую после cross-validation на основе f1-score, чтобы предсказать неудачи стартапов. Точность прогноза была довольно низкой. Однако это может быть связано не с дисбалансом в тренировочном выборке, а, возможно, сам набор тестовых данных не очень репрезентативен для рынка стартапов. Новие прогнозы должены быть переданы с использованием нового тестового набора.


# Creation of a machine learning model to predict startups failure

startups_project.ipynb

# Description

Some statistics state that the failure rate for new startups is currently 90%, https://explodingtopics.com/blog/startup-failure-stats. Since lot of money are involved it would be interesting to be able to predict startups failure. 

# Skills and Tools

- python
- pandas
- numpy
- pipeline
- RandomizedSearchCV
- SMOTETomek
- f1-score
- LogisticRegression
- BalancedRandomForestClassifier
- LGBMClassifier
- SHAP

# Conclusion
Using SMOTETomek to solve the disblance problem of the training dataset (90%-10%), we have trained several models and have selected the best one after using cross validtation algorithm based on f1-score, in order to predict startups failures. The accuracy of the prediction was rather low. This however might not be because of the disbalance of the training data but possibly the test dataset itself not being very representative of the startups' market. New predictions should be convey using a new test dataset.







