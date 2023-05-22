# 2V Introduction to Web Scraping and Data Management for Social
Scientists
Dr Marius Sältzer & Dr Johannes B. Gruber

This is the course material for the Essex Summer School in Social
Science Data Analysis course [2V Introduction to Web Scraping and Data
Management for Social
Scientists](https://essexsummerschool.com/summer-school-facts/courses/ess-2023-course-list/2v-introduction-to-web-scraping-and-data-management-for-social-scientists/).

# Schedule

| time   | Session                                  |
|--------|------------------------------------------|
| Day 1  | Introduction to computing                |
| Day 2  | Introduction to the Web                  |
| Day 3  | static web pages                         |
| Day 4  | interactive web pages                    |
| Day 5  | application programming interface (APIs) |
| Day 6  | Reading and storing treelike data        |
| Day 7  | Linking and joining data                 |
| Day 8  | Basic SQL                                |
| Day 9  | Storing data at scale                    |
| Day 10 | Planning a data project                  |

# Required software

You should have several software applications installed before the start
of the course:

- [R](https://cran.r-project.org/)
- [RStudio Desktop](https://posit.co/download/rstudio-desktop/) or
  [VSCodium](https://vscodium.com/) or
  [VSCodium](https://code.visualstudio.com/download)
- [Quarto](https://quarto.org/docs/get-started/)
- [Docker Desktop](https://docs.docker.com/get-docker/) or the [Docker
  Engine](https://docs.docker.com/engine/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

You do not need to know what all of these do and we have limited time
available to help you get them running, but ideally they all work
beforehand.

Most R packages install quickly, but you can get ahead and run this code
in a new R session to find and install all required packages:

``` r
if (!requireNamespace("rlang", quietly = TRUE)) install.packages("rlang", dependencies = TRUE)
rlang::check_installed("attachment")
rlang::check_installed(attachment::att_from_qmds(path = ".", recursive = TRUE))
```
