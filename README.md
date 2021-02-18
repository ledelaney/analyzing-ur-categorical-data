# Analysis of Categorical (Discrete) Data

Find below some helpful websites for learning about categorical data analysis. Personally I found the PennState course to be the most helpful, as it also includes associated R tutorials. Humble word of advice: start with categorical data analysis in general, and then move on to `caper` or `phylolm` for phylogenetic methods. The main difference is that you will use a phylogeny along with your data, but that can complicate things.

Another humble word of advice: it matters if your response variable is binary. If your response variable is binary, you will need to use a specialized case of `glm` (`family = "binomial"`) and a special function from the `rr2` package (`BinaryPGLMM`).

For visualizing the output, I cannot speak highly enough about `vcdExtra` (for non-phylogentic data).

## For any data

+ [PennState graduate course on Analysis of Discrete Data](https://online.stat.psu.edu/stat504/lesson/welcome-stat-504)
  - [R programs specifically](https://online.stat.psu.edu/stat504/lesson/r-programs)
+ [Slide presentation on log-linear models for contingency tables](https://education.illinois.edu/docs/default-source/carolyn-anderson/edpsy589/lectures/6-loglinear/6_loglinear_models_beamer-online.pdf)
+ [Categorical data analysis in R from Boston University](https://sphweb.bumc.bu.edu/otlt/MPH-Modules/BS/R/R6_CategoricalDataAnalysis/index.html)
+ [Watch me personally test every kind of relationship under the sun for one binary response variable and 3 explanatory variables](https://ledelaney.org/projects/whitepapers/trait-association-model-fitting.htm)

## For analyzing species data

+ [Phylogenetic linear regression for non-binary response data: R package `caper`](https://cran.r-project.org/web/packages/caper/vignettes/caper.pdf)
+ [Phylogenetic regression for binary response variable](https://leanpub.com/correlateddata/read#leanpub-auto-phylogenetic-regression-for-binary-data)
+ [Calculating predicted R^2 values for `BinaryPGLMM` results](https://github.com/arives/rr2)
+ Check out Chapter 9 in the book _Modern Phylogenetic Comparative Methods and Their Application in Evolutionary Biology_ (included in materials)
