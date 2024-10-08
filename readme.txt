Описание проекта:

Интернет-магазин «В один клик» продаёт разные товары: для детей, для дома, мелкую бытовую технику, косметику и даже продукты. Отчёт магазина за прошлый период показал, что активность покупателей начала снижаться. Привлекать новых клиентов уже не так эффективно: о магазине и так знает большая часть целевой аудитории. Возможный выход — удерживать активность постоянных клиентов. Сделать это можно с помощью персонализированных предложений.

Постановка задачи:

Разработать решение, которое позволит персонализировать предложения постоянным клиентам, чтобы увеличить их покупательскую активность.
1. Нужно построить модель, которая предскажет вероятность снижения покупательской активности клиента в следующие три месяца;
2. В исследование нужно включить дополнительные данные финансового департамента о прибыльности клиента: какой доход каждый покупатель приносил компании за последние три месяца;
3. Используя данные модели и данные о прибыльности клиентов, нужно выделить сегменты покупателей и разработать для них персонализированные предложения.

Используемые модели:

DecisionTreeClassifier() - модель дерева решений;
KNeighborsClassifier() - модель ближайших соседей;
LogisticRegression() - модель логистической регрессии;
SVC() - модель опорных векторов

Результат применения моделей:

Примерно одинаковое качество предсказаний показали модели опорных векторов и логистической регрессии. У данных моделей вероятность корректного предсказания 89,8% и 89,7% соответственно