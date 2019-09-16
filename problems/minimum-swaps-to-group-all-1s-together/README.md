<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/check-if-a-number-is-majority-element-in-a-sorted-array "Check If a Number Is Majority Element in a Sorted Array")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/analyze-user-website-visit-pattern "Analyze User Website Visit Pattern")

## 1151. Minimum Swaps to Group All 1's Together (Medium)



### Related Topics
  [[Array](https://github.com/openset/leetcode/tree/master/tag/array/README.md)]
  [[Sliding Window](https://github.com/openset/leetcode/tree/master/tag/sliding-window/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
How many 1's should be grouped together ? Is not a fixed number?
</details>

<details>
<summary>Hint 2</summary>
Yeah it's just the number of 1's the whole array has. Let's name this number as ones
</details>

<details>
<summary>Hint 3</summary>
Every subarray of size of ones, needs some number of swaps to reach, Can you find the number of swaps needed to group all 1's in this subarray?
</details>

<details>
<summary>Hint 4</summary>
It's the number of zeros in that subarray.
</details>

<details>
<summary>Hint 5</summary>
Do you need to count the number of zeros all over again for every position ?
</details>

<details>
<summary>Hint 6</summary>
Use Sliding Window technique.
</details>