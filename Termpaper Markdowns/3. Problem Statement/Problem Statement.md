Narcissistic numbers also known as Armstrong numbers are a specific subset of natural numbers. A number with $n$ digits (where $n$ denotes its dimension) is defined as narcissistic if the sum of its digits, each raised to the power of $n$, equals the number itself [1]. 

A prominent example of a five digit narcissistic number ($\text{n} = 5$) is:

$$54748 = 5^5 + 4^5 + 7^5 + 4^5 + 8^5$$

*(Note: 3125 + 1024 + 16807 + 1024 + 32768 = 54748.)*

In 1985, D. Winter mathematically proved that within the base 10 numeral system, narcissistic numbers can only exist up to a maximum length of 60 digits. This upper bound is derived from the following inequality constraint [1]:

$$\text{n} \cdot 9^{\text{n}} < 10^{\text{n}-1}$$

For any dimension greater than 60, the maximum possible sum of the powered digits ($\text{n} \cdot 9^{\text{n}}$) is strictly less than the smallest possible number of that length ($10^{\text{n}-1}$), making the existence of larger narcissistic numbers mathematically impossible. Consequently, there are exactly 88 narcissistic numbers in base 10, with the largest being the 39 digit number:

$$115,132,219,018,763,992,565,095,597,973,971,522,401 \quad [1]$$

The primary objective of this term paper is to develop and implement the most efficient algorithmic approach to search for and identify as many of these 88 narcissistic numbers as computationally feasible.

Source: https://mathworld.wolfram.com/NarcissisticNumber.html  Access: 1st June 2026 9 AM
