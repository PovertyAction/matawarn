matawarn
========

Syntax:

```stata
matawarn filename [, view]
```

`matawarn` runs `filename`, checking that Mata issues no warnings. `r(warn)` is `1` if there is a warning and `0` if not. If there is a warning and option `view` is specified, `matawarn` opens a log file that contains the warning.
