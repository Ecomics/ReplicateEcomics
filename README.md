## Welcome to Ecomics Replication Station.

The page is for anyone who wants to replicate the results published in Kim et al. 2016. 

### Dependencies

- [R 3.4.0 or above](https://www.r-project.org/)
- [ggplot2](http://ggplot2.org/)

### Replication of Published Results

#### 1) Reproduce Fig S5.

```R
source("run.R")
drawCV("Dataset/CorrectEcomics.txt","FigS5.CorrectEcomics.pdf","FigS5")
drawCV("Dataset/WrongEcomics.csv","FigS5.WrongEcomics.pdf","FigS5")
```

#### 2) Reproduce Fig S10a.

```R
source("run.R")
drawCV("Dataset/CorrectEcomics.txt","FigS10a.CorrectEcomics.pdf","Fig10a")
drawCV("Dataset/WrongEcomics.csv","FigS10a.WrongEcomics.pdf","FigS10a")
```

#### 3) Reproduce Fig S12.

```R
source("run.R")
drawCV("Dataset/CorrectEcomics.txt","FigS12.CorrectEcomics.pdf","Fig12")
drawCV("Dataset/WrongEcomics.csv","FigS12.WrongEcomics.pdf","FigS12")
```

### Support or Contact

If you have any questions on this page, please contact Minseung Kim (msgkim@ucdavis.edu).
