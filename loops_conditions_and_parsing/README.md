# Shell, loops, conditions and parsing

Bash scripts using `for`, `while` and `until` loops, `if`/`elif`/`else`
and `case` conditions, file test operators, `cut`, `IFS` and `awk`.
Every script starts with `#!/usr/bin/env bash`, has a comment on its second
line and passes Shellcheck.

| Script | What it does |
| ------ | ------------ |
| `1-for_best_school` | Prints Best School 10 times with a for loop |
| `2-while_best_school` | Prints Best School 10 times with a while loop |
| `3-until_best_school` | Prints Best School 10 times with an until loop |
| `4-if_9_say_hi` | Prints Best School 10 times and Hi after the 9th |
| `5-4_bad_luck_8_is_your_chance` | bad luck at 4, good luck at 8, Best School otherwise |
| `6-superstitious_numbers` | Numbers 1 to 20 with superstition messages at 4, 9 and 17 |
| `7-clock` | Hours 0 to 12 with minutes 1 to 59 |
| `8-for_ls` | Lists the current directory, names after the first dash |
| `9-to_file_or_not_to_file` | Describes the file named `school` |
| `10-fizzbuzz` | FizzBuzz from 1 to 100 |
| `11-read_and_cut` | Username, uid and home directory from `/etc/passwd` |
| `12-tell_the_story_of_passwd` | A story for each line of `/etc/passwd` |
| `13-lets_parse_apache_logs` | IP and HTTP code from `apache-access.log` |
| `14-dig_the-data` | Occurrences per IP and HTTP code, most frequent first |
