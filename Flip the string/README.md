# codeChef
You are given two binary strings AA and BB with the same length.

You may perform the following operation any number of times (including zero): pick a substring of AA with odd length and invert all the bits (change '0' to '1' or vice versa) at odd positions in this substring. For example, if we choose a substring "01011", we can convert it to "11110" (bits at odd positions are bold).

Determine the minimum number of operations required to change the string AA to the string BB.

Input
The first line of the input contains a single integer TT denoting the number of test cases. The description of TT test cases follows.
The first line of each test case contains a single string AA.
The second line contains a single string BB.
Output
For each test case, print a single line containing one integer — the minimum number of operations required.

 
Sample 1:
Input
3
100001
110111
1010
1010
000
111

output
2
0
2

Explanation:
Example case 1: Initially, AA is "100001". We choose the substring "000" between the 22-nd and 44-th character and convert it to "101".

Now AA becomes "110101". We choose the string "0" containing only the 55-th character and convert it to "1".

Finally, AA becomes "110111", which is equal to BB.

Example case 2: AA and BB are initially equal, so there is no need to perform any operation.
