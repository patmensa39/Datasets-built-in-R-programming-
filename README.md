# Datasets-built-in-R-programming-
---
title: "Examining datasets built in R programming"
output:
  pdf_document: default
  html_document: default
  word_document: default
date: "June 2022"
theme: cerulean
---

<!-- For more info on RMarkdown see http://rmarkdown.rstudio.com/ -->

## Name: Mensah Patrick-Hw-1


## The IRIS data
### This famous (Fisher's or Anderson's) iris data set gives the measurements in centimeters of the variables sepal length and width and petal length and width, respectively, for 50 flowers from each of 3 species of iris. The species are Iris setosa, versicolor, and virginica.

```{r echo=TRUE}
?iris
View(iris)
### This shows the summary of the iris data
summary(iris)
```


## The Titanic data

### This data set provides information on the fate of passengers on the fatal maiden voyage of the ocean liner ‘Titanic’, summarized according to economic status (class), sex, age and survival.

```{r echo=TRUE}
?Titanic
View(Titanic)
```

## Student Admissions at UC Berkeley
### Aggregate data on applicants to graduate school at Berkeley for the six largest departments in 1973 classified by admission and sex.

```{r echo=TRUE, fig.align='center'}
?UCBAdmissions
View(UCBAdmissions)
```



## The STATE.77 data
### Data sets related to the 50 states of the United States of America.
```{r echo=FALSE}
?state.x77
View(state.x77)
### This shows the summary of the state.77 data
summary(state.x77)
```


## The SWISS data 
### Standardized fertility measure and socio-economic indicators for each of 47 French-speaking provinces of Switzerland at about 1888.
```{r echo=TRUE}
?swiss
View(swiss)
### This shows the summary of the swiss data
summary(swiss)
```


