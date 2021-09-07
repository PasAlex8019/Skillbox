# Skillbox
practical training on Skillbox

Экзамен по курсу Аналитика данных на Python

import pandas as pd

import numpy as np

import matplotlib.pyplot as plt

⭐️ Вопрос 1 Загрузите данные из файла online-retail.csv в переменную типа pandas DataFrame

Подсказка: Используйте функцию из библиотеки pandas

Какой символ-разделитель используется в этом файле?

Запятая "," Двоеточие ":" Точка с запятой ";" Символ табуляции "tab"

df = pd.read_csv('online-retail.csv', sep=';')

df.head()

Type Markdown and LaTeX:  𝛼2

df.info()
