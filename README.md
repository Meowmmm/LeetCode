

| TOP  | 题目                                                         | 说明                                                         | flag                     |
| ---- | ------------------------------------------------------------ | ------------------------------------------------------------ | ------------------------ |
| TOP  | [1. 两数之和](https://leetcode-cn.com/problems/two-sum/)     | hash_map                                                     | STL                      |
| TOP  | [2. 两数相加](https://leetcode-cn.com/problems/add-two-numbers/) | 链表操作                                                     | 链表                     |
| TOP  | [3. 无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/) | 标记每次的begin，一旦发现重复，则需要从这个字母上一次出现的地方的下一个字符为begin | 数组                     |
| TOP  | [4. 寻找两个正序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/) | 两指针o(n)遍历<br />变形二分查找，第一个数组找cut点，第二个数组的cut点位置可以计算得到 |                          |
| TOP  | [5. 最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring/) | 1、扩充法，从mid向两边遍历<br />2、马拉车算法                | **TODO**<br />马拉车算法 |
| TOP  | [7. 整数反转](https://leetcode-cn.com/problems/reverse-integer/) | unsigned int 判断溢出的小trick                               |                          |
| TOP  | [11. 盛最多水的容器](https://leetcode-cn.com/problems/container-with-most-water/) | 两端向中间逼近找答案                                         |                          |
| TOP  | [19. 删除链表的倒数第N个节点](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/) |                                                              | fakeHead + 快慢指针      |
|      | [24. 两两交换链表中的节点](https://leetcode-cn.com/problems/swap-nodes-in-pairs/) | 4指针，遍历处理                                              |                          |
| bos  | [25. K 个一组翻转链表](https://leetcode-cn.com/problems/reverse-nodes-in-k-group/) | 一遍遍来                                                     |                          |
|      | [26. 删除排序数组中的重复项](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-array/) |                                                              | 双指针                   |
|      | [27. 移除元素](https://leetcode-cn.com/problems/remove-element/) |                                                              | 双指针                   |
| TOP  | [29. 两数相除](https://leetcode-cn.com/problems/divide-two-integers/) | 傻逼题，用long long不香？                                    | 各种溢出边界             |
|      | [34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/) | 二分查找                                                     | 二分查找                 |
| TOP  | [35. 搜索插入位置](https://leetcode-cn.com/problems/search-insert-position/) | 二分查找                                                     | 二分查找                 |
|      | [31. 下一个排列](https://leetcode-cn.com/problems/next-permutation/) | STL真香                                                      | Next_permutation         |
|      | [32. 最长有效括号](https://leetcode-cn.com/problems/longest-valid-parentheses/) | Stack, trick                                                 | trick                    |
| TOP  | [38. 外观数列](https://leetcode-cn.com/problems/count-and-say/) | 类似斐波拉契，一层层处理                                     | 字符串处理               |
| TOP  | [39. 组合总和](https://leetcode-cn.com/problems/combination-sum/) | 完全背包                                                     | dfs                      |
|      | [41. 缺失的第一个正数](https://leetcode-cn.com/problems/first-missing-positive/) |                                                              | Trick                    |
| TOP  | [46. 全排列](https://leetcode-cn.com/problems/permutations/) | next_permutation                                             | dfs or stl               |
|      | [47. 全排列 II](https://leetcode-cn.com/problems/permutations-ii/) | next_permutation                                             | dfs or stl               |
| TOP  | [49. 字母异位词分组](https://leetcode-cn.com/problems/group-anagrams/) | 排序后的字符串作为key，map汇聚                               | STL                      |
| TOP  | [50. Pow(x, n)](https://leetcode-cn.com/problems/powx-n/)    | 超时警告⚠️，指数增长                                          |                          |
|      | [51. N 皇后](https://leetcode-cn.com/problems/n-queens/)     | 同下                                                         | DFS+位运算               |
|      | [52. N皇后 II](https://leetcode-cn.com/problems/n-queens-ii/) | n & -n得到最低位的1的位置<br />n &= (n-1): 把最低位1置0      | DFS+位运算               |
| 剑指 | [53. 最大子序和](https://leetcode-cn.com/problems/maximum-subarray/) |                                                              | O(N)                     |
| TOP  | [56. 合并区间](https://leetcode-cn.com/problems/merge-intervals/) |                                                              |                          |
|      | [57. 插入区间](https://leetcode-cn.com/problems/insert-interval/) | 原理同上                                                     | 56变形                   |
|      | [58. 最后一个单词的长度](https://leetcode-cn.com/problems/length-of-last-word/) |                                                              | 智障题目                 |
|      | [61. 旋转链表](https://leetcode-cn.com/problems/rotate-list/) | 两次遍历                                                     | 链表                     |
|      | [64. 最小路径和](https://leetcode-cn.com/problems/minimum-path-sum/) |                                                              | dp                       |
| TOP  | [69. x 的平方根](https://leetcode-cn.com/problems/sqrtx/)    | 溢出警告⚠️                                                    | 二分                     |
|      | [70. 爬楼梯](https://leetcode-cn.com/problems/climbing-stairs/) | dp[n] = dp[n-1] + dp[n-2]                                    | dp                       |
|      | [72. 编辑距离](https://leetcode-cn.com/problems/edit-distance/) | 二维dp                                                       | Dp                       |
|      | [74. 搜索二维矩阵](https://leetcode-cn.com/problems/search-a-2d-matrix/) |                                                              | 二分                     |
| TOP  | [75. 颜色分类](https://leetcode-cn.com/problems/sort-colors/) |                                                              | 排序                     |
| TOP  | [76. 最小覆盖子串](https://leetcode-cn.com/problems/minimum-window-substring/) |                                                              | 滑动窗口                 |
| TOP  | [77. 组合](https://leetcode-cn.com/problems/combinations/)   | 本位置【选中】、【不选中】                                   | dfs                      |
| TOP  | [78. 子集](https://leetcode-cn.com/problems/subsets/)        | 每个位置可选可不选                                           | dfs                      |
| TOP  | [79. 单词搜索](https://leetcode-cn.com/problems/word-search/) |                                                              | Dfs                      |
|      | [81. 搜索旋转排序数组 II](https://leetcode-cn.com/problems/search-in-rotated-sorted-array-ii/) |                                                              | 二分变形                 |
|      | [82. 删除排序链表中的重复元素 II](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list-ii/) |                                                              | 链表                     |
|      | [83. 删除排序链表中的重复元素](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list/) |                                                              | 智障题                   |
|      | [88. 合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/) |                                                              |                          |
|      | [89. 格雷编码](https://leetcode-cn.com/problems/gray-code/)  |                                                              | 数学规律                 |
|      | [90. 子集 II](https://leetcode-cn.com/problems/subsets-ii/)  |                                                              | dfs                      |
| TOP  | [91. 解码方法](https://leetcode-cn.com/problems/decode-ways/) | 26进制+dp                                                    | dp                       |
|      | [98. 验证二叉搜索树](https://leetcode-cn.com/problems/validate-binary-search-tree/) |                                                              |                          |
| TOP  | [102. 二叉树的层序遍历](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/) |                                                              | queue                    |
| TOP  | [103. 二叉树的锯齿形层次遍历](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/) |                                                              | Queue + reverse          |
| TOP  | [104. 二叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/) |                                                              | 递归                     |
| TOP  | [105. 从前序与中序遍历序列构造二叉树](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/) |                                                              | 递归                     |
| TOP  | [108. 将有序数组转换为二叉搜索树](https://leetcode-cn.com/problems/convert-sorted-array-to-binary-search-tree/) |                                                              | 不断递归二分             |
|      | [111. 二叉树的最小深度](https://leetcode-cn.com/problems/minimum-depth-of-binary-tree/) |                                                              | 树的层次遍历             |
|      | [112. 路径总和](https://leetcode-cn.com/problems/path-sum/)  |                                                              | 递归                     |
|      | [113. 路径总和 II](https://leetcode-cn.com/problems/path-sum-ii/) |                                                              | DFS+递归                 |
|      | [114. 二叉树展开为链表](https://leetcode-cn.com/problems/flatten-binary-tree-to-linked-list/) |                                                              | 递归                     |
|      | [116. 填充每个节点的下一个右侧节点指针](https://leetcode-cn.com/problems/populating-next-right-pointers-in-each-node/) |                                                              | 树的层次遍历<br />递归   |
|      | [117. 填充每个节点的下一个右侧节点指针 II](https://leetcode-cn.com/problems/populating-next-right-pointers-in-each-node-ii/) |                                                              | 树的层次遍历<br />递归   |
|      | [118. 杨辉三角](https://leetcode-cn.com/problems/pascals-triangle/) |                                                              | 智障题                   |
|      | [119. 杨辉三角 II](https://leetcode-cn.com/problems/pascals-triangle-ii/) |                                                              | 数学                     |
| TOP  | [121. 买卖股票的最佳时机](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/) |                                                              | 智障题                   |
| TOP  | [122. 买卖股票的最佳时机 II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/) | 所有连续升序子序列首尾差的总和                               |                          |
| TOP  | [124. 二叉树中的最大路径和](https://leetcode-cn.com/problems/binary-tree-maximum-path-sum/) |                                                              | 递归                     |
|      | [125. 验证回文串](https://leetcode-cn.com/problems/valid-palindrome/) | 字符串操作+边界处理                                          | 字符串操作               |
| TOP  | [127. 单词接龙](https://leetcode-cn.com/problems/word-ladder/) | 双端bfs加快查找速度                                          | BFS                      |
|      | [129. 求根到叶子节点数字之和](https://leetcode-cn.com/problems/sum-root-to-leaf-numbers/) |                                                              | 树，递归                 |
| TOP  | [130. 被围绕的区域](https://leetcode-cn.com/problems/surrounded-regions/) |                                                              | bfs                      |
|      | [134. 加油站](https://leetcode-cn.com/problems/gas-station/) |                                                              | 贪心                     |
|      | [135. 分发糖果](https://leetcode-cn.com/problems/candy/)     |                                                              | 贪心                     |
| TOP  | [139. 单词拆分](https://leetcode-cn.com/problems/word-break/) |                                                              | DFS+MEM                  |
| TOP  | [141. 环形链表](https://leetcode-cn.com/problems/linked-list-cycle/) | 快慢指针                                                     | 快慢指针                 |
|      | [142. 环形链表 II](https://leetcode-cn.com/problems/linked-list-cycle-ii/) | slow = head，fast = fast->next<br />下次相遇就是找到了链表的环入口 | 快慢指针                 |
|      | [143. 重排链表](https://leetcode-cn.com/problems/reorder-list/) |                                                              | vector保存每个节点       |
|      | [144. 二叉树的前序遍历](https://leetcode-cn.com/problems/binary-tree-preorder-traversal/) |                                                              | 闭着眼都能写             |
| TOP  | [146. LRU缓存机制](https://leetcode-cn.com/problems/lru-cache/) | list + unordered_map                                         | List + hash              |
| TOP  | [150. 逆波兰表达式求值](https://leetcode-cn.com/problems/evaluate-reverse-polish-notation/) | Stack                                                        | stack                    |
|      | [154. 寻找旋转排序数组中的最小值 II](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array-ii/) |                                                              | 二分                     |
|      | [155. 最小栈](https://leetcode-cn.com/problems/min-stack/)   | 双stack，其中一个stack存当前最小值。                         | 设计思想                 |
| TOP  | [160. 相交链表](https://leetcode-cn.com/problems/intersection-of-two-linked-lists/) | 1、第一遍求长度差，第二遍找交点<br />2、第一个链表尾巴指向第二个，相遇就是交点 |                          |
| TOP  | [162. 寻找峰值](https://leetcode-cn.com/problems/find-peak-element/) |                                                              | 分治                     |
| TOP  | [166. 分数到小数](https://leetcode-cn.com/problems/fraction-to-recurring-decimal/) |                                                              | Map                      |
|      | [167. 两数之和 II - 输入有序数组](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/) | 两头向中间夹击                                               | 双指针                   |
|      | [168. Excel表列名称](https://leetcode-cn.com/problems/excel-sheet-column-title/) |                                                              | int -> excel             |
| TOP  | [169. 多数元素](https://leetcode-cn.com/problems/majority-element/) | 消除思想                                                     | trick                    |
| TOP  | [171. Excel表列序号](https://leetcode-cn.com/problems/excel-sheet-column-number/) | 26进制+字符串处理                                            | 傻瓜题                   |
|      | [172. 阶乘后的零](https://leetcode-cn.com/problems/factorial-trailing-zeroes/) | 因子5的个数                                                  | 数学                     |
| SQL  | [175. 组合两个表](https://leetcode-cn.com/problems/combine-two-tables/) |                                                              | left join                |
| SQL  | [176. 第二高的薪水](https://leetcode-cn.com/problems/second-highest-salary/) |                                                              | max                      |
| SQL  | [181. 超过经理收入的员工](https://leetcode-cn.com/problems/employees-earning-more-than-their-managers/) |                                                              | Select from select       |
| SQL  | [182. 查找重复的电子邮箱](https://leetcode-cn.com/problems/duplicate-emails/) |                                                              | Group by having count    |
| SQL  | [183. 从不订购的客户](https://leetcode-cn.com/problems/customers-who-never-order/) |                                                              | NOT IN                   |
|      | [189. 旋转数组](https://leetcode-cn.com/problems/rotate-array/) |                                                              | trick                    |
| TOP  | [190. 颠倒二进制位](https://leetcode-cn.com/problems/reverse-bits/) | 位运算： <<、>>、&<br />result左移，ori_num右移              | 位运算                   |
| TOP  | [191. 位1的个数](https://leetcode-cn.com/problems/number-of-1-bits/) | 位运算：>>、&<br />原数右移32次判断最低位即可                | 位运算<br />bitset       |
| TOP  | [198. 打家劫舍](https://leetcode-cn.com/problems/house-robber/) | dp[i] = max(dp[i - 1], n[i] + dp[i - 2]);                    | Dp                       |
| TOP  | [200. 岛屿数量](https://leetcode-cn.com/problems/number-of-islands/) |                                                              | Dfs                      |
| TOP  | [202. 快乐数](https://leetcode-cn.com/problems/happy-number/) | 有限次穷举<br />模拟快慢指针判断有环                         | <-                       |
|      | [203. 移除链表元素](https://leetcode-cn.com/problems/remove-linked-list-elements/) |                                                              | 智障题                   |
| TOP  | [204. 计数质数](https://leetcode-cn.com/problems/count-primes/) |                                                              | 鄂尔多塞筛法             |
|      | [205. 同构字符串](https://leetcode-cn.com/problems/isomorphic-strings/) |                                                              | 智障题                   |
| TOP  | [206. 反转链表](https://leetcode-cn.com/problems/reverse-linked-list/) | 三指针遍历                                                   | 三指针                   |
| TOP  | [207. 课程表](https://leetcode-cn.com/problems/course-schedule/) |                                                              | 图，检测环               |
| TOP  | [208. 实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree/) | 前缀树                                                       | 前缀树                   |
| TOP  | [210. 课程表 II](https://leetcode-cn.com/problems/course-schedule-ii/) |                                                              | BFS                      |
|      | [213. 打家劫舍 II](https://leetcode-cn.com/problems/house-robber-ii/) |                                                              | dp                       |
|      | [215. 数组中的第K个最大元素](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/) |                                                              | 排序                     |
|      | [216. 组合总和 III](https://leetcode-cn.com/problems/combination-sum-iii/) | dfs                                                          | dfs                      |
|      | [221. 最大正方形](https://leetcode-cn.com/problems/maximal-square/) |                                                              | dfs 、dp                 |
|      | [225. 用队列实现栈](https://leetcode-cn.com/problems/implement-stack-using-queues/) |                                                              | STL                      |
| TOP  | [227. 基本计算器 II](https://leetcode-cn.com/problems/basic-calculator-ii/) | 第一次遍历解析字符串、第二次遍历进行计算                     | 字符串处理    STL queue  |
|      | [228. 汇总区间](https://leetcode-cn.com/problems/summary-ranges/) |                                                              | 区间                     |
|      | [229. 求众数 II](https://leetcode-cn.com/problems/majority-element-ii/) |                                                              | 摩尔投票法               |
| TOP  | [230. 二叉搜索树中第K小的元素](https://leetcode-cn.com/problems/kth-smallest-element-in-a-bst/) | 树的中序遍历                                                 | 树                       |
|      | [231. 2的幂](https://leetcode-cn.com/problems/power-of-two/) | 计算int中1的个数==1即可                                      | 位运算                   |
|      | [232. 用栈实现队列](https://leetcode-cn.com/problems/implement-queue-using-stacks/) |                                                              | STL                      |
| TOP  | [234. 回文链表](https://leetcode-cn.com/problems/palindrome-linked-list/) | 快慢指针+反转前半部分链表                                    | 链表                     |
|      | [235. 二叉搜索树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-search-tree/) | 二叉搜索树的特性<br />同下                                   | 树                       |
| TOP  | [236. 二叉树的最近公共祖先](https://leetcode-cn.com/problems/lowest-common-ancestor-of-a-binary-tree/) | 递归<br />树的后续遍历                                       | 树                       |
| TOP  | [237. 删除链表中的节点](https://leetcode-cn.com/problems/delete-node-in-a-linked-list/) | cur复制next node的值，释放next node                          | 值拷贝                   |
| TOP  | [238. 除自身以外数组的乘积](https://leetcode-cn.com/problems/product-of-array-except-self/) | 考虑多种情况：有0、1个0、多个0                               | 数学问题                 |
| TOP  | [240. 搜索二维矩阵 II](https://leetcode-cn.com/problems/search-a-2d-matrix-ii/) | 从右上或者左下开始搜索                                       | 矩阵                     |
| TOP  | [242. 有效的字母异位词](https://leetcode-cn.com/problems/valid-anagram/) | 统计每个字母的count是否一致即可                              | 字符串                   |
|      | [257. 二叉树的所有路径](https://leetcode-cn.com/problems/binary-tree-paths/) |                                                              | 树 + 递归                |
|      | [258. 各位相加](https://leetcode-cn.com/problems/add-digits/) | 每次其实是减9的倍数                                          | 数学问题                 |
| TOP  | [268. 缺失数字](https://leetcode-cn.com/problems/missing-number/) | 减差 OR 位运算                                               | 位运算                   |
|      | [278. 第一个错误的版本](https://leetcode-cn.com/problems/first-bad-version/) | 二分找突变的点                                               | 二分                     |
| TOP  | [279. 完全平方数](https://leetcode-cn.com/problems/perfect-squares/) | dp                                                           | dp                       |
|      | [283. 移动零](https://leetcode-cn.com/problems/move-zeroes/) |                                                              | 双指针                   |
|      | [284. 顶端迭代器](https://leetcode-cn.com/problems/peeking-iterator/) | 拷贝构造函数                                                 | 迭代器                   |
| TOP  | [287. 寻找重复数](https://leetcode-cn.com/problems/find-the-duplicate-number/) |                                                              | **TODO**                 |
| TOP  | [289. 生命游戏](https://leetcode-cn.com/problems/game-of-life/) |                                                              | 傻逼题                   |
|      | [290. 单词规律](https://leetcode-cn.com/problems/word-pattern/) |                                                              | 字符串split + map        |
| 100  | [297. 二叉树的序列化与反序列化](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree/) |                                                              | 前序遍历                 |
| TOP  | [300. 最长上升子序列](https://leetcode-cn.com/problems/longest-increasing-subsequence/) |                                                              | DP                       |
|      | [303. 区域和检索 - 数组不可变](https://leetcode-cn.com/problems/range-sum-query-immutable/) |                                                              | 数据结构设计             |
|      | [304. 二维区域和检索 - 矩阵不可变](https://leetcode-cn.com/problems/range-sum-query-2d-immutable/) |                                                              | 上题变形                 |
|      | [309. 最佳买卖股票时机含冷冻期](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/) |                                                              | dp，三种状态             |
|      | [310. 最小高度树](https://leetcode-cn.com/problems/minimum-height-trees/) |                                                              | 树，bfs                  |
| TOP  | [322. 零钱兑换](https://leetcode-cn.com/problems/coin-change/) | 完全背包、dp（用stack会死循环）                              | 完全背包、DP             |
| TOP  | [324. 摆动排序 II](https://leetcode-cn.com/problems/wiggle-sort-ii/) |                                                              |                          |
| TOP  | [326. 3的幂](https://leetcode-cn.com/problems/power-of-three/) |                                                              |                          |
| TOP  | [328. 奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list/) |                                                              | 指针操作                 |
| TOP  | [334. 递增的三元子序列](https://leetcode-cn.com/problems/increasing-triplet-subsequence/) |                                                              |                          |
|      | [337. 打家劫舍 III](https://leetcode-cn.com/problems/house-robber-iii/) |                                                              | dp                       |
|      | [338. 比特位计数](https://leetcode-cn.com/problems/counting-bits/) |                                                              | 位运算                   |
| TOP  | [341. 扁平化嵌套列表迭代器](https://leetcode-cn.com/problems/flatten-nested-list-iterator/) |                                                              |                          |
| TOP  | [344. 反转字符串](https://leetcode-cn.com/problems/reverse-string/) |                                                              | 头尾交换                 |
|      | [345. 反转字符串中的元音字母](https://leetcode-cn.com/problems/reverse-vowels-of-a-string/) |                                                              | 双指针                   |
| TOP  | [347. 前 K 个高频元素](https://leetcode-cn.com/problems/top-k-frequent-elements/) | 小顶堆                                                       | priority_queue           |
|      | [349. 两个数组的交集](https://leetcode-cn.com/problems/intersection-of-two-arrays/) |                                                              | Set                      |
|      | [354. 俄罗斯套娃信封问题](https://leetcode-cn.com/problems/russian-doll-envelopes/) |                                                              | 300变种，dp              |
|      | [367. 有效的完全平方数](https://leetcode-cn.com/problems/valid-perfect-square/) |                                                              | 二分                     |
| TOP  | [371. 两整数之和](https://leetcode-cn.com/problems/sum-of-two-integers/) |                                                              | 位运算                   |
| TOP  | [380. 常数时间插入、删除和获取随机元素](https://leetcode-cn.com/problems/insert-delete-getrandom-o1/) | unordered_map + vector联动管理数据                           | 数据结构设计             |
|      | [381. O(1) 时间插入、删除和获取随机元素 - 允许重复](https://leetcode-cn.com/problems/insert-delete-getrandom-o1-duplicates-allowed/) | Unordered_map + unordered_set + vector                       | 数据结构设计             |
|      | [383. 赎金信](https://leetcode-cn.com/problems/ransom-note/) | 字符统计                                                     | 智障题                   |
| TOP  | [384. 打乱数组](https://leetcode-cn.com/problems/shuffle-an-array/) | 随机数，两数交换                                             |                          |
|      | [389. 找不同](https://leetcode-cn.com/problems/find-the-difference/) | 同 383                                                       | 智障题                   |
|      | [392. 判断子序列](https://leetcode-cn.com/problems/is-subsequence/) | 遍历找子串字符就行                                           |                          |
|      | [394. 字符串解码](https://leetcode-cn.com/problems/decode-string/) |                                                              | stack                    |
|      | [395. 至少有K个重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-with-at-least-k-repeating-characters/) |                                                              | 分治                     |
|      | [399. 除法求值](https://leetcode-cn.com/problems/evaluate-division/) |                                                              | 并查集 + bfs             |
|      | [404. 左叶子之和](https://leetcode-cn.com/problems/sum-of-left-leaves/) |                                                              | 递归                     |
|      | [409. 最长回文串](https://leetcode-cn.com/problems/longest-palindrome/) |                                                              | 智障题目                 |
| TOP  | [412. Fizz Buzz](https://leetcode-cn.com/problems/fizz-buzz/) |                                                              | 智障题目                 |
|      | [415. 字符串相加](https://leetcode-cn.com/problems/add-strings/) |                                                              | 字符串处理               |
|      | [417. 太平洋大西洋水流问题](https://leetcode-cn.com/problems/pacific-atlantic-water-flow/) | 四个方向dfs                                                  | DFS                      |
|      | [424. 替换后的最长重复字符](https://leetcode-cn.com/problems/longest-repeating-character-replacement/) |                                                              | 滑动窗口                 |
|      | [434. 字符串中的单词数](https://leetcode-cn.com/problems/number-of-segments-in-a-string/) |                                                              | 智障题目                 |
|      | [435. 无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/) |                                                              | 贪心                     |
|      | [441. 排列硬币](https://leetcode-cn.com/problems/arranging-coins/) |                                                              | 智障题目                 |
|      | [448. 找到所有数组中消失的数字](https://leetcode-cn.com/problems/find-all-numbers-disappeared-in-an-array/) |                                                              | 位运算                   |
|      | [451. 根据字符出现频率排序](https://leetcode-cn.com/problems/sort-characters-by-frequency/) |                                                              | 桶排序                   |
|      | [452. 用最少数量的箭引爆气球](https://leetcode-cn.com/problems/minimum-number-of-arrows-to-burst-balloons/) |                                                              | 贪心                     |
|      | [455. 分发饼干](https://leetcode-cn.com/problems/assign-cookies/) |                                                              | 贪心                     |
|      | [460. LFU 缓存](https://leetcode-cn.com/problems/lfu-cache/) |                                                              | map+set+自定义比较       |
|      | [461. 汉明距离](https://leetcode-cn.com/problems/hamming-distance/) |                                                              | 位运算                   |
|      | [463. 岛屿的周长](https://leetcode-cn.com/problems/island-perimeter/) | 数边长                                                       | 简单                     |
|      | [485. 最大连续1的个数](https://leetcode-cn.com/problems/max-consecutive-ones/) | 一次遍历                                                     | 智障题目                 |
|      | [494. 目标和](https://leetcode-cn.com/problems/target-sum/)  |                                                              | Dp                       |
|      | [501. 二叉搜索树中的众数](https://leetcode-cn.com/problems/find-mode-in-binary-search-tree/) |                                                              | 中序遍历                 |
|      | [506. 相对名次](https://leetcode-cn.com/problems/relative-ranks/) |                                                              | Priority_queue           |
|      | [509. 斐波那契数](https://leetcode-cn.com/problems/fibonacci-number/) |                                                              | 智障题                   |
|      | [514. 自由之路](https://leetcode-cn.com/problems/freedom-trail/) |                                                              | dp                       |
|      | [520. 检测大写字母](https://leetcode-cn.com/problems/detect-capital/) |                                                              | 非常智障                 |
|      | [538. 把二叉搜索树转换为累加树](https://leetcode-cn.com/problems/convert-bst-to-greater-tree/) |                                                              | 前序遍历变种             |
|      | [540. 有序数组中的单一元素](https://leetcode-cn.com/problems/single-element-in-a-sorted-array/) |                                                              | 位运算 or 二分变形       |
|      | [542. 01 矩阵](https://leetcode-cn.com/problems/01-matrix/)  | 两次遍历                                                     | 矩阵                     |
|      | [543. 二叉树的直径](https://leetcode-cn.com/problems/diameter-of-binary-tree/) |                                                              | 递归                     |
|      | [547. 省份数量](https://leetcode-cn.com/problems/number-of-provinces/) |                                                              | 并查集/DFS               |
|      | [557. 反转字符串中的单词 III](https://leetcode-cn.com/problems/reverse-words-in-a-string-iii/) |                                                              | Reverse                  |
|      | [559. N 叉树的最大深度](https://leetcode-cn.com/problems/maximum-depth-of-n-ary-tree/) |                                                              | 递归                     |
|      | [572. 另一个树的子树](https://leetcode-cn.com/problems/subtree-of-another-tree/) |                                                              | 递归                     |
|      | [583. 两个字符串的删除操作](https://leetcode-cn.com/problems/delete-operation-for-two-strings/) | 二维dp，【72题编辑距离】的变形                               | dp                       |
|      | [594. 最长和谐子序列](https://leetcode-cn.com/problems/longest-harmonious-subsequence/) |                                                              | map                      |
|      | [598. 范围求和 II](https://leetcode-cn.com/problems/range-addition-ii/) |                                                              | 智障                     |
|      | [605. 种花问题](https://leetcode-cn.com/problems/can-place-flowers/) |                                                              | 贪心                     |
|      | [617. 合并二叉树](https://leetcode-cn.com/problems/merge-two-binary-trees/) |                                                              | 递归                     |
|      | [621. 任务调度器](https://leetcode-cn.com/problems/task-scheduler/) |                                                              | 贪心                     |
|      | [633. 平方数之和](https://leetcode-cn.com/problems/sum-of-square-numbers/) | 注意溢出                                                     | 双指针                   |
|      | [643. 子数组最大平均数 I](https://leetcode-cn.com/problems/maximum-average-subarray-i/) | 简单的遍历就行                                               | 滑动窗口                 |
|      | [645. 错误的集合](https://leetcode-cn.com/problems/set-mismatch/) |                                                              | 智障题目                 |
|      | [646. 最长数对链](https://leetcode-cn.com/problems/maximum-length-of-pair-chain/) |                                                              | 300变种，dp              |
|      | [647. 回文子串](https://leetcode-cn.com/problems/palindromic-substrings/) |                                                              |                          |
|      | [653. 两数之和 IV - 输入 BST](https://leetcode-cn.com/problems/two-sum-iv-input-is-a-bst/) |                                                              | 树的遍历+set             |
|      | [665. 非递减数列](https://leetcode-cn.com/problems/non-decreasing-array/) |                                                              | 贪心                     |
|      | [673. 最长递增子序列的个数](https://leetcode-cn.com/problems/number-of-longest-increasing-subsequence/) |                                                              | 300变种，dp              |
|      | [674. 最长连续递增序列](https://leetcode-cn.com/problems/longest-continuous-increasing-subsequence/) |                                                              | 序列                     |
|      | [680. 验证回文字符串 Ⅱ](https://leetcode-cn.com/problems/valid-palindrome-ii/) |                                                              | 双指针                   |
|      | [682. 棒球比赛](https://leetcode-cn.com/problems/baseball-game/) |                                                              | 简单到家的状态机         |
|      | [684. 冗余连接](https://leetcode-cn.com/problems/redundant-connection/) |                                                              | 并查集                   |
|      | [692. 前K个高频单词](https://leetcode-cn.com/problems/top-k-frequent-words/) |                                                              | 自定义sort               |
|      | [695. 岛屿的最大面积](https://leetcode-cn.com/problems/max-area-of-island/) |                                                              | Dfs                      |
|      | [697. 数组的度](https://leetcode-cn.com/problems/degree-of-an-array/) | map                                                          | STL                      |
|      | [712. 两个字符串的最小ASCII删除和](https://leetcode-cn.com/problems/minimum-ascii-delete-sum-for-two-strings/) | 二维dp，【72题编辑距离】的变形                               | dp                       |
|      | [718. 最长重复子数组](https://leetcode-cn.com/problems/maximum-length-of-repeated-subarray/) |                                                              | dp                       |
|      | [746. 使用最小花费爬楼梯](https://leetcode-cn.com/problems/min-cost-climbing-stairs/) |                                                              | dp                       |
|      | [762. 二进制表示中质数个计算置位](https://leetcode-cn.com/problems/prime-number-of-set-bits-in-binary-representation/) |                                                              | 位运算/bitset            |
|      | [763. 划分字母区间](https://leetcode-cn.com/problems/partition-labels/) | 滑动窗口+合并区间                                            | 滑动窗口                 |
|      | [771. 宝石与石头](https://leetcode-cn.com/problems/jewels-and-stones/) |                                                              | 智障题                   |
|      | [783. 二叉搜索树节点最小距离](https://leetcode-cn.com/problems/minimum-distance-between-bst-nodes/) |                                                              | 树                       |
|      | [788. 旋转数字](https://leetcode-cn.com/problems/rotated-digits/) |                                                              | 智障题                   |
|      | [804. 唯一摩尔斯密码词](https://leetcode-cn.com/problems/unique-morse-code-words/) |                                                              | unordered_set            |
|      | [806. 写字符串需要的行数](https://leetcode-cn.com/problems/number-of-lines-to-write-string/) |                                                              | 智障题                   |
|      | [830. 较大分组的位置](https://leetcode-cn.com/problems/positions-of-large-groups/) |                                                              | 智障题                   |
|      | [836. 矩形重叠](https://leetcode-cn.com/problems/rectangle-overlap/) | 简单的判断非重叠的情况就行                                   | 数学                     |
|      | [844. 比较含退格的字符串](https://leetcode-cn.com/problems/backspace-string-compare/) |                                                              | 字符串                   |
|      | [845. 数组中的最长山脉](https://leetcode-cn.com/problems/longest-mountain-in-array/) | 边界很烦                                                     | 双指针                   |
|      | [876. 链表的中间结点](https://leetcode-cn.com/problems/middle-of-the-linked-list/) |                                                              | 快慢指针                 |
|      | [888. 公平的糖果棒交换](https://leetcode-cn.com/problems/fair-candy-swap/) |                                                              | 二数之和的变形           |
|      | [922. 按奇偶排序数组 II](https://leetcode-cn.com/problems/sort-array-by-parity-ii/) |                                                              | 双指针                   |
|      | [925. 长按键入](https://leetcode-cn.com/problems/long-pressed-name/) |                                                              | 双指针                   |
|      | [934. 最短的桥](https://leetcode-cn.com/problems/shortest-bridge/) |                                                              | dfs + bfs                |
|      | [941. 有效的山脉数组](https://leetcode-cn.com/problems/valid-mountain-array/) |                                                              | 智障题                   |
|      | [973. 最接近原点的 K 个点](https://leetcode-cn.com/problems/k-closest-points-to-origin/) |                                                              | priority_queue           |
|      | [977. 有序数组的平方](https://leetcode-cn.com/problems/squares-of-a-sorted-array/) | 找到中值，再向两边遍历                                       |                          |
|      | [1002. 查找常用字符](https://leetcode-cn.com/problems/find-common-characters/) |                                                              | 智障题                   |
|      | [1004. 最大连续1的个数 III](https://leetcode-cn.com/problems/max-consecutive-ones-iii/) |                                                              | 滑动窗口                 |
|      | [1038. 把二叉搜索树转换为累加树](https://leetcode-cn.com/problems/binary-search-tree-to-greater-sum-tree/) |                                                              | 前序遍历变种             |
| 并发 | [1114. 按序打印](https://leetcode-cn.com/problems/print-in-order/) |                                                              |                          |
| 并发 | [1115. 交替打印FooBar](https://leetcode-cn.com/problems/print-foobar-alternately/) |                                                              |                          |
| 并发 | [1116. 打印零与奇偶数](https://leetcode-cn.com/problems/print-zero-even-odd/) |                                                              |                          |
| 并发 | [1117. H2O 生成](https://leetcode-cn.com/problems/building-h2o/) |                                                              |                          |
|      | [1018. 可被 5 整除的二进制前缀](https://leetcode-cn.com/problems/binary-prefix-divisible-by-5/) |                                                              | 取余+位移                |
|      | [1143. 最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence/) |                                                              | dp                       |
|      | [1160. 拼写单词](https://leetcode-cn.com/problems/find-words-that-can-be-formed-by-characters/) | 统计单词                                                     | 智障题                   |
| 并发 | [1195. 交替打印字符串](https://leetcode-cn.com/problems/fizz-buzz-multithreaded/) |                                                              |                          |
|      | [1207. 独一无二的出现次数](https://leetcode-cn.com/problems/unique-number-of-occurrences/) |                                                              | 智障题                   |
| 并发 | [1226. 哲学家进餐](https://leetcode-cn.com/problems/the-dining-philosophers/) |                                                              |                          |
|      | [1347. 制造字母异位词的最小步骤数](https://leetcode-cn.com/problems/minimum-number-of-steps-to-make-two-strings-anagram/) | 统计两个单词字母出现次数差                                   | 字符串变换               |
|      | [1356. 根据数字二进制下 1 的数目排序](https://leetcode-cn.com/problems/sort-integers-by-the-number-of-1-bits/) |                                                              | 位运算 + map + multiset  |
|      | [1365. 有多少小于当前数字的数字](https://leetcode-cn.com/problems/how-many-numbers-are-smaller-than-the-current-number/) | 如何累加                                                     | 简单题                   |
|      | [1401. 圆和矩形是否有重叠](https://leetcode-cn.com/problems/circle-and-rectangle-overlapping/) |                                                              | 数学                     |
|      | [1438. 绝对差不超过限制的最长连续子数组](https://leetcode-cn.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/) |                                                              | 滑动窗口                 |
|      | [1694. 重新格式化电话号码](https://leetcode-cn.com/problems/reformat-phone-number/) |                                                              | 智障题                   |
| 剑指 | [剑指 Offer 18. 删除链表的节点](https://leetcode-cn.com/problems/shan-chu-lian-biao-de-jie-dian-lcof/) |                                                              | 智障题                   |
| 剑指 | [剑指 Offer 38. 字符串的排列](https://leetcode-cn.com/problems/zi-fu-chuan-de-pai-lie-lcof/) |                                                              | dfs                      |
| 剑指 | [剑指 Offer 39. 数组中出现次数超过一半的数字](https://leetcode-cn.com/problems/shu-zu-zhong-chu-xian-ci-shu-chao-guo-yi-ban-de-shu-zi-lcof/) | 消除思想                                                     | trick                    |
| 剑指 | [剑指 Offer 40. 最小的k个数](https://leetcode-cn.com/problems/zui-xiao-de-kge-shu-lcof/) | priority_queue                                               | STL                      |
| 剑指 | [剑指 Offer 47. 礼物的最大价值](https://leetcode-cn.com/problems/li-wu-de-zui-da-jie-zhi-lcof/) |                                                              | dp                       |
| 剑指 | [剑指 Offer 48. 最长不含重复字符的子字符串](https://leetcode-cn.com/problems/zui-chang-bu-han-zhong-fu-zi-fu-de-zi-zi-fu-chuan-lcof/) |                                                              | 记录begin                |
| 剑指 | [剑指 Offer 58 - II. 左旋转字符串](https://leetcode-cn.com/problems/zuo-xuan-zhuan-zi-fu-chuan-lcof/) |                                                              | 智障题                   |
| 剑指 | [剑指 Offer 59 - II. 队列的最大值](https://leetcode-cn.com/problems/dui-lie-de-zui-da-zhi-lcof/) |                                                              | queue+deque              |
| 剑指 | [剑指 Offer 63. 股票的最大利润](https://leetcode-cn.com/problems/gu-piao-de-zui-da-li-run-lcof/) |                                                              | 同121                    |
|      | [面试题 01.01. 判定字符是否唯一](https://leetcode-cn.com/problems/is-unique-lcci) |                                                              | 智障题                   |
|      | [面试题 01.02. 判定是否互为字符重排](https://leetcode-cn.com/problems/check-permutation-lcci/) |                                                              | 智障题                   |
|      | [面试题 01.03. URL化](https://leetcode-cn.com/problems/string-to-url-lcci/) |                                                              | 智障题                   |
|      | [面试题 01.06. 字符串压缩](https://leetcode-cn.com/problems/compress-string-lcci/) |                                                              | 字符串处理               |
|      | [面试题 01.09. 字符串轮转](https://leetcode-cn.com/problems/string-rotation-lcci/) | 每次找到头                                                   | 字符串处理               |
|      | [面试题 02.01. 移除重复节点](https://leetcode-cn.com/problems/remove-duplicate-node-lcci/) |                                                              | 链表操作                 |
|      | [面试题 02.06. 回文链表](https://leetcode-cn.com/problems/palindrome-linked-list-lcci/) | 同234                                                        |                          |
|      | [面试题 04.03. 特定深度节点链表](https://leetcode-cn.com/problems/list-of-depth-lcci/) |                                                              | 树的层次遍历             |
|      | [面试题 08.04. 幂集](https://leetcode-cn.com/problems/power-set-lcci/) |                                                              | Dfs                      |
|      | [面试题 16.02. 单词频率](https://leetcode-cn.com/problems/words-frequency-lcci/) |                                                              | map                      |
|      | [面试题 17.22. 单词转换](https://leetcode-cn.com/problems/word-transformer-lcci/) |                                                              | dfs                      |
|      |                                                              |                                                              |                          |
|      |                                                              |                                                              |                          |



牛客网：

|      |                                                              |                              |                |
| ---- | ------------------------------------------------------------ | ---------------------------- | -------------- |
|      | [NC0001大数相加](https://www.nowcoder.com/practice/11ae12e8c6fe48f883cad618c2e81475?tpId=188&&tqId=37369&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 字符串         |
|      | [NC0002重排链表](https://www.nowcoder.com/practice/3d281dc0b3704347846a110bf561ef6b?tpId=188&&tqId=37552&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 取中，切断，翻转，合并       | 链表           |
|      | [NC0003链表中环的入口](https://www.nowcoder.com/practice/6e630519bf86480296d0f1c868d425ad?tpId=188&&tqId=37517&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 链表，公式     |
|      | [NC0004判断链表有环](https://www.nowcoder.com/practice/650474f313294468a4ded3ce0f7898b9?tpId=188&&tqId=37363&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 快慢指针       |
|      | [NC0005二叉树根节点到叶子节点的所有路径和](https://www.nowcoder.com/practice/185a87cd29eb42049132aed873273e83?tpId=196&tqId=37049&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | 递归           |
|      | [NC0006二叉树的最大路径和](https://www.nowcoder.com/practice/da785ea0f64b442488c125b441a4ba4a?tpId=196&tqId=37050&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | 递归           |
|      | [NC0008二叉树根节点到叶子节点为指定和的路径](https://www.nowcoder.com/practice/840dd2dc4fbd4b2199cd48f2dadf930a?tpId=188&&tqId=37535&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 递归           |
|      | [NC0009二叉树中是否存在节点和为指定值的和](https://www.nowcoder.com/practice/508378c0823c423baa723ce448cbfd0c?tpId=188&&tqId=37365&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 递归           |
|      | [NC0012 重建二叉树](https://www.nowcoder.com/practice/8a19cbe657394eeaac2f6ea9b0f6fcf6?tpId=188&&tqId=37364&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 树，递归       |
|      | [NC0013二叉树的最大深度](https://www.nowcoder.com/practice/8a2b2bf6c19b4f23a9bdb9b233eefa73?tpId=196&tqId=37055&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | Dfs，递归      |
|      | [NC0014 二叉树的之字形层次遍历](https://www.nowcoder.com/practice/47e1687126fa461e8a3aff8632aa5559?tpId=188&&tqId=37372&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 层次遍历，reverse            | 树             |
|      | [NC0015二叉树的层次遍历](https://www.nowcoder.com/practice/04a5560e43e24e9db4595865dc9c63a3?tpId=188&&tqId=37370&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 树，queue      |
|      | [NC0016判断二叉树是否对称](https://www.nowcoder.com/practice/1b0b7f371eae4204bc4a7570c84c2de1?tpId=188&&tqId=37515&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 树，递归       |
|      | [NC0017最长回文子串](https://www.nowcoder.com/practice/b4525d1d84934cf280439aeecc36f4af?tpId=190&&tqId=35207&rp=1&ru=/activity/oj&qru=/ta/job-code-high-rd/question-ranking) | 2n + 1，方便处理             | 字符串         |
|      | [NC0019子数组的最大累加和问题](https://www.nowcoder.com/practice/554aa508dd5d4fefbf0f86e5fe953abd?tpId=188&&tqId=37545&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 1维dp                        | dp             |
|      | [NC0022 合并两个有序的数组](https://www.nowcoder.com/practice/89865d4375634fc484f3a24b7fe65665?tpId=188&&tqId=37378&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 双指针                       | 数组           |
|      | [NC0030数组中没有出现过的最小整数](https://www.nowcoder.com/practice/8cc4f31432724b1f88201f7b721aa391?tpId=188&&tqId=37539&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 位运算         |
|      | [NC0032求平方根](https://www.nowcoder.com/practice/09fbfb16140b40499951f55113f2166c?tpId=196&tqId=37068&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | 二分           |
|      | [NC0031第一个只出现一次的字符](https://www.nowcoder.com/practice/1c82e8cf713b4bbeb2a5b31cf5b0417c?tpId=196&&tqId=37558&rp=1&ru=/activity/oj&qru=/ta/job-code-total/question-ranking) | 两次遍历                     | 字符串         |
|      | [NC0033合并有序链表](https://www.nowcoder.com/practice/a479a3f0c4554867b35356e0d57cf03d?tpId=188&&tqId=37516&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 链表           |
|      | [NC0034求路径](https://www.nowcoder.com/practice/166eaff8439d4cd898e3ba933fbc6358?tpId=188&&tqId=37383&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | dp             |
|      | [NC0035最小编辑代价](https://www.nowcoder.com/practice/05fed41805ae4394ab6607d0d745c8e4?tpId=196&&tqId=37134&rp=1&ru=/activity/oj&qru=/ta/job-code-total/question-ranking) | 二维dp，72编辑距离的变形     | dp             |
|      | [NC0038 螺旋矩阵](https://www.nowcoder.com/practice/7edf70f2d29c4b599693dc3aaeea1d31?tpId=188&&tqId=37374&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 常规           |
|      | [NC0040两个链表生成相加链表](https://www.nowcoder.com/practice/c56f6c70fb3f4849bc56e33ff2a50b6b?tpId=188&&tqId=37538&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 倒序链表，链表相加，倒序链表 | 链表           |
|      | [NC0041最长无重复子串](https://www.nowcoder.com/practice/b56799ebfd684fb394bd315e89324fb4?tpId=188&&tqId=37555&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | unordered_map, 记录begin     | STL            |
|      | [NC0045二叉树的前中后序遍历](https://www.nowcoder.com/practice/a9fec6c46a684ad5a3abd4e365a9d362?tpId=188&&tqId=37375&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 递归                         | 树             |
|      | [NC0048在转动过的有序数组中寻找目标值](https://www.nowcoder.com/practice/7cd13986c79d4d3a8d928d490db5d707?tpId=188&&tqId=37525&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              |                |
|      | [NC0049最长的括号子串](https://www.nowcoder.com/practice/45fd68024a4c4e97a8d6c45fc61dc6ad?tpId=196&tqId=37079&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) | 同leetcode 32                | trick          |
|      | [NC0050链表中的节点每K个一组翻转](https://www.nowcoder.com/practice/b49c3dc907814e9bbfa8437c251b028e?tpId=188&tqId=37526&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-high-week%2Fquestion-ranking&tab=answerKey) |                              | 链表           |
|      | [NC0052括号序列](https://www.nowcoder.com/practice/37548e94a270412c8b9fb85643c8ccc2?tpId=188&&tqId=37530&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | stack                        | STL            |
|      | [NC0053删除链表的倒数第N个节点](https://www.nowcoder.com/practice/f95dcdafbde44b22a6d741baf71653f6?tpId=188&&tqId=37366&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 快慢指针       |
|      | [NC0054数组中相加和为0的三元组](https://www.nowcoder.com/practice/345e2ed5f81d4017bbb8cc6055b0b711?tpId=188&&tqId=37532&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | Map, pair                    | STL            |
|      | [NC0055最长公共前缀](https://www.nowcoder.com/practice/28eb3175488f4434a4a6207f6f484f47?tpId=196&&tqId=37086&rp=1&ru=/activity/oj&qru=/ta/job-code-total/question-ranking) | 遍历                         | 字符串         |
|      | [NC0059矩阵最小路径和](https://www.nowcoder.com/practice/7d21b6be4c6b429bb92d219341c4f8bb?tpId=196&tqId=37157&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | dp             |
|      | [NC0060 判断二叉树是否为搜索二叉树和完全二叉树](https://www.nowcoder.com/practice/f31fc6d3caf24e7f8b4deb5cd9b5fa97?tpId=196&&tqId=37156&rp=1&ru=/activity/oj&qru=/ta/job-code-total/question-ranking) | 中序遍历+层次遍历            | 树             |
|      | [NC0061两数之和](https://www.nowcoder.com/practice/20ef0972485e41019e39543e8e895b7f?tpId=188&&tqId=37382&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | map                          | STL            |
|      | [NC0063 跳台阶](https://www.nowcoder.com/practice/8c82a5b80378478f9484d87d1c5f12a4?tpId=188&&tqId=37379&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 斐波那契数列                 | dp             |
|      | [NC0065斐波拉契数列](https://www.nowcoder.com/practice/c6c7742f5ba7442aada113136ddea0c3?tpId=188&&tqId=37527&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | Dp             |
|      | [NC0066两个链表的第一个公共节点](https://www.nowcoder.com/practice/6ab1d9a29e88450685099d45c9e31e46?tpId=188&&tqId=37541&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 遍历                         | 链表           |
|      | [NC0072二叉树的镜像](https://www.nowcoder.com/practice/564f4c26aa584921bc75623e48ca3011?tpId=188&&tqId=37380&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 递归                         | 树             |
|      | [NC0073数组中出现次数超过一半的数字](https://www.nowcoder.com/practice/e8a1b01a2df14cb2b228b30ee6a92163?tpId=188&&tqId=37529&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 消除思想                     | trick          |
|      | [NC0076用两个栈实现队列](https://www.nowcoder.com/practice/54275ddae22f475981afa2244dd448c6?tpId=188&&tqId=37536&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | stack                        | STL            |
|      | [NC0078 反转链表](https://www.nowcoder.com/practice/75e878df47f24fdc9dc3e400ec6058ca?tpId=188&&tqId=37361&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 链表           |
|      | [NC0086矩阵元素查找](https://www.nowcoder.com/practice/3afe6fabdb2c46ed98f06cfd9a20f2ce?tpId=196&tqId=37121&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) | 右上↙左下                    | 剑指offer原题  |
|      | [NC0088第K大的数](https://www.nowcoder.com/practice/e016ad9b7f0b45048c58a9f27ba618bf?tpId=117&&tqId=35010&rp=1&ru=/activity/oj&qru=/ta/job-code-high/question-ranking) |                              | 快排           |
|      | [NC0090设计getMin功能的栈](https://www.nowcoder.com/practice/c623426af02d4c189f92f2a99647bd34?tpId=188&&tqId=37556&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | stack                        | STL            |
|      | [NC0091最长递增子序列](https://www.nowcoder.com/practice/9cf027bf54714ad889d4f30ff0ae5481?tpId=196&tqId=37129&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | trick          |
|      | [NC0093 实现LRU](https://www.nowcoder.com/practice/e3769a5f49894d49b871c09cadd13a61?tpId=188&&tqId=37367&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | unordered_map + list         | STL            |
|      | [NC0096 判断一个链表是否为回文结构](https://www.nowcoder.com/practice/3fed228444e740c8be66232ce8b87c2f?tpId=188&&tqId=37381&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 链表           |
|      | [NC0097出现次数的TopK问题](https://www.nowcoder.com/practice/fd711bdfa0e840b381d7e1b82183b3ee?tpId=196&tqId=37142&rp=1&ru=%2Fta%2Fjob-code-total&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) | map，unordered_map           | STL            |
|      | [NC0101缺失数字](https://www.nowcoder.com/practice/9ce534c8132b4e189fd3130519420cde?tpId=188&&tqId=37384&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 遍历           |
|      | [NC0102二叉树两个节点的最近公共祖先](https://www.nowcoder.com/practice/e0cc33a83afe4530bcec46eba3325116?tpId=196&tqId=37160&rp=1&ru=%2Factivity%2Foj&qru=%2Fta%2Fjob-code-total%2Fquestion-ranking&tab=answerKey) |                              | 递归           |
|      | [NC0103反转字符串](https://www.nowcoder.com/practice/c3a6afee325e472386a1c4eb1ef987f3?tpId=190&&tqId=35226&rp=1&ru=/activity/oj&qru=/ta/job-code-high-rd/question-ranking) |                              | 双指针         |
|      | [NC0105二分查找](https://www.nowcoder.com/practice/7bc4a1c7c371425d9faa9d1b511fe193?tpId=117&&tqId=35030&rp=1&ru=/activity/oj&qru=/ta/job-code-high/question-ranking) |                              | 二分查找>=     |
|      | [NC0108最大正方形](https://www.nowcoder.com/practice/0058c4092cec44c2975e38223f10470e?tpId=188&&tqId=37550&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 2维dp                        | dp             |
|      | [NC0109岛屿数量](https://www.nowcoder.com/practice/0c9664d1554e466aa107d899418e814e?tpId=188&&tqId=37543&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | dfs            |
|      | [NC0112 进制转换](https://www.nowcoder.com/practice/2cc32b88fff94d7e8fd458b8c7b25ec1?tpId=188&&tqId=37376&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 常规           |
|      | [NC0117合并二叉树](https://www.nowcoder.com/practice/7298353c24cc42e3bd5f0e0bd3d1d759?tpId=188&&tqId=37368&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 递归           |
|      | [NC0119最小的k个数](https://www.nowcoder.com/practice/6a296eb82cf844ca8539b57c23e6e9bf?tpId=188&&tqId=37373&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | Priority_queue |
|      | [NC0121字符串的排序](https://www.nowcoder.com/practice/fe6b651b66ae47d7acce78ffdd9a96c7?tpId=188&&tqId=37549&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | dfs，递归      |
|      | [NC0127最长公共子串](https://www.nowcoder.com/practice/f33f5adc55f444baa0e0ca87ad8a6aac?tpId=188&&tqId=37540&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) | 2维dp                        | dp             |
|      | [NC0140排序](https://www.nowcoder.com/practice/2baf799ea0594abd974d37139de27896?tpId=188&&tqId=37551&rp=1&ru=/activity/oj&qru=/ta/job-code-high-week/question-ranking) |                              | 快排           |
|      | [NC0141判断回文串](https://www.nowcoder.com/practice/e297fdd8e9f543059b0b5f05f3a7f3b2?tpId=190&&tqId=36606&rp=1&ru=/activity/oj&qru=/ta/job-code-high-rd/question-ranking) |                              | 双指针         |
|      | [NC0149kmp算法](https://www.nowcoder.com/practice/bb1615c381cc4237919d1aa448083bcc?tpId=196&&tqId=37564&rp=1&ru=/activity/oj&qru=/ta/job-code-total/question-ranking) |                              |                |



