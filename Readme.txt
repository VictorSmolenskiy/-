Постановка задачи.

Из «Бета-Банка» стали уходить клиенты. Каждый месяц. Немного, но заметно. Банковские маркетологи посчитали: сохранять текущих клиентов дешевле, чем привлекать новых.
Нужно спрогнозировать, уйдёт клиент из банка в ближайшее время или нет. Предоставлены исторические данные о поведении клиентов и расторжении договоров с банком. 
Требуется построить модель с предельно большим значением F1-меры. Значение метрики нужно довести до 0.59. F1-меру надо проверить на тестовой выборке.
Дополнительно требуется измерять AUC-ROC, сравнивать её значение с F1-мерой.

Используемые модели.

Для прогнозирования использовались модели:
- Дерево решений
- Случайный лес
- Логическая регрессия

Результат их применения.

Наибольшую эффективность показала модель случайного леса, где была применена методика взвешивания классов.
Значение F1 модели - 0.6408977556109726
AUC-ROC модели: 0.8668832438896723
Модель сохранена в переменной best_balanced_model_forest
Гиперпараметры модели:
- Кол-во деревьев: 10
- Глубина: 9
