Project Euler
==============

1) If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000.
*  Notes: Naive solution done using list comprehension:<code>sum([x for x in range(1000) if x % 3== 0 or x % 5== 0])</code>

2) Each new term in the Fibonacci sequence is generated by adding the previous two terms. By starting with 1 and 2, the first 10 terms will be:
    <code>1, 2, 3, 5, 8, 13, 21, 34, 55, 89, ...</code>
By considering the terms in the Fibonacci sequence whose values do not exceed four million, find the sum of the even-valued terms.

3) The prime factors of 13195 are 5, 7, 13 and 29. What is the largest prime factor of the number 600851475143 ?

4) A palindromic number reads the same both ways. The largest palindrome made from the product of two 2-digit numbers is 9009 = 91 99. Find the largest palindrome made from the product of two 3-digit numbers.

5) 2520 is the smallest number that can be divided by each of the numbers from 1 to 10 without any remainder. What is the smallest positive number that is evenly divisible by all of the numbers from 1 to 20?

6) The sum of the squares of the first ten natural numbers is,
<code>1^2 + 2^2 + ... + 10^2 = 385</code>
The square of the sum of the first ten natural numbers is,
<code>(1 + 2 + ... + 10)^2 = 55^2 = 3025</code>
Hence the difference between the sum of the squares of the first ten natural numbers and the square of the sum is 3025 - 385 = 2640.
Find the difference between the sum of the squares of the first one hundred natural numbers and the square of the sum.

7) By listing the first six prime numbers: 2, 3, 5, 7, 11, and 13, we can see that the 6th prime is 13. What is the 10,001st prime number?
* Notes: Decided to implement the solution using the Sieve of Atkin algorithm (http://en.wikipedia.org/wiki/Sieve_of_Atkin). Time to find 10,001st prime: 0.20333(rep) sec