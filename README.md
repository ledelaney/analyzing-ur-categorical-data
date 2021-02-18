<img src="https://i1.wp.com/www.sammichespsychmeds.com/wp-content/uploads/2014/09/data-analysis-meme.jpg" width="320" height="200" />

# Analysis of Categorical (Discrete) Data

This repo includes a collection of resources that may be helpful for learning about methods of categorical data analysis, including the specialized case of species data. Many materials are linked below, and others are included in the folders above.

For getting a general sense of what to do with your data and how to work with it in R, I found the `vcdExtra` tutorial and the Penn State course very helpful. The Agresti book is also extremely useful, and also includes an associated R manual (both in general-materials folder). Humble word of advice: start with categorical data analysis in general, and then move on to `caper` or `phylolm` for phylogenetic methods. The main difference is that you will use a phylogeny along with your data, but that can complicate things.

Another humble word of advice: it matters if your response variable is binary. If your response variable is binary, you will need to use a specialized case of `glm` (`family = "binomial"`) and a special function from the `rr2` package (`BinaryPGLMM`).

For visualizing the output, I cannot speak highly enough about `vcdExtra` (for non-phylogentic data).

## For analysis of general data

+ [Analyzing categorical data with `vcdExtra` tutorial](https://www.datavis.ca/courses/VCD/vcd-tutorial.pdf)
+ [PennState graduate course on Analysis of Discrete Data](https://online.stat.psu.edu/stat504/lesson/welcome-stat-504)
  - [R programs specifically](https://online.stat.psu.edu/stat504/lesson/r-programs)
+ [Categorical data analysis in R from Boston University](https://sphweb.bumc.bu.edu/otlt/MPH-Modules/BS/R/R6_CategoricalDataAnalysis/index.html)
+ [Slide presentation on log-linear models for contingency tables](https://education.illinois.edu/docs/default-source/carolyn-anderson/edpsy589/lectures/6-loglinear/6_loglinear_models_beamer-online.pdf)
+ [Watch me personally test every kind of relationship under the sun for one binary response variable and 3 explanatory variables](https://ledelaney.org/projects/whitepapers/trait-association-model-fitting.html)

## For analysis of species data

+ [Phylogenetic linear regression for non-binary response variable: R package `caper`](https://cran.r-project.org/web/packages/caper/vignettes/caper.pdf)
+ [Phylogenetic regression for binary response variable](https://leanpub.com/correlateddata/read#leanpub-auto-phylogenetic-regression-for-binary-data)
+ [Calculating predicted R^2 values for `BinaryPGLMM` results](https://github.com/arives/rr2)
+ For a great primer on binary phylogenetic data, check out Chapter 9 in the book _Modern Phylogenetic Comparative Methods and Their Application in Evolutionary Biology_ (included in materials)
