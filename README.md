## SDSS Computing Studies Python Assignment
### Assignment #3b More Math (Total Marks 10)

Objectives:
* Use the input() command
* Using math operations as appropriate
* Use the math module if necessary
* Use different options for displaying your output


### 2 Tasks

##### Task 1 Percent Error
Ask the user to input the following:
* the expected number
* the actual result
Calculate the percent difference between the two results. Round your answer to 2 decimal places

```
https://www.skillsyouneed.com/num/percent-change.html

Sample Output:
Enter expected: 10
Enter actual : 9
The percent difference is -10.0%

Enter expected: 12
Enter actual : 14
The percent difference is 16.67%
```

##### Task 2 Compound Interest
Ask the user to enter the following:
* The principal (amount invested or borrowed)
* The annual interest rate (expressed as a percent)
* The number of compounding periods per year
* The length of time for the investment
Calculate the final amoutn as well as the amount of interest earned. Round your answer to 2 decimal places

```
https://www.thecalculatorsite.com/articles/finance/compound-interest-formula.php
Enter the Princial: 2000
Enter the annual interest rate as a percent: 4
Enter the number of compounding periods: 4
How long is the investment period in years: 3
Your final amount is $2253.65
You earned $253.65 interest

##### Task 3 Heron's Formula:
write a program to calculate the area of a triangle provided the 3 sides are known:
sample:
```
I will use Heron's formula to find the area of a triangle provided that all 3 sides are known.
You will need to enter the lengths of the 3 sides: a, b and c
Enter the length of side a: 3
Enter the length of side b: 5
Enter the length of side c: 7
Your half perimeter is 7.5
The area of your triangle is 6.495

I will use Heron's formula to find the area of a triangle provided that all 3 sides are known.
You will need to enter the lengths of the 3 sides: a, b and c
Enter the length of side a: 5
Enter the length of side b: 12
Enter the length of side c: 12
Your half perimeter is 14.5
The area of your triangle is 29.342
```

##### Task 4 Convert centimeters to feet and inches
Write a program to ask the user to input a length in centimeters. Convert this into feet and inches.  Round your inches to the nearest whole inch.
You will likely need to make use of at least one of the following:
* % modulus
* math.floor()

Sample output:
```
Enter a length in centimeters: 172
172 centimeters is 5 feet and 8 inches

Enter a length in centimeters: 32
32 centimeters is 1 feet and 1 inches
```

##### Problem 1 : Canadian Income Tax
It's tax season!  Nobody loves doing taxes, so EVERYONE uses computers to help them.  We will use
Python to determine Federal and Provincial Income Tax.

The Canadian income tax system is a tiered system, which means you pay different percentages of
your income for different parts of your income.
You pay 15% tax on the first 49020 you earn.  If you earn more than this amount, you pay
20.5% on amounts over 49020 that are less than 98040
26% on amounts over 98040 but less than 151978
29% on amounts over 151978 but less than 216511
33% on amounts over 216511

Write a program to calculate the amount of Federal Income Tax for people who earn over 100,000 but less than 150,000

Example:
Enter your income: 125000
Your federal income tax is: 24411.7
