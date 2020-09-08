Statistics with R
================
Yihun Zeleke
8/21/2020

``` r
rmarkdown::render("testR.md", params = list(
  year = 2020,
  printcode = T
))
```

    ## "C:/Users/yihun/ANACON~1/Scripts/pandoc" +RTS -K512m -RTS testR.utf8.md --to html4 --from markdown+autolink_bare_uris+tex_math_single_backslash --output testR.html --email-obfuscation none --self-contained --standalone --section-divs --table-of-contents --toc-depth 3 --variable toc_float=1 --variable toc_selectors=h1,h2,h3 --variable toc_print=1 --template "C:\Users\yihun\Documents\R\win-library\4.0\rmarkdown\rmd\h\default.html" --highlight-style zenburn --variable "theme:flatly" --include-in-header "C:\Users\yihun\AppData\Local\Temp\RtmpUHvXAL\rmarkdown-strbb84dfc404.html" --mathjax --variable "mathjax-url:https://mathjax.rstudio.com/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" --lua-filter "C:/Users/yihun/Documents/R/win-library/4.0/rmarkdown/rmd/lua/pagebreak.lua" --lua-filter "C:/Users/yihun/Documents/R/win-library/4.0/rmarkdown/rmd/lua/latex-div.lua" --variable code_folding=hide --variable code_menu=1
