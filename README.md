
# <center> Проект 3. EDA + Feature Engineering. Соревнование на Kaggle </center>
## Оглавление
1. [Описание проекта](#Описание-проекта)
2. [Описание данных](#Описание-данных)
3. [Зависимости](#Используемые-зависимости)
4. [Установка проекта](#Установка-проекта)
5. [Использование проекта](#Использование)

## Описание проекта

Данный проект создан в качестве jupyter-ноутбука, участвующего в соревновании по машинному обучению на Kaggle ["Booking reviews. Прогнозирование рейтинга отеля на Booking"](https://www.kaggle.com/competitions/sf-booking).

Представим, что работаем дата-сайентистом в компании Booking. Одна из проблем компании — это нечестные отели, которые накручивают себе рейтинг. Одним из способов обнаружения таких отелей является построение модели, которая предсказывает рейтинг отеля. Если предсказания модели сильно отличаются от фактического результата, то, возможно, отель ведёт себя нечестно, и его стоит проверить.

**Основные этапы проекта:**
* Знакомство с данными
* Очистка данных
* Исследование данных
* Генерация признаков
* Преобразование признаков
* Отбор признаков
* Обучение модели

**О структуре проекта:**

* [PROJECT-3. EDA + Feature Engineering.ipynb](./PROJECT-3.%20EDA%20%2B%20Feature%20Engineering.ipynb) - jupyter-ноутбук, содержащий основной код проекта.

## Описание данных

<table >
   <tr>
    <th>Признак</th>
    <th>Описание</th>
  </tr>
  
   <tr>
    <td>hotel_address</td>
    <td>street, post code, city, country </td>
  </tr>
    
   <tr>
    <td>additional_number_of_scoring</td>
    <td>the number of hotel scores without review </td>
  </tr> 
    
  <tr>
    <td>review_date</td>
    <td>the day of review </td>
  </tr>
    
  <tr>
    <td>average_score</td>
    <td>the average rating of the hotel </td>
  </tr>
    
   <tr>
    <td>hotel_name</td>
    <td>the full name of hotel </td>
  </tr>
    
   <tr>
    <td>reviewer_nationality</td>
    <td>country from which the reviewer came </td>
  </tr>
    
   <tr>
    <td>negative_review </td>
    <td>text of negative review </td>
  </tr> 
   
   <tr>
    <td>review_total_negative_word_counts </td>
    <td>the total number words of negative review </td>
  </tr>  
    
   <tr>
    <td>total_number_of_reviews </td>
    <td>the total number of reviews that the hotel has </td>
  </tr>  
    
   <tr>
    <td>positive_review</td>
    <td>text of positive review </td>
  </tr> 
    
   <tr>
    <td>review_total_positive_word_counts</td>
    <td>the total number words of positive review </td>
  </tr> 
    
  <tr>
    <td>total_number_of_reviews_reviewer_has_given</td>
    <td>the total number of reviews reviewer has given </td>
  </tr> 
    
   <tr>
    <td>reviewer_score</td>
    <td>the number of reviewer score </td>
  </tr> 
    
   <tr>
    <td>tags</td>
    <td>tags that describe purpose of trip,type of room, count of nights of reviewer </td>
  </tr> 
    
   <tr>
    <td>days_since_review</td>
    <td>a difference in the number of days between review date and scrape date</td>
  </tr> 
    
   <tr>
    <td>lat</td>
    <td>latitude coordinate of hotel location </td>
  </tr> 
    
   <tr>
    <td>lng</td>
    <td>longitude coordinate of hotel location </td>
  </tr> 
    
</table> </center>

## Используемые зависимости
* Python (3.9):
    * [pandas (1.4.2)](https://pandas.pydata.org)
    * [numpy (1.24.2)](https://numpy.org)
    * [scikit-learn (1.2.2)](https://scikit-learn.org)
    * [matplotlib (3.7.1)](https://matplotlib.org)
    * [plotly (5.14.1)](https://plotly.com/python/)
    * [seaborn (0.12.2)](https://seaborn.pydata.org)

## Установка проекта

```
git clone https://github.com/Vsevolod90/Data_Science_PROJECT_3.git
```
**Примечание:** для запуска jupyter-ноутбука на локальном компьютере используемые в проекте файлы hotels_train.csv (набор данных для обучения), hotels_test.csv (набор данных для оценки качества) и submission.csv (файл сабмишна в нужном формате) необходимо скачать самостоятельно на [сайте соревнования Kaggle](https://www.kaggle.com/competitions/sf-booking/data).

## Использование
Вся информация о работе представлена в jupyter-ноутбуке [PROJECT-3. EDA + Feature Engineering.ipynb](./PROJECT-3.%20EDA%20%2B%20Feature%20Engineering.ipynb).
