# Resolve methodology template for R

Developed by Julie Christie, March 2024

This is a template structure for how Resolve communicates its data journalism work publicly and to our newsroom and community partners. We have available a methodology template and a data diary template available to use in this repo.

The methodology template is also available as a package in R to download and customize.

This package was developed with lots of [references to Bookdown](https://bookdown.org/yihui/rmarkdown/document-templates.html).

:link: [Check out the data diary template](https://github.com/Resolve-Philly/Methodology-Template/blob/main/Data%20Diary%20Template.md)

:link: [Check out a markdown version of the methodology template](https://github.com/Resolve-Philly/Methodology-Template/blob/main/Template%20Markdown.md) that is tool agnostic

## Instructions to download package in R

1. Open RStudio and paste the below code in your console, one line at a time
```r
if (!requireNamespace("devtools")) install.packages("devtools")
devtools::install_github("Resolve-Philly/Methodology-Template-R")
library(ResolveMethodology)
```
2. Click the button to add a new file and select R Markdown
3. Choose the `From Template` option and then select `Resolve Methodology Template` to get started
4. Each phrase with TK is a part of the template that you will need to fill in with your information.

# Use this methodology
Anybody is welcome to replicate and customize this methodology structure for their work. See below to follow instructions to make your own template

## Customize the R package for your organization

You can [fork this repository](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) to create your own custom package. Below I've suggested the portions of the template that are best to customize.

- [ ] Change the logo at the top of the methodology
- [ ] Change the `newsroom` section in the YAML to whatever way collaboration shows up in your work
- [ ] Change the output information so you can knit the methodology however you want
- [ ] Add in the packages your team should always use, as well as the common packages they'll often use
- [ ] Plug in all the API keys you will need to use

## For programs other than R

You can get a basic markdown file of this methodology structure as well. If you jump to [Template Markdown](https://github.com/Resolve-Philly/Methodology-Template-R/blob/main/Template%20Markdown.md) above, you can just directly save the file and customize to your heart's desire for your other programs. 

Updates specifically for other tools to export to much more "human friendly" views like a `.pdf` or `.html` document may be done in the future.

## Template Preview

![TemplatePreview](inst/rmarkdown/templates/template-name/skeleton/TemplatePreview.png)
