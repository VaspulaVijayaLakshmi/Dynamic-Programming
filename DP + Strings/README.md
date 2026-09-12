https://leetcode.com/discuss/post/4861127/lcs-and-its-patterns-10-similar-question-4b7y/



| Problem / Pattern                 |            Recursion calls | Memoization | Tabulation |
| --------------------------------- | -------------------------: | ----------: | ---------: |
| **LCS**                           |               `O(2^(n+m))` |     `O(nm)` |    `O(nm)` |
| **Longest Common Substring**      |              `O(2^(n+m))`* |     `O(nm)` |    `O(nm)` |
| **Longest Repeating Subsequence** |               `O(2^(n+m))` |     `O(n²)` |    `O(n²)` |
| **Distinct Subsequences**         |                   `O(2^n)` |     `O(nm)` |    `O(nm)` |
| **Edit Distance**                 |               `O(3^(n+m))` |     `O(nm)` |    `O(nm)` |
| **Delete Operation 2 Strings**    |               `O(2^(n+m))` |     `O(nm)` |    `O(nm)` |
| **Min Insert + Delete**           |                          — |     `O(nm)` |    `O(nm)` |
| **Shortest Common Supersequence** |                          — |     `O(nm)` |    `O(nm)` |
| **Palindrome Subsequence / LPS**  |                   `O(2^n)` |     `O(n²)` |    `O(n²)` |
| **Palindrome Substring**          | usually `O(2^n)` recursion |     `O(n²)` |    `O(n²)` |
| **Longest Palindromic Substring** |                          — |     `O(n²)` |    `O(n²)` |
| **Wildcard Matching**             |               `O(2^(n+m))` |     `O(nm)` |    `O(nm)` |
| **Regex Matching**                |               `O(2^(n+m))` |     `O(nm)` |    `O(nm)` |
| **Interleaving String**           |               `O(2^(n+m))` |     `O(nm)` |    `O(nm)` |

