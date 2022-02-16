<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    awesee <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/awesee                                 |-->
<!--|@home      https://github.com/awesee/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](../can-you-eat-your-favorite-candy-on-your-favorite-day "Can You Eat Your Favorite Candy on Your Favorite Day?")
　　　　　　　　　　　　　　　　
[Next >](../maximum-subarray-sum-after-one-operation "Maximum Subarray Sum After One Operation")

## [1745. Palindrome Partitioning IV (Hard)](https://leetcode.com/problems/palindrome-partitioning-iv "回文串分割 IV")

<p>Given a string <code>s</code>, return <code>true</code> <em>if it is possible to split the string</em> <code>s</code> <em>into three <strong>non-empty</strong> palindromic substrings. Otherwise, return </em><code>false</code>.​​​​​</p>

<p>A string is said to be palindrome if it the same string when reversed.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;abcbdd&quot;
<strong>Output:</strong> true
<strong>Explanation: </strong>&quot;abcbdd&quot; = &quot;a&quot; + &quot;bcb&quot; + &quot;dd&quot;, and all three substrings are palindromes.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> s = &quot;bcbddxy&quot;
<strong>Output:</strong> false
<strong>Explanation: </strong>s cannot be split into 3 palindromes.
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>3 &lt;= s.length &lt;= 2000</code></li>
	<li><code>s</code>​​​​​​ consists only of lowercase English letters.</li>
</ul>

### Related Topics
  [[String](../../tag/string/README.md)]
  [[Dynamic Programming](../../tag/dynamic-programming/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Preprocess checking palindromes in O(1)
</details>

<details>
<summary>Hint 2</summary>
Note that one string is a prefix and another one is a suffix you can try brute forcing the rest
</details>