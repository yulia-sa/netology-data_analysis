# netology-data_analysis

Дано: данные о популярности имен для новорожденных (директория /names). 

# Задача №1

С использованием Pandas написать функцию, которая загружает указанные года и выводит ТОП-3 популярных имен. Например:

```#!bash

count_top3([1880]) == ['John', 'William', 'Mary']
count_top3([1900, 1950, 2000]) == ['James', 'John', 'Robert']

```


# Задача №2

С использованием Pandas написать функцию, которая возвращает динамику изменения количества имен за указанные года в разрезе полов. Например:

```#!bash

count_dynamics([1900, 1950, 2000]) == {
  'F': [299810, 1713259, 1814922],
  'M': [150486, 1790871, 1962744]
}

```
