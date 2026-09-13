
https://www.youtube.com/watch?v=SxykjoG1NHU&list=PLiF6lAo--At1-wfJi5qwVxqwAsSEOkDMK&index=25


https://algo.monster/problems/dynamic_programming_intro





# Dynamic-Programming
LC, CODEWITHMIK, TUF


Dp probem with true/ false scenarios

*IMP
122. Best Time to Buy and Sell Stock II



https://leetcode.com/problems/minimum-cost-to-cut-a-stick/solutions/780880/dp-with-picture-burst-balloons/



1547. Minimum Cost to Cut a Stick
312. Burst Balloons
1000. Minimum Cost to Merge Stones
1039. Minimum Score Triangulation of Polygon


there are certain prblms  which may seem like dp:
but dp would be an overkill.

-> 3100. Water Bottles II

here we may have multiple options but until and unless i have empty bottled i dony have much of a choice..

```
when u use dp... pay attention on how many variable are changing .... 
 IF 2 varialble are chaning use 2D dp array 
 IF 3 ... use 3D 

```





When converting recursion → DP, ask:

What information changes between recursive calls?
That changing information becomes part of the DP state.

Here your recursive function is:

robHelper(root, parent)

There are two changing inputs:

root → which subtree/node we're at
parent → whether the parent was robbed

So the DP state is conceptually:

dp[root][parent]


________________________________________


Think of it this way:

1. First ask: what does my state depend on?

If:

dp[i] depends on dp[i-1]

go left → right.

Examples:

House Robber
LIS
LCS
Coin Change
0/1 Knapsack


Because you're using information from the past.

2. If:
dp[i] depends on dp[i+1] or dp[i+2]

go right → left.

Examples:

House Robber (suffix formulation)
Stock problems with future-state recursion
