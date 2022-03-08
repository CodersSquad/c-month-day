Lab - Month Day Calculator
===========================
Using basic concepts of [Pointers and Structures lecture](https://talks.obedmr.com/content/hello-c-world/start-up/01-pointers-structures.html#8),
create a program that calculates the month's day from a given year and year's day. Use pointers for the month and month's day variables.
Don't forget to add proper errors handling in your program.

Modify the provided `month_day.c` file to receive the parameters in the way and also print the proper formatted output.

```
# ./month_day <year> <yearday>

# Example for Feb 2nd, 2019:
\$ ./month-day 2019 33
Feb 02, 2019
```

General instructions
--------------------
1. Use the  `month-day.c` file for your code
2. Don't forget to test your code before submission
3. Submit your code to your personal fork


Errors handling
---------------
In order to pass the tests, the following instructions must be followed for handling error.

- Consider the following list of output strings in case of errors. The strings are descriptive.
```
Invalid Input
```

Test Suite
----------
Build and Test automation is already implemented with the following command. Below some general tips and comments.

- Make sure that your program passes all test cases without errors.
- Remember that this is being executed by a robot script.
- Failed compilation or segmentation faults means 0-graded.
- Failed tests will be properly discounted from total grade.

### Build
```
make
```

### Test
```
make test
```

### Clean
```
make clean
```
