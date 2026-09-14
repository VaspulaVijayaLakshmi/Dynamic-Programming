
# Dynamic-Programming
LC, CODEWITHMIK, TUF

https://www.youtube.com/watch?v=SxykjoG1NHU&list=PLiF6lAo--At1-wfJi5qwVxqwAsSEOkDMK&index=25

https://algo.monster/problems/dynamic_programming_intro

https://leetcode.com/problems/minimum-cost-to-cut-a-stick/solutions/780880/dp-with-picture-burst-balloons/


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


___________________________________

Series 

Jump Game

Jump Game → greedy reachability
Jump Game II → minimum jumps
Jump Game III → graph/BFS/DFS flavor
Jump Game VII → DP + sliding window

House Robber

Robber I → 1D DP
Robber II → circular DP
Robber III → tree DP
Variants → state transition recognition

Stock

Stock I → simple greedy
Stock II → unlimited transactions
Stock III/IV → transaction-state DP
Cooldown → state DP
Fee → state DP

Gas Station

Basic → greedy
