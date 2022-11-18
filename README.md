This [drat](http://dirk.eddelbuettel.com/code/drat.html) package repository provides [csverse](https://www.csids.no/packages.html) packages.

![csverse](https://www.csids.no/packages/hex_dependencies.png)

### Usage

#### Usage via drat

```{.r}
# first add the repo
drat::addRepo("csids")

# either install just one or more given packages
install.packages("csdata")     

# or update already installed packages
update.packages()
```

#### Usage without drat

```{r}
# pass the repo info directly to install.packages()
install.packages("csdata", repos = c("https://www.csids.no/drat", "https://cran.rstudio.com"))
```

#### Usage without drat on the shell

```{sh}
Rscript -e 'install.packages("csdata", repos = c("https://www.csids.no/drat", "https://cran.rstudio.com"))'
```

### License

Packages in this repository are available under their respective licenses (generally MIT).