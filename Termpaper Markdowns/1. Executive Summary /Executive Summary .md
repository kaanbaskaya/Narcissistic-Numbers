Narcissistic numbers (or Armstrong number) are numbers that can be recreated by summing each of their digits raised to the power of the total number of digits in the number itself. For example, the number 153 is a narcissistic number because it has three digits and satisfies the equation: 

153 = 1^3 + 5^3 + 3^3

The objective of this project is to find as many narcissistic numbers as possible. A major challenge is the rapidly increasing runtime required to test larger numbers. A pure brute force approach checks every number individually by calculating the sum of its powered digits and comparing the result with the original number. However, the search space grows exponentially with the number of digits.

For example if checking a single number requires only 1 microsecond (10^-6 seconds) testing all numbers up to:

(10^6) numbers would already take about 1 second,
(10^9) numbers would take about 17 minutes,
(10^12) numbers would require around 11.5 days,
and (10^15) numbers would take more than 31 years.

Because of this exponential growth, the main task of this project is to develop an optimized algorithm and strategies that minimize runtime as much as possible. The more efficient the approach is, the more narcissistic numbers can realistically be found within a limited amount of computeation time.

Source: https://web.archive.org/web/20171228054132/https://everything2.net/index.pl?node_id=1407017&displaytype=printable&lastnode_id=1407017 Access: 7th May 2026 4 PM
