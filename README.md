matawarn
========

Syntax:

```stata
matawarn filename [, view noclear]
```

`matawarn` runs `filename`, checking whether Mata issues a warning. `r(warn)` is `1` if there is a warning and `0` if not.

If there is a warning and option `view` is specified, `matawarn` opens a log file that contains the warning.

`matawarn` clears programs and Mata before running the file unless option `noclear` is specified.
