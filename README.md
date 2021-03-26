# A tester for Push_swap@42 - To see what's going on
This tester shows the performance of your push_swap program. 

This tester *DOES NOT* check that your checker works correctly.

* [What's push_swap tester?](#what's-push_swap_tester?)
* [How do I run this tester?](#how-do-I-run-this-tester?)
* [Project status](#project-status)


## What's push_swap_tester?

Push_swap_tester is a little tester that shows you how your push_swap performs.
It displays the number of instructions performed by your push_swap in color, here is what the colors mean:
```diff
# white means amazing!
@@ blue means good @@
+ green means ok
! orange means really bad
- red means eliminatory
```

![Screenshot](screenshot.png)


## How do I run this tester?

```bash
git clone https://github.com/lmalki-h/push_swap_tester
bash push_swap_tester/tester.sh [path-to-push-swap-dir] [stack-size 0R range] [nb_of_tests]
```
### for example:
the following command will perform 100 testss with a stack of 100 integers
```bash
bash push_swap_tester/tester.sh ../push_swap 100 100
```
   
the following command will perform 100 tests with a stack of 100 integers, then 100 tests with a stack of 101 integers and then 100 tests with a stack of 102 integers
```bash
bash push_swap_tester/tester.sh ../push_swap 100-1002 100
```

## Project status
This project was submitted as is.
