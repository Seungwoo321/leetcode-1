<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    awesee <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/awesee                                 |-->
<!--|@home      https://github.com/awesee/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../maximum-number-of-weeks-for-which-you-can-work "Maximum Number of Weeks for Which You Can Work")
　　　　　　　　　　　　　　　　
[Next >](../count-number-of-special-subsequences "Count Number of Special Subsequences")

## [1954. Minimum Garden Perimeter to Collect Enough Apples (Medium)](https://leetcode.com/problems/minimum-garden-perimeter-to-collect-enough-apples "收集足够苹果的最小花园周长")

<p>In a garden represented as an infinite 2D grid, there is an apple tree planted at <strong>every</strong> integer coordinate. The apple tree planted at an integer coordinate <code>(i, j)</code> has <code>|i| + |j|</code> apples growing on it.</p>

<p>You will buy an axis-aligned <strong>square plot</strong> of land that is centered at <code>(0, 0)</code>.</p>

<p>Given an integer <code>neededApples</code>, return <em>the <strong>minimum perimeter</strong> of a plot such that <strong>at least</strong></em><strong> </strong><code>neededApples</code> <em>apples are <strong>inside or on</strong> the perimeter of that plot</em>.</p>

<p>The value of <code>|x|</code> is defined as:</p>

<ul>
	<li><code>x</code> if <code>x &gt;= 0</code></li>
	<li><code>-x</code> if <code>x &lt; 0</code></li>
</ul>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>
<img alt="" src="https://assets.leetcode.com/uploads/2019/08/30/1527_example_1_2.png" style="width: 442px; height: 449px;" />
<pre>
<strong>Input:</strong> neededApples = 1
<strong>Output:</strong> 8
<strong>Explanation:</strong> A square plot of side length 1 does not contain any apples.
However, a square plot of side length 2 has 12 apples inside (as depicted in the image above).
The perimeter is 2 * 4 = 8.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> neededApples = 13
<strong>Output:</strong> 16
</pre>

<p><strong>Example 3:</strong></p>

<pre>
<strong>Input:</strong> neededApples = 1000000000
<strong>Output:</strong> 5040
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= neededApples &lt;= 10<sup>15</sup></code></li>
</ul>

### Related Topics
  [[Math](../../tag/math/README.md)]
  [[Binary Search](../../tag/binary-search/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Find a formula for the number of apples inside a square with a side length L.
</details>

<details>
<summary>Hint 2</summary>
Iterate over the possible lengths of the square until enough apples are collected.
</details>