# Literate programming

Install the [RStudio](https://www.rstudio.com/) software.

Open it and enter the following commands in the R console:

    install.packages(c("knitr","stargazer","xtable","devtools"))
    library(devtools)
    install_github("rCharts", "ramnathv")

Clone this github repo, or download the files `literate-programming.Rmd`
and `literate-slides.Rpres` by clicking on each file, selecting the
“Raw” button in the upper right, and using your browser’s “Save as”
command.  Be sure you preserve the file extensions.

Open the `literate-programming.Rmd` file in RStudio and select "Knit
HTML" in the editor toolbar.  Read the resulting document.  Open the
`literate-slides.Rpres` file and select “Preview”.
