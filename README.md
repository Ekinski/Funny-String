# Funny-String
In this challenge, you will determine whether a string is funny or not. To determine whether a string is funny, create a copy of the string in reverse e.g. abc > cba . Iterating through each string, compare the absolute difference in the ascii values of the characters at positions 0 and 1, 1 and 2 and so on to the end. If the list of absolute differences is the same for both strings, they are funny.

Determine whether a give string is funny. If it is, return Funny, otherwise return Not Funny.

Function Description

Complete the funnyString function in the editor below. For each test case, it should return a string, either Funny or Not Funny.

funnyString has the following parameter(s):

s: a string to test

Sample Input

2
acxz
bcxz
Sample Output

Funny
Not Funny

HackerRank: https://www.hackerrank.com/challenges/funny-string/problem
