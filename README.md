# ROIM

## Теоретическая часть 
Доклад на тему <a href="https://colab.research.google.com/drive/1twB4h1TxneUaRUszkSubSzjSbRg9u9tY?usp=sharing">Non-maximum suppression</a>  и картинки 
<a href="non_max_suppression.ipynb%20-%20Colaboratory.pdf">результатов</a>

## Практическая часть 

| Метод         | Параметра          | Количество ошибок (Loo) |
| ------------- |:------------------:| -----:|
|  <a href="src/2w.R">kNN</a>     | k = 4 , l = 150 |  0.04 |
|  <a href="src/Kwnn.r">Kwnn</a>  | k = 4 , l = 150 |  0.04 |
| Парзеновские окна|
| Ядро         | Параметры         | Количество ошибок (Loo) |
|  Прямоугольное      | h = 0.32 |  0.04 |
|  Треугольное   |  h = 0.32 |  0.04 |
|  Квартическое    |  h = 0.32 |  0.04 |
|  Епанечниково    |  h = 0.32 |  0.04 |
|  Гауссовское    |  h = 0.1 |  0.04 |

