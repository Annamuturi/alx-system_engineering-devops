# 0x04. Loops, conditions and parsing

## About this project:
* In this project i learnt and practiced;
* How to create SSH keys
* What is the advantage of using `#!/usr/bin/env bash` over `#!/bin/bash`
* How to use `while,` `until` and `for loops`
* How to use `if,` `else,` `elif` and `case` condition statements
* How to use the `cut` command
* What are files and other comparison operators, and how to use them

## Task files description:
* [0-RSA_public_key.pub](0-RSA_public_key.pub) A public SSH key for Login to remote servers for ALX project. Private key is on the ALX ubuntu sandbox 

* [1-for_best_school](1-for_best_school) A Bash script that displays `Best school` 10 times.using `for`

* [2-while_best_school](2-while_best_school) A Bash script that displays Best School 10 times. using `while`

* [3-until_best_school](3-until_best_school) A Bash that displays "Best School" 10times using `until`

* [4-if_9_say_hi](4-if_9_say_hi) A Bash script that displays Best School 10 times, but for the 9th iteration, displays Best School and then Hi on a new line
 - You must use the while loop (for and until are forbidden)
 - You must use the if statement

* [5-4_bad_luck_8_is_your_chance](5-4_bad_luck_8_is_your_chance) A Bash script that loops from 1 to 10 and:
 - displays `bad luck`  for the 4th loop iteration
 - displays `good luck` for the 8th loop iteration
 - displays `Best School` for the other iterations
### Requirements:
 - You must use the while loop (for and until are forbidden)
 - You must use the if, elif and else statements

* [6-superstitious_numbers](6-superstitious_numbers) A bash script that displays numbers from 1 to 20 and:
 - displays `4` and then `bad luck from China` for the 4th loop iteration
 - displays `9` and then `bad luck from Japan` for the 9th loop iteration
 - displays `17` and then bad `luck from Italy` for the 17th loop iteration
### Requirement:
 - You must use the `while` loop (`for` and `until` are forbidden)
 - You must use the `case` statement

* [7-clock](7-clock) A bash script that displays the time for 12hours and 59minutes:
 - display hours from 0 to 12
 - display minutes from 1 to 59
###Requirement:
 - You must use the `while` loop (`for` and `until` are forbidden)

* [8-for_ls](8-for_ls) A Bash script that displays:
 - The content of the current directory
 - In a list format
 - Where only the part of the name after the first dash is displayed (refer to the example)
###Requirements:
 - You must use the `for` loop (`while` and `until` are forbidden)
 - Do not display hidden files

* [9-to_file_or_not_to_file](9-to_file_or_not_to_file) A Bash script that gives you information about the school file.
###Requirements:
 - You must use `if` and, `else` (`case` is forbidden)
 - Your Bash script should check if the file exists and print:
        * if the file exists: school file exists
        * if the file does not exist: school file does not exist
 - If the file exists, print:
        - if the file is empty: school file is empty
        - if the file is not empty: school file is not empty
        - if the file is a regular file:school is a regular file
        - if the file is not a regular file: (nothing)

* [10-fizzbuzz](10-fizzbuzz) A  Bash script that displays numbers from 1 to 100.
###Requirements:
 - Displays `FizzBuzz` when the number is a multiple of 3 and 5
 - Displays `Fizz` when the number is multiple of 3
 - Displays `Buzz` when the number is a multiple of 5
 - Otherwise, displays the number
 - In a list format
