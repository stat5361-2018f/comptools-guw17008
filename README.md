# comptools-guw17008
comptools-guw17008 created by GitHub Classroom
> sessionInfo()
R version 3.5.1 (2018-07-02)
Platform: x86_64-w64-mingw32/x64 (64-bit)
Running under: Windows >= 8 x64 (build 9200)

Matrix products: default

locale:
[1] LC_COLLATE=Chinese (Simplified)_China.936  LC_CTYPE=Chinese (Simplified)_China.936   
[3] LC_MONETARY=Chinese (Simplified)_China.936 LC_NUMERIC=C                              
[5] LC_TIME=Chinese (Simplified)_China.936    

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

loaded via a namespace (and not attached):
 [1] compiler_3.5.1  backports_1.1.2 bookdown_0.7    magrittr_1.5    rprojroot_1.3-2 htmltools_0.3.6
 [7] tools_3.5.1     yaml_2.2.0      Rcpp_0.12.18    stringi_1.1.7   rmarkdown_1.10  knitr_1.20     
[13] xfun_0.3        stringr_1.3.1   digest_0.6.16   evaluate_0.11  


1.delete line 251-258 in Introduction.Rmd(can't fix it)
  Quitting from lines 251-258 (Introduction.Rmd) 
  Error: package 'translations' does not have a namespace
  Execution halted
  Error in Rscript_render(f, render_args, render_meta) : 
  Failed to compile Introduction.Rmd
  Calls: <Anonymous> ... render_book -> render_new_session -> Rscript_render
  Execution halted

Exited with status 1.

2.download all package this project needs
  some packages should be downloaded through github(see what reader says in some Rmd files)
  
3.rtools path should be added to system path 

4.download font inconsolata

5.undate pandoc in R

6.download MiKTeX
