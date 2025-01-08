# knit_wo_overwrite

Generally when we knit a Rmd file within Rstudio, it makes an output file with same name as input Rmd file with the new extension. This has the unfortunate effect of overwriting previous knitted output. This is a chunk of code to be added to the header to avoid overwriting the output file when re-knitting a Rmd file.

Here the output is a html document which will have same name as input file with the date as the extension.
