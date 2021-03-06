# 打卡

每天完成自己的题目后打卡。

Victor 打卡

| 姓名 | 日期 | 打卡 | 备注
| --- | --- | --- | --- |
| victor | 2018.3.20 | x | --- |

# Ruby LeetCode

做这些题目的不是为了要去应聘这些公司，而是为了锻炼一下自己的算法和编程能力。所以只要会 `if, else, for, break, next, while, until, array, hash` 就可以刷了。其它的边刷边学就行。

## 前言

LeetCode的题大致分成两类：

基础算法的知识。这些题里面有大量的算法题，解这些题都是有套路的，不是用递归（深度优先DFS，广度优先BFS），就是要用动态规划（Dynamic Programming），或是二分查找（Binary Search），或是回溯（Back tracing），或是分治法（Divide and Conquer），还有大量的对 树，数组、链表、字符串 和 hash 的操作。**通过做这些题能让你对这些最基础的算法的思路有非常扎实的了解和训练。**

编程题。比如：atoi，strstr，add two num，括号匹配，字符串乘法，通配符匹配，文件路径简化，Text Justification，反转单词等等，这些题的 Edge Case, Corner Case 有很多。这些题需要你想清楚了再干，只要你稍有疏忽，就会有几个 case 让你痛不欲生，而且一不小心就会让你的代码会写得又臭又长，无法阅读。**通过做这些题，可以非常好的训练你对各种情况的考虑，以及你对程序代码组织的掌控（其实就是其中的状态变量）**

摘自 [LEETCODE 编程训练](https://coolshell.cn/articles/12052.html)

## 路线

1. 头一次刷，先把这五个 tag 做了：`array，string，tree，linkedlist，math` 其它的千万别按 tag 刷（帮助巩固数据结构，还可以自己归纳某种数据结构的全部技巧）
2. 每个 tag 内部就按照 easy-medium-hard 的顺序做
3. 顺序也可以参考下图

![](https://pic2.zhimg.com/80/0281c7e9d5111554f9efd2b595cd017d_hd.jpg)

## 答题步骤

1. 正确性：能在纸上跑代码，尽量做到写之前先有完整的思路，考虑清楚各种边界情况，测试先行
2. 对良好的代码风格：简洁明了，变量命名规范，模块之间疏落有致
3. 合适的时间空间复杂度：好的解法，时间空间复杂度通常更低
4. 对边界数据和海量数据的关注：
  * 常规，用来检查算法基本正确，
  * 边界，用来检查是否细心不掉边界坑，
  * 海量，用来检查代码的时间空间复杂度有没有超出限制。
5. 小技巧：诸如能用位运算就不要用乘除法，之类的。小技巧能给你的代码，增添一点逼格。

## 准备工作

推荐在答题前和答题的过程中阅读如下书籍：

* 《算法图解》简单好读，涵盖了基础算法和数据结构，如果大学那点知识都忘光了，很适合从这本捡起来，而且 Kindle 的排版不错。
* 《算法的乐趣》也是一本从0基础开始复习的算法书
* 《算法 第4版》这本就很经典了，也很难在1，2周内读完
* 《程序员的数学1，2，3》从初中数学开始补
* 《编程珠玑》

专门的解答书：

* 《最优解》
* 《剑指 offer》

## 网站

* [leetcode](https://leetcode.com/)
* [lintcode](http://www.lintcode.com/) 题目覆盖：人工智能、大数据、算法。只能使用 GO/C/Java/JavaScript/Python 答题
* [千里码](http://www.qlcoder.com/)
* [LINTCODE / LEETCODE 参考答案查询](http://www.jiuzhang.com/solution/)
* [Python / C++ 11 Solutions of All LeetCode Questions](https://github.com/kamyu104/LeetCode)
* [LeetCode solutions in C++ 11 and Python3](https://github.com/pezy/LeetCode)
