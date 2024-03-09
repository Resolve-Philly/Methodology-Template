# Resolve methodology template for R

This is a simple package that you can download to use Resolve Philly's standard methodology.

Developed by Julie Christie, March 2024

This package was developed with lots of references to [Bookdown](https://bookdown.org/yihui/rmarkdown/document-templates.html).

You are welcome to use and replicate this package for your own use. This package was developed with lots of references to [Bookdown](https://bookdown.org/yihui/rmarkdown/document-templates.html).

## Instructions to download package

1. Open RStudio and paste the below code in your console, one line at a time
```r
if (!requireNamespace("devtools")) install.packages("devtools")
devtools::install_github("Resolve-Philly/Methodology-Template-R")
```
2. Click the button to add a new file and select R Markdown
3. Choose the `From Template` option and then select `Resolve Methodology Template` to get started
4. Each phrase with TK is a part of the template that you will need to fill in with your information.

# Replicating this methodology for others
Anybody is welcome to replicate and customize this methodology structure for their work. See below to follow instructions to make your own template

## Customize the R package for your organization
1. Change the logo 
  1. Navigate to `/ResolveMethodology/inst/rmarkdown/templates/template-name/skeleton`
  2. Delete Resolve's logo and add your own logo
  3. In that same folder, open `skeleton.rmd` and paste in your new logo file name in the parenthesis.
  4. Save your file.
  5. Update your package 

If you want to further customize the template for your company -- changing its name or adding in your needed API keys, for example, you can edit the foldernames and then follow the above instructions for downloading a new package. To make your own template from scratch (which may be easier) follow the instructions outlined in [Bookdown](https://bookdown.org/yihui/rmarkdown/document-templates.html).

## For programs other than R
You can get a basic markdown file of this methodology structure as well. If you jump to [Template Markdown](https://github.com/Resolve-Philly/Methodology-Template-R/blob/main/Template%20Markdown.md) above, you can just directly save the file and customize to your heart's desire for your other programs. 

Updates specifically for other programs to export to much more "human friendly" views like a `.pdf` or `.html` document may be done in the future.

## Template Preview

![TemplatePreview](inst/rmarkdown/templates/template-name/skeleton/TemplatePreview.png)
