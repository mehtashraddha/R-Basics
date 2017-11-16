
### WORKING WITH BOOLEAN LOGIC
Code reference: https://www.r-bloggers.com/logical-operators-in-r/
This code demonstrates the use of AND, OR and NOT boolean operators in R.


```r
x <- 30
y <- 22

#Exploring AND, represented by "&" in R
#AND checks for both the given values to be TRUE, else the answer becomes FALSE

(x == 30) & (y == 22) #Both the values are correct, answer will be TRUE
```

```
## [1] TRUE
```

```r
(x == 30) & (y == 55) #Value of y is wrong, answer becomes FALSE
```

```
## [1] FALSE
```

```r
#Exploring OR, represented by "|" in R
#OR checks for either of the values to be correct, even if one value is correct answer will be TRUE

(x == 40) | (y == 22) #Value of y is correct, answer will  be TRUE
```

```
## [1] TRUE
```

```r
(x == 1) | (y == 90) #Both the values are wrong, answer will be FALSE
```

```
## [1] FALSE
```

```r
#Exploring NOT, represented by "!" in R
#NOT negates the value, if it is TRUE it becomes FALSE and vice-versa

a <- TRUE
b <- FALSE
!a #Negates the value of a , answer will be FALSE
```

```
## [1] FALSE
```

```r
!b #Negates the value of b , answer will be TRUE
```

```
## [1] TRUE
```
