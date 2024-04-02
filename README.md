# Dataset Description
Данные представляют собой сгенерированные и созданные человеком изображения, на которых находятся обычные бытовые сцены человеческой жизни. Для тестовых данных вам нужно будет подготовить предсказания вероятности того, что изображения были сгенерированы с помощью ИИ.  
Дедлайн до 15 апреля
Данные вязты с этого [сайта](https://www.kaggle.com/competitions/generated-or-not)
test unique values = 506
train unique values = 1012
# Files
- train.csv - тренировочная выборка
- test.csv - тестовая выборка
- sample_submission.csv - пример форматирования файла с ответами
- images - папка с изображениями для тренировки и предсказаний, разделение на train/test можно взять из соответствующих файлов
# Columns
- id - название файла с изображением
- target - вероятность того, что изображение было сгенерировано с помощью ИИ
# Evaluation
В качестве метрики для оценки качества решения мы выбрали log loss

# Submission File
Для каждого ID изображения в тестовом сете вы должны предсказать вероятность того, что оно было сгенерировано. Формат файл с решением можно взять на вкладке "Data (sample_submission.csv)
