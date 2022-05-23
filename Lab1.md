#### 1.	Створити змінні базових (atomic) типів. Базові типи: character, numeric, integer, complex, logical.
```{r}
character <- "example"
logical <- TRUE
numeric <- 5
integer <- 5L
complex <- 1 + 4i
```
#### 2.	Створити вектори, які: містить послідовність з 5 до 75; містить числа 3.14, 2.71, 0, 13; 100 значень TRUE.
```{r}
numeric_vector <- 5:75
vector_with_math <- c(pi, 2.71, 0, 13)
logical_vector <- rep(TRUE, 100)
```
#### 3.	Створити наступну матрицю за допомогою matrix, та за допомогою cbind або rbind
| 0.5 | 1.3 | 3.5 |
|---|---|---|
| 3.9 | 131 | 2.8 |
| 0   | 2.2 | 4.6 |
| 2   | 7   | 5.1 |
