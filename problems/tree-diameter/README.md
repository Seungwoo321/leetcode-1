<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/design-a-leaderboard "Design A Leaderboard")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/palindrome-removal "Palindrome Removal")

## [1245. Tree Diameter (Medium)](https://leetcode.com/problems/tree-diameter "树的直径")



### Related Topics
  [[Tree](https://github.com/openset/leetcode/tree/master/tag/tree/README.md)]
  [[Depth-first Search](https://github.com/openset/leetcode/tree/master/tag/depth-first-search/README.md)]
  [[Breadth-first Search](https://github.com/openset/leetcode/tree/master/tag/breadth-first-search/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Start at any node A and traverse the tree to find the furthest node from it, let's call it B.
</details>

<details>
<summary>Hint 2</summary>
Having found the furthest node B, traverse the tree from B to find the furthest node from it, lets call it C.
</details>

<details>
<summary>Hint 3</summary>
The distance between B and C is the tree diameter.
</details>