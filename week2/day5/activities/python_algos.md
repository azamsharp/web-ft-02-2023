# Python Algorithms

1) Create a function that takes a number as an argument, increments the number by +1 and returns the result.



Example:

```

addition(0) ➞ 1

addition(9) ➞ 10

addition(-3) ➞ -2

```


2) You are counting points for a basketball game, given the amount of 2-pointers scored and 3-pointers scored, find the final points for the team and return that value.



Example:

```
points(1, 1) ➞ 5

points(7, 5) ➞ 29

points(38, 8) ➞ 100

```

3) You have an array of random intergers. Create a function that finds the sum of the three largest numbers inside that array.


Example:

```
array = [141, 1, 17, -7, -17, -27, 18, 541, 8, 7, 7]

find_sum(array)

Output:

700

```

4) Read the prompt below for the compare triplets problem.

The rating for Alice's challenge is the triplet a = (a[0], a[1], a[2]), and the rating for Bob's challenge is the triplet b = (b[0], b[1], b[2]).

The task is to find their comparison points by comparing a[0] with b[0], a[1] with b[1], and a[2] with b[2].

If a[i] > b[i], then Alice is awarded 1 point.
If a[i] < b[i], then Bob is awarded 1 point.
If a[i] = b[i], then neither person receives a point.
Comparison points is the total points a person earned.

Given a and b, determine their respective comparison points.

Example:

```

a = [1, 2, 3]
b = [3, 2, 1]

For elements *0*, Bob is awarded a point because a[0] .

For the equal elements a[1] and b[1], no points are earned.

Finally, for elements 2, a[2] > b[2] so Alice receives a point.

The return array is [1, 1] with Alice's score first and Bob's second.

```

Function Description

compareTriplets has the following parameter(s):

int a[3]: Alice's challenge rating
int b[3]: Bob's challenge rating
Return

int[2]: Alice's score is in the first position, and Bob's score is in the second.
Input Format

The first line contains 3 space-separated integers, a[0], a[1], and a[2], the respective values in triplet a.
The second line contains 3 space-separated integers, b[0], b[1], and b[2], the respective values in triplet b.

# New!

# Advent of Code 2020 Challenges (from a real coding challenge!)

1. You are given a list. You don't know how long the list is or where it came from, but you know that two values on the list should sum to 2020. You need to find those values, then multiply them to get the answer. 

#### SAMPLE LIST

```
1977
1802
1856
1309
2003
1854
1898
1862
1857
542
1616
1599
1628
1511
1848
1623
1959
1693
1444
1211
1551
1399
2010
10
1855
1538
1869
1664
1719
1241
1875
1733
1547
1813
1531
1773
624
1336
1897
1179
1258
```

##### Did you spot that the values your program should add together are actually on lines 28 and 29? If you're stuck, don't be afraid to figure out the right answer and work back.

2. Good job! Now, you need to find out which of these passwords are considered valid. But wait, you say, what makes a password valid? Great question! A valid password in this paradigm is one that has at least 2 instances of the required letter, and it fits within the password length prompts. Someone setting up this password validation program should be able to input a custom required letter and both the maximum and minimum lengths for passwords.

#### SAMPLE LIST

```
aAA2424
wERI334
LIKO332
FKE33
dfk42p3
aaaer34
rree324
uewo43u
eoitn4lka
32095jfdsklj
eoekjlks
ljsjste
3uvdnEE
EErhjs
OEIRn3
```
