This reprex appears to crash R.
See standard output and standard error for more details.

#### Standard output and error

``` sh
[31mx[39m Install the [34m[34mstyler[34m[39m package in order to use [38;5;235m[48;5;253m[38;5;235m[48;5;253m`style = TRUE`[48;5;253m[38;5;235m[49m[39m.
running: python  -c "x = 'hello, python world!'
print(x.split(' '))"
Building shared library for Rcpp code chunk...
Warning message:
In system(cmd) : 'make' not found

Quitting from lines 71-78 (parcial_reprex.Rmd) 
Error in (function (file = "", code = NULL, env = globalenv(), embeddedR = TRUE,  : 
  Error 1 occurred building shared library.
Además: Warning message:
In system2(cmd, code, stdout = TRUE, stderr = TRUE, env = options$engine.env) :
  comando ejecutado '"python"  -c "x = 'hello, python world!'
print(x.split(' '))"' tiene estatus 9009
```

