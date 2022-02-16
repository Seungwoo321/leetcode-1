<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    awesee <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/awesee                                 |-->
<!--|@home      https://github.com/awesee/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../maximum-height-by-stacking-cuboids "Maximum Height by Stacking Cuboids ")
　　　　　　　　　　　　　　　　
[Next >](../daily-leads-and-partners "Daily Leads and Partners")

## [1692. Count Ways to Distribute Candies (Hard)](https://leetcode.com/problems/count-ways-to-distribute-candies "计算分配糖果的不同方式")



### Related Topics
  [[Dynamic Programming](../../tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Try to define a recursive approach. For the ith candies, there will be one of the two following cases:
</details>

<details>
<summary>Hint 2</summary>
If the i - 1 previous candies are already distributed into k bags for the ith candy, you can have k * dp[n - 1][k] ways to distribute the ith candy. We need then to solve the state of (n - 1, k).
</details>

<details>
<summary>Hint 3</summary>
If the i - 1 previous candies are already distributed into k - 1 bags for the ith candy, you can have dp[n - 1][k - 1] ways to distribute the ith candy. We need then to solve the state of (n - 1, k - 1).
</details>

<details>
<summary>Hint 4</summary>
This approach will be too slow and will traverse some states more than once. We should use memoization to make the algorithm efficient.
</details>