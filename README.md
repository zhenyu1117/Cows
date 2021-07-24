# Cows
POJ Contest,Author:Mathematica@ZSU 
Cows
Time Limit: 3000MS		Memory Limit: 65536K
Total Submissions: 27431		Accepted: 8996
Description

Farmer John's cows have discovered that the clover growing along the ridge of the hill (which we can think of as a one-dimensional number line) in his field is particularly good.

Farmer John has N cows (we number the cows from 1 to N). Each of Farmer John's N cows has a range of clover that she particularly likes (these ranges might overlap). The ranges are defined by a closed interval [S,E].

But some cows are strong and some are weak. Given two cows: cowi and cowj, their favourite clover range is [Si, Ei] and [Sj, Ej]. If Si <= Sj and Ej <= Ei and Ei - Si > Ej - Sj, we say that cowi is stronger than cowj.

For each cow, how many cows are stronger than her? Farmer John needs your help!
Input

The input contains multiple test cases.
For each test case, the first line is an integer N (1 <= N <= 105), which is the number of cows. Then come N lines, the i-th of which contains two integers: S and E(0 <= S < E <= 105) specifying the start end location respectively of a range preferred by some cow. Locations are given as distance from the start of the ridge.

The end of the input contains a single 0.
Output

For each test case, output one line containing n space-separated integers, the i-th of which specifying the number of cows that are stronger than cowi.
Sample Input

3
1 2
0 3
3 4
0
Sample Output

1 0 0
Hint

Huge input and output,scanf and printf is recommended.
Source

POJ Contest,Author:Mathematica@ZSU
