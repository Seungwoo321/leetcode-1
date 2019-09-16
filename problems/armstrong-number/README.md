<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/largest-unique-number "Largest Unique Number")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/connecting-cities-with-minimum-cost "Connecting Cities With Minimum Cost")

## 1134. Armstrong Number (Easy)



### Related Topics
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Check if the given k-digit number equals the sum of the k-th power of it's digits.
</details>

<details>
<summary>Hint 2</summary>
How to compute the sum of the k-th power of the digits of a number ? Can you divide the number into digits using division and modulus operations ?
</details>

<details>
<summary>Hint 3</summary>
You can find the least significant digit of a number by taking it modulus 10. And you can remove it by dividing the number by 10 (integer division). Once you have a digit, you can raise it to the power of k and add it to the sum.
</details>