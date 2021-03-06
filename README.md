![Title PNG "Skill Factory"](skillfactory_logo.png)
# Дипломный проект. Market prediction. 
<!-- vim-markdown-toc Redcarpet -->

1. [Задача](#задача)
2. Какой кейс решаем?
3. Краткая информация о данных
4. Этапы работы над проектом
5. [Результат](#Результат)

<!-- vim-markdown-toc -->
## Команда
* [Sophia Zamoreeva](https://sfdatasciencecourse.slack.com/archives/D0187AWUYFQ)
* [Shuler](https://sfdatasciencecourse.slack.com/archives/D017GFWS42V)

## Задача
Построить модель, которая бы принимала или пропускала сделку на бирже.

https://www.kaggle.com/c/jane-street-market-prediction

## Какой кейс решаем?
Бинарная классификация. 

## Краткая информация о данных

https://www.kaggle.com/c/jane-street-market-prediction/data

 Этот набор данных содержит анонимизированный набор функций feature_{0...129}, представляющих реальные данные фондового рынка. 
 
 Каждая строка в наборе данных представляет собой торговую возможность, для которой будет предсказываться значение действия: 1 для совершения сделки и 0 для ее передачи. 

*	train.csv - обучающий набор, содержащий исторические данные и возвраты. Большой файл, 2390492 строк, 138 столбцов, 5.77G.
*	example_test.CSV-файл - макет тест-набора, который представляет структуру невидимого набора для тестирования. 
*	example_sample_submission.CSV-файл - образец оформления файла в правильном формате.
*	features.csv - метаданные, относящиеся к анонимизированным функциям.


## Этапы работы над проектом
 * EDA
https://www.kaggle.com/sophiazamoreeva/eda-mp
 * Построение и обучение ML модели.
https://www.kaggle.com/sophiazamoreeva/catboost-models-mp
 * Построение и обучение DL модели.
https://www.kaggle.com/maxkamashev/controlnotebook
 * Blending.
https://www.kaggle.com/sophiazamoreeva/blend-cat-and-nn-models
## Результат
Команда: TWAS Public Score: 8472.277
