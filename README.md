# divideChocolatebar
Determine how many ways to divide the chocolate.

Two children, Lily and Ron, want to share a chocolate bar. Each of the squares has an integer on it.

Lily decides to share a contiguous segment of the bar selected such that:

The length of the segment matches Ron's birth month, and,
The sum of the integers on the squares is equal to his birth day.
Determine how many ways she can divide the chocolate.

Example



Lily wants to find segments summing to Ron's birth day,  with a length equalling his birth month, . In this case, there are two segments meeting her criteria:  and .

Function Description

Complete the birthday function in the editor below.

birthday has the following parameter(s):

int s[n]: the numbers on each of the squares of chocolate
int d: Ron's birth day
int m: Ron's birth month
Returns

int: the number of ways the bar can be divided
Input Format

The first line contains an integer , the number of squares in the chocolate bar.
The second line contains  space-separated integers , the numbers on the chocolate squares where .
The third line contains two space-separated integers,  and , Ron's birth day and his birth month.

Constraints

, where ()


![image](https://user-images.githubusercontent.com/43896389/217681151-b495cc67-2c35-4301-b51a-e75859637ba7.png)
![image](https://user-images.githubusercontent.com/43896389/217681215-d7c8147f-bf3f-43c0-b7a1-197488ea2059.png)

