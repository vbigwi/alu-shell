# Shell, init files, variables and expansions

Bash scripts about shell initialization files, variables, expansions,
shell arithmetic and aliases. Every script is exactly two lines long and
starts with `#!/bin/bash`.

| Script | What it does |
| ------ | ------------ |
| `0-alias` | Creates an alias `ls` with the value `rm *` |
| `1-hello_you` | Prints `hello <user>` for the current Linux user |
| `2-path` | Adds `/action` as the last directory of `PATH` |
| `3-paths` | Counts the number of directories in `PATH` |
| `4-global_variables` | Lists environment variables |
| `5-local_variables` | Lists local variables, environment variables and functions |
| `6-create_local_variable` | Creates the local variable `BEST` with value `School` |
| `7-create_global_variable` | Creates the global variable `BEST` with value `School` |
| `8-true_knowledge` | Prints 128 plus the value of `TRUEKNOWLEDGE` |
| `9-divide_and_rule` | Prints `POWER` divided by `DIVIDE` |
| `10-love_exponent_breath` | Prints `BREATH` to the power `LOVE` |
| `11-binary_to_decimal` | Converts the base 2 number in `BINARY` to base 10 |
| `12-combinations` | Prints all two-letter combinations except `oo` |
| `13-print_float` | Prints `NUM` with two decimal places |
| `14-decimal_to_hexadecimal` | Converts the base 10 number in `DECIMAL` to base 16 |
| `15-rot13` | Encodes or decodes standard input with rot13 |
| `16-odd` | Prints every other line of the input, starting with the first |
| `17-water_and_stir` | Adds `WATER` (base water) and `STIR` (base stir.) and prints the result in base bestchol |
