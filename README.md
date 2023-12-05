# problem1

Для классификаций изображений была использована CNN - ResNet50

Первая тренировка модели включала в себе 8 эпох:
на основе данных train_tiny был создан первый вариант модели best_train_tiny.
Протестировав на различных датасетах были получены следующие результаты:

10% of test_tiny - balanced accuracy 0.8889

test_tiny - balanced accuracy 0.9333

test_small - balanced accuracy 0.9072

test - balanced accuracy 0.9020.

Используя количество эпох = 5 и датасет train_small, была получена модель best_train_small. Со следующими результатами:

10% of test_small - balanced accuracy 0.9889

test_tiny - balanced accuracy 0.9778 

test_small - balanced accuracy 0.9433

10% of test - balanced accuracy 0.9911

test - balanced accuracy 0.9458.


В PDF файле представлены графики зависимости accuracy от эпохи. (к сожалению я не разобралась как убрать лишние строки из выходных данных, поэтому количесвто страниц в файле очень большое)
