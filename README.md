# Repozytorium na potrzeby przedmiotu WIRDS 2021

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pfiedorowicz/wirds-2021-binder/main?urlpath=rstudio)

Aby binder działał potrzebuję następującego pliku:

1. 'runtime.txt' -- określamy z jakiej wersji R będizemy korzystać oraz z jakiego dnia mają być pakiety (np. r-2021-01-01).

Możemy założyć jakie pakiety mają być w ramach tego obrazu. W takim razie powinniśmy utworzyć plik o nazwie 'install.R', który będzie zawierał skrypt R do instalacji pakietów. Na przykład:

```{r}
install.packages("tidyverse")
install.packages("data.table")
install.packages("sf")
install.packages("rio")
```
