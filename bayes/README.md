# bayes

This is a talk I gave at Uber about Bayes' Theorem + Bayesian Inference (including my world famous package [bayesAB](https://github.com/FrankPortman/bayesAB)).

## How to build

In your terminal, assuming R and `rmarkdown` are installed:
```
Rscript -e 'rmarkdown::render("bayes.Rmd")'
```

## What's included here

- Raw rmarkdown file that generates slides + figures
- Final output `bayes.html`
- Some intermediate files for `bayes.html` to be viewable on Github

## Extra (2017-11-01)

Github isn't showing the `.html` file claiming it's "too big". If you don't want to rebuild the markdown file yourself
you can simply clone the repo and open the html file locally and the relative paths will work.
