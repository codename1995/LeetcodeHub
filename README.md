LeetCodeHub
===========================
LeetCode solution (C++ and Python)

- [LeetCodeHub](#leetcodehub)
- [TODO](#todo)
- [Leetcode Hot & Top](#leetcode-hot--top)
- [Sort by coding-interview (剑指offer)](#sort-by-coding-interview-%e5%89%91%e6%8c%87offer)
- [Tag](#tag)

# TODO
* [x] 1. 《剑指offer》习题一刷 (19年11月10日完成)
* [ ] 2. 按Tag整理习题
   * 对常用的数据结构、方法、套路进行整理
* [ ] 3. 《剑指offer》二刷 (6/66)
* [ ] 4. Leetcode [Hot 100](https://leetcode-cn.com/problemset/hot-100/) + [Top](https://leetcode-cn.com/problemset/top/) (20/144/245) (上传/完成/总数)
 
# Leetcode Hot & Top
| Leetcode  | Solution  | Basic idea   |
| ---       | ---       |  ---         |
005 [Longest Palindromic Substring](https://leetcode-cn.com/problems/longest-palindromic-substring/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/5_Longest_Palindromic_Substring/5_Longest_Palindromic_Substring.cpp) | 1. 中心扩展
010 [Regular Expression Matching](https://leetcode-cn.com/problems/regular-expression-matching/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/10_Regular_Expression_Matching/10_Regular_Expression_Matching.cpp) | 1. 二维布尔型数组，dp[i][j]表示s[i:]与p[j:]匹配
034 [Find First and Last Position of Element in Sorted Array](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/34_Find_First_And_Last_Position_Of_Element_In_Sorted_Array/34_Find_First_And_Last_Position_Of_Element_In_Sorted_Array.cpp )| 1. 两次二分，分别返回 不大于/大于 target的第一个位置。需要注意两次二分的细节差异和确定返回位置是否在数组范围内。
053 [Maximum  Subarray](https://leetcode-cn.com/problems/maximum-subarray/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/53_Maximum_Subarray/53_Maximum_Subarray.cpp)| 1. DP |
062 [Unique Paths](https://leetcode-cn.com/problems/unique-paths/ ) | [Python](https://github.com/codename1995/leetcodehub/blob/master/python/62_Unique_Paths.py) | 1. DP 
064 [Minimum Path Sum](https://leetcode-cn.com/problems/minimum-path-sum/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/64_Minimum_Path_Sum/64_Minimum_Path_Sum.cpp) | 1. DP|
070 [Climbing Stairs](https://leetcode-cn.com/problems/climbing-stairs/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/70_Climbing_Stairs/70_Climbing_Stairs.cpp) | 1. DP|
| 079 [Word Search](https://leetcode-cn.com/problems/word-search/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/79_Word_Search/79_Word_Search.cpp)  | 1. DFS+Backtracking
091 [Decode Ways](https://leetcode-cn.com/problems/decode-ways/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/91_Decode_Ways/91_Decode_Ways.cpp) | 1. DP
105 [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)| [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/105_Construct_Binary_Tree_from_Preorder_and_Inorder/105_Construct_Binary_Tree_from_Preorder_and_Inorder.cpp)| 1. 根据前序的第一个元素中序中确定根的位置，从而得到左右子树的元素数量，于是将前序和中序分为左右子树。再对左右子树递归此过程
121 [Best Time To Buy And Sell Stock](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/submissions/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/121_Best_Time_To_Buy_And_Sell_Stock/121_Best_Time_To_Buy_And_Sell_Stock.cpp) | 1. DP <br> 2. 遍历数组时维护最小价格，并判断价差是否产生更大收益|
122 [Best Time To Buy And Sell Stock II](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-ii/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/122_Best_Time_To_Buy_And_Sell_Stock_II/122_Best_Time_To_Buy_And_Sell_Stock_II.cpp) | 1. DP <br> 2. 逐步更新收益 |
139 [Word Break](https://leetcode-cn.com/problems/word-break/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/139_Word_Break/139_Word_Break.cpp) | 1. DP, dp[i] = dp[i-ws] && s[i-ws:i] == word, (ws: word.size())
152 [Maximum Product Subarray](https://leetcode-cn.com/problems/maximum-product-subarray/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/152_Maximum_Product_Subarray/152_Maximum_Product_Subarray.cpp) | 1. DP (Update cur_max and cur_min, when meeting a negative number, exchange this two number before updating)
188 [Best Time To Buy And Sell Stock IV](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-iv/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/188_Best_Time_To_Buy_And_Sell_Stock_IV/188_Best_Time_To_Buy_And_Sell_Stock_IV.cpp) | 1. DP Table/State Machine |
191 [Number of 1 Bits](https://leetcode-cn.com/problems/number-of-1-bits/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/191_Number_of_1_Bits/191_Number_of_1_Bits.cpp)  | 1. n &= (n-1) 能够将最右一位1置零
198 [House Robber](https://leetcode-cn.com/problems/house-robber/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/198_House_Robber/198_House_Robber.cpp) | 1. DP|
221 [Maximal Square](https://leetcode-cn.com/problems/maximal-square/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/221_Maximal_Square/221_Maximal_Square.cpp) | 1. DP dp[r][c] = min(dp[r-1][c], dp[r][c-1], dp[r-1][c-1]) + 1 表示(r,c)处的最大边长|
240 [Search a 2D Matrix II](https://leetcode-cn.com/problems/search-a-2d-matrix-ii/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/240_Search_a_2D_Matrix_II/240_Search_a_2D_Matrix_II.cpp)  |  1. 自右上向左或向下移动指针，直到找到目标或者退出循环 |
268 [Missing Number](https://leetcode-cn.com/problems/missing-number/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/268_Missing_Number/268_Missing_Number.cpp) | 1. 两遍XOR，剩余的就是答案； <br> 2. 数学方法，利用求和公式减去实际和|
279 [Perfect Squares](https://leetcode-cn.com/problems/perfect-squares/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/279_Perfect_Squares/279_Perfect_Squares.cpp) | 1. DP (Bottom-Up faster)|
287 [Find the Duplicate Number](https://leetcode-cn.com/problems/find-the-duplicate-number/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/287_Find_the_Duplicate_Number/287_Find_the_Duplicate_Number.cpp) |  1. 排序+逐个比较，能过，但**不符合要求** <br> 2. 对数值进行二分，统计[l,m]和(m,h]中数字的数量，重复数在大于标准值(m-l+1或h-m)的那一半里
300 [Longest Increasing Subsequence](https://leetcode-cn.com/problems/longest-increasing-subsequence/solution/zui-chang-shang-sheng-zi-xu-lie-dong-tai-gui-hua-2/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/300_Longest_Increasing_Subsequence/300_Longest_Increasing_Subsequence.cpp) | 1. DP O(n^2) <br> 2. DP + Binary Searcy O(nlogn)|
309 [Best Time To Buy And Sell Stock With Cooldown](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/309_Best_Time_To_Buy_And_Sell_Stock_With_Cooldown/309_Best_Time_To_Buy_And_Sell_Stock_With_Cooldown.cpp) | 1. DP <br> 2. 有限状态机（rest, hold, sold)|
322 [Coin Change](https://leetcode-cn.com/problems/coin-change/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/322_Coin_Change/322_Coin_Change.cpp) | 1. DP (Bottom-Up)|
337 [House Robber III](https://leetcode-cn.com/problems/house-robber-iii/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/337_House_Robber_III/337_House_Robber_III.cpp) | 1. 树型DP，子函数返回{MaxWithCurrNode, MaxWithoutCurrNode} |
338 [Counting_Bits](https://leetcode-cn.com/problems/counting-bits/)|[C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/338_Counting_Bits/338_Counting_Bits.cpp)| 1. 偶数的1的个数与其一半有关，奇数的1的个数与前一个数有关
343 [Interger Break](https://leetcode-cn.com/problems/integer-break/)   | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/343_Interger_Break/343_Interger_Break.cpp)  | 1. 穷举找规律，发现4及以下单独处理，4以上不停地分出3 |

# Sort by coding-interview (剑指offer)
这里按照剑指offer的顺序整理了部分Leetcode的题目，方便直接在Leetcode上刷题。同时，也给出了每题能AC的解法，以C++为主。  
Most of leetcode links are based on @yanring's [REPO](https://gist.github.com/yanring/fd7c494616f99052d1fea3bc788cc800).

| 剑指offer | Leetcode | Solution |  
| --- | --- | --- | 
| 03 数组中重复的数字 | | [官方题解](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/coding_interview_03_01_FindDuplicates/coding_interview_03_01_FindDuplicates.cpp) 以原数组做哈希表
| 03_02 不修改数组找出重复的数字 |287 [Find the Duplicate Number](https://leetcode-cn.com/problems/find-the-duplicate-number/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/287_Find_the_Duplicate_Number/287_Find_the_Duplicate_Number.cpp) |  
| 04 二维数组中的查找 | 240 [Search a 2D Matrix II](https://leetcode-cn.com/problems/search-a-2d-matrix-ii/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/240_Search_a_2D_Matrix_II/240_Search_a_2D_Matrix_II.cpp)  |  
| 05 [替换空格](https://www.nowcoder.com/practice/4060ac7e3e404ad1a894ef3e17650423?tpId=13&tqId=11155&tPage=1&rp=1&ru=/ta/coding-interviews&qru=/ta/coding-interviews/question-ranking) |  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/coding_interview_05_ReplaceSpace/05_ReplaceSpace.cpp) | 
| 06 从尾到头打印链表|| 1. 利用栈实现（略）<br> 2. 利用递归实现（略）|
|07 重建二叉树| 105 [Construct Binary Tree from Preorder and Inorder Traversal](https://leetcode-cn.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)| [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/105_Construct_Binary_Tree_from_Preorder_and_Inorder/105_Construct_Binary_Tree_from_Preorder_and_Inorder.cpp)|
|08 二叉树的下一个节点|510 [Inorder Successor in BST II](https://leetcode-cn.com/problems/inorder-successor-in-bst-ii/)| [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/510_Inorder_Successor_in_BST_II/510_Inorder_Successor_in_BST_II.cpp) |
|09 用两个栈实现队列   |  232 [Implement Queue using Stacks](https://leetcode-cn.com/problems/implement-queue-using-stacks/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/232_Implement_Queue_using_Stacks/232_Implement_Queue_using_Stacks.cpp)  |
| 09_02 用两个队列实现栈   |  225 [Implement Stack using Queue](https://leetcode-cn.com/problems/implement-stack-using-queues/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/225_Implement_Stack_using_Queue/225_Implement_Stack_using_Queue.cpp) <u>**两个栈实现队列，一个队列实现栈!!!**</u>  |
| 10 斐波那契数列  |509 [Fibonacci Number](https://leetcode-cn.com/problems/fibonacci-number/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/509_Fibonacci_Number/509_Fibonacci_Number.cpp) |
| 10_02 青蛙跳台阶 | 70 [Climbing Stairs](https://leetcode-cn.com/problems/climbing-stairs/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/70_Climbing_Stairs/70_Climbing_Stairs.cpp) |
| 11 旋转数组中的最小数字  | 153 [Find Minimum in Rotated Sorted Array](https://leetcode-cn.com/problems/find-minimum-in-rotated-sorted-array/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/153_Find_Minimum_in_Rotated_Sorted_Array/153_Find_Minimum_in_Rotated_Sorted_Array.cpp)  核心是比较nums[m]与nums[r]|
| 12 矩阵中的路径  | 79 [Word Search](https://leetcode-cn.com/problems/word-search/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/79_Word_Search/79_Word_Search.cpp)  |
| 13 机器人的运动范围  |   | 可参考1219 黄金矿工，也是二维矩阵dfs搜索的问题，而且更难一些  |
| 14 剪绳子 | 343 [Interger Break](https://leetcode-cn.com/problems/integer-break/)   | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/343_Interger_Break/343_Interger_Break.cpp)  |
| 15 二进制中1的个数  | 191 [Number of 1 Bits](https://leetcode-cn.com/problems/number-of-1-bits/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/191_Number_of_1_Bits/191_Number_of_1_Bits.cpp)  |
||(Advanced) 338 [Counting_Bits](https://leetcode-cn.com/problems/counting-bits/)|[C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/338_Counting_Bits/338_Counting_Bits.cpp)|
| 16 数值的整数次方 | 50 [Pow(x, n)](https://leetcode-cn.com/problems/powx-n/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/50_Pow/50_Pow.cpp), Python   |
| 17 打印从1到最大的n位数 |   |   |
| 18 删除链表的节点  | 237 [Delete Node in a Linked List](https://leetcode-cn.com/problems/delete-node-in-a-linked-list/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/237_Delete_Node_in_a_Linked_List/237_Delete_Node_in_a_Linked_List.cpp) [python](https://github.com/codename1995/LeetCodeHub/blob/master/python/237.DeleteNodeInALinkedList.py)  |
|   | 203 [Remove Linked List Elements](https://leetcode-cn.com/problems/remove-linked-list-elements/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/203_Remove_Linked_List_Elements/203_Remove_Linked_List_Elements.cpp)  |
| 18_02 删除链表中重复的节点  | 83 [Remove Duplicates from Sorted List](https://leetcode-cn.com/problems/remove-duplicates-from-sorted-list/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/83_Remove_Duplicates_from_Sorted_List/Remove_Duplicates_from_Sorted_List.cpp)  |
| 19 正则表达式匹配  | 10 [Regular Expression Matching](https://leetcode-cn.com/problems/regular-expression-matching/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/10_Regular_Expression_Matching/10_Regular_Expression_Matching.cpp),[Python](https://github.com/codename1995/LeetCodeHub/blob/master/python/10.RegularExpressionMatching.py), adapted from [offical solution](https://leetcode-cn.com/problems/regular-expression-matching/solution/zheng-ze-biao-da-shi-pi-pei-by-leetcode/)  |
| 20 表示数值的字符串  | 65 [Valid Number](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/65_Valid_Number/Valid_Number.cpp) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/65_Valid_Number/65_Valid_Number.cpp)  |
| 21 调整数组顺序使奇数位于偶数前面  |905 [Sort Array By Parity](https://leetcode-cn.com/problems/sort-array-by-parity/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/905_Sort_Array_by_Parity/905_Sort_Array_by_Parity.cpp)  |
| 22 链表中倒数第k个节点  |19 [Remove Nth Node From End of List](https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/19_Remove_Nth_Node_from_End_of_List/19_Remove_Nth_Node_from_End_of_List.cpp) |
| 23 链表中环的入口节点  |142 [Linked List Cycle II](https://leetcode-cn.com/problems/linked-list-cycle-ii/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/142_Linked_List_Cycle_II/142_Linked_List_Cycle_II.cpp)  |
| 24 反转链表  |206 [Reverse Linked List](https://leetcode-cn.com/problems/reverse-linked-list/)| [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/206_Reverse_Linked_List/206_Reverse_Linked_List.cpp),[Python](https://github.com/codename1995/LeetCodeHub/blob/master/python/206.ReverseLinkedList.py)  |
| 25 合并两个排序的链表  |21 [Merge Two Sorted Lists](https://leetcode-cn.com/problems/merge-two-sorted-lists/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/21_Merge_Two_Sorted_Lists/21_Merge_Two_Sorted_Lists.cpp)  |
| 26 树的子结构  | 572 [Subtree of Another Tree](https://leetcode-cn.com/problems/subtree-of-another-tree/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/572_Subtree_of_Another_Tree/572_Subtree_of_Another_Tree.cpp)  |
| 27 二叉树的镜像  | 226 [Invert Binary Tree](https://leetcode-cn.com/problems/invert-binary-tree/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/226_Invert_Binary_Tree/226_Invert_Binary_Tree.cpp)  |
| 28 对称的二叉树  | 101 [Symmetric Tree](https://leetcode-cn.com/problems/symmetric-tree/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/101_Symmetric_Tree/101_Symmetric_Tree.cpp)  |
| 29 顺时针打印矩阵  | 54 [Spiral Matrix](https://leetcode-cn.com/problems/spiral-matrix/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/54_Spiral_Matrix/54_Spiral_Matrix.cpp)  |
| 30 包含min函数的栈  | 155 [Min Stack](https://leetcode-cn.com/problems/min-stack/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/155_Min_Stack/155_Min_Stack.cpp)  |
| 31 栈的压入、弹出序列  | 946 [Validate Stack Sequences](https://leetcode-cn.com/problems/validate-stack-sequences/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/946_Validate_Stack_Sequences/946_Validate_Stack_Sequences.cpp)  |
| 32 从上往下打印二叉树| 102 [Binary Tree Level Order Traversal](https://leetcode-cn.com/problems/binary-tree-level-order-traversal/)| [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/102_Binary_Tree_Level_Order_Traversal/102_Binary_Tree_Level_Order_Traversal.cpp)|
| 32_03 之字形遍历二叉树| 103 [Binary Tree Zigzag Level Order Traversal](https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/submissions/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/103_Binary_Tree_Zigzag_Level_Order_Traversal/103_Binary_Tree_Zigzag_Level_Order_Traversal.cpp) |
| 33 二叉搜索树的后序遍历序列  | (Primer) 255 [Verify Preorder Sequence of a Binary Tree](https://leetcode-cn.com/problems/verify-preorder-sequence-in-binary-search-tree/submissions/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/255_Verify_Preorder_Sequence_of_a_Binary_Tree/255_Verify_Preorder_Sequence_of_a_Binary_Tree.cpp)  |
| 34 二叉树中和为某一值的路径  | 112 [Path Sum](https://leetcode-cn.com/problems/path-sum/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/112_Path_Sum/112_Path_Sum.cpp)  |
| 35 复杂链表的复制  | 138 [Copy List with Random Pointer](https://leetcode-cn.com/problems/copy-list-with-random-pointer/) | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/138_Copy_List_with_Random_Pointer/138_Copy_List_with_Random_Pointer.cpp)  |
| 36 二叉搜索树与双向链表  | (Primer) 426 [Convert Binary Search Tree to Sorted Doubly Linked List](https://leetcode-cn.com/problems/convert-binary-search-tree-to-sorted-doubly-linked-list/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/426_Convert_Binary_Search_Tree_to_Sorted_Doubly_Linked_List/426_Convert_Binary_Search_Tree_to_Sorted_Doubly_Linked_List.cpp) 光有思路不行，这题自己写比题解的简洁性差很多 |
| 37 序列化二叉树  | 297 [serialize and deserialize binary tree](https://leetcode-cn.com/problems/serialize-and-deserialize-binary-tree/)  | [C++](https://github.com/codename1995/LeetCodeHub/blob/master/cpp/297_Serialize_and_Deserialize_Binary_Tree/297_Serialize_and_Deserialize_Binary_Tree.cpp)  |
| 38 字符串的排列  | 46 [Permutations (unique number)](https://leetcode-cn.com/problems/permutations/)  | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/46_Permutations/46_Permutations.cpp)  |
| | 47 [Permutations ii (perhaps duplicates)](https://leetcode-cn.com/problems/permutations-ii/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/47_Permutations_II/47_Permutations_II.cpp) |
| | 51 [N Queens](https://leetcode-cn.com/problems/n-queens/) ||
| 39 数组中出现次数超过一半的数字 | 169 [majority element (appear over 1/2)](https://leetcode-cn.com/problems/majority-element/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/169_Majority_Element/169_Majority_Element.cpp) | 
| | 229 [majority element ii (appear over 1/3)](https://leetcode-cn.com/problems/majority-element-ii/) |  |
| 40 最小的k个数| 215 [Kth Largest Element in an array](https://leetcode-cn.com/problems/kth-largest-element-in-an-array/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/215_Kth_Largest_Element_In_An_Array/215_Kth_Largest_Element_In_An_Array.cpp) | 
| 41 数据流中的中位数 | 295 [Find Median From Data Stream](https://leetcode-cn.com/problems/find-median-from-data-stream/) |[C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/295_Find_Median_From_Data_Stream/295_Find_Median_From_Data_Stream.cpp) | 
| 42 连续子数组的最大和| 53 [Maximum  Subarray](https://leetcode-cn.com/problems/maximum-subarray/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/53_Maximum_Subarray/53_Maximum_Subarray.cpp)|
| 43 1-n整数中1出现的次数| 233 [Number of Digit One](https://leetcode-cn.com/problems/number-of-digit-one/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/233_Number_of_Digit_One/233_Number_of_Digit_One.cpp) | 
| 44 数字序列中某一位的数字|400 [Nth Digit](https://leetcode-cn.com/problems/nth-digit/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/400_Nth_Digit/400_Nth_Digit.cpp) | 
| 45 把数组排成最小的数| 179 [Largest Number](https://leetcode-cn.com/problems/largest-number/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/179_Largest_Number/179_Largest_Number.cpp), [Python](https://github.com/codename1995/LeetCodeHub/blob/master/python/179.LargestNumber.py)| 
| 46 把数字翻译成字符串| 91 [Decode Ways](https://leetcode-cn.com/problems/decode-ways/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/91_Decode_Ways/91_Decode_Ways.cpp) |
| 47 礼物最大值| 64 [Minimum Path Sum](https://leetcode-cn.com/problems/minimum-path-sum/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/64_Minimum_Path_Sum/64_Minimum_Path_Sum.cpp) | 
| 48 最长不含重复字符的子字符串|3 [Longest Substring without Repeating Characters](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/3_Longest_Substring_Without_Repeating_Characters/3_Longest_Substring_Without_Repeating_Characters.cpp) |
||159 [Longest Substring with At Most two Distinct Characters](https://leetcode-cn.com/problems/longest-substring-with-at-most-two-distinct-characters/)| 直接套用340代码，将输入参数k改为默认2即可 |
||340 [Longest Substring with At Most two Distinct Characters](https://leetcode-cn.com/problems/longest-substring-with-at-most-two-distinct-characters/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/159_Longest_Substring_With_At_Most_Two_Distinct_Characters/159_Longest_Substring_With_At_Most_Two_Distinct_Characters.cpp)|
| 49 丑数| 263 [Ugly Number](https://leetcode-cn.com/problems/ugly-number/)|[C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/263_Ugly_Number/263_Ugly_Number.cpp)|
| |264 [Ugly Number II](https://leetcode-cn.com/problems/ugly-number-ii/)|[C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/264_Ugly_Number_II/264_Ugly_Number_II.cpp)|
| 50 第一个只出现一次的字符| 387 [First Unique Character in A String](https://leetcode-cn.com/problems/first-unique-character-in-a-string/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/387_First_Unique_Character_in_A_String/387_First_Unique_Character_in_A_String.cpp) |
|50_02 字符流中第一个只出现一次的字符|| 剑指50和LC340的集合，过于简单，略（~~其实是因为LC上没找到~~）|
| 51 求数组中的逆序对的总数||与LC493思路基本一致|
|| (Advanced) 493 [Reverse Pairs](https://leetcode-cn.com/problems/reverse-pairs/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/493_Reverse_Pairs/493_Reverse_Pairs.cpp) |
||(Advanced Advanced) 315 [Count of Smaller Numbers after Self](https://leetcode-cn.com/problems/count-of-smaller-numbers-after-self/)|[C++] <!--(https://github.com/codename1995/leetcodehub/blob/master/cpp/315_Count_Of_Smaller_Numbers_After_Self/Count_Of_Smaller_Numbers_After_Self.cpp) -->|
| 52 两个链表的第一个公共节点|160 [Intersection of Two Linked Lists](https://leetcode-cn.com/problems/intersection-of-two-linked-lists/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/160_Intersection_Of_Two_Linked_Lists/160_Intersection_Of_Two_Linked_Lists.cpp)|
| 53_01 数字在排序数组中出现的次数 | 34 [Find First and Last Position of Element in Sorted Array](https://leetcode-cn.com/problems/find-first-and-last-position-of-element-in-sorted-array/)| [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/34_Find_First_And_Last_Position_Of_Element_In_Sorted_Array/34_Find_First_And_Last_Position_Of_Element_In_Sorted_Array.cpp )|
| 53_02 0..N-1中确实的数字 |268 [Missing Number](https://leetcode-cn.com/problems/missing-number/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/268_Missing_Number/268_Missing_Number.cpp) |
| 53_03 数组中数值和下标相等的元素 || 二分查找，[官方题解](https://github.com/zhedahht/CodingInterviewChinese2/blob/master/53_03_IntegerIdenticalToIndex/IntegerIdenticalToIndex.cpp)|
| 54 二叉搜索树的第k大节点|230 [Kth Smallest Element In A Bst](https://leetcode-cn.com/problems/kth-smallest-element-in-a-bst/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/230_Kth_Smallest_Element_In_A_Bst/230_Kth_Smallest_Element_In_A_Bst.cpp) |
| 55 二叉树的深度|104 [Maximum Depth Of Binary Tree](https://leetcode-cn.com/problems/maximum-depth-of-binary-tree/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/104_Maximum_Depth_Of_Binary_Tree/104_Maximum_Depth_Of_Binary_Tree.cpp) |
| 56_00 56题的前置 数组中只出现1次的那个数字| 136 [Single Number](https://leetcode-cn.com/problems/single-number/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/136_Single_Number/136_Single_Number.cpp)  XOR for every single number|
| 56_01 数组中只出现1次的2个数字 |260 [Single Number III](https://leetcode-cn.com/problems/single-number-iii/) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/230_Single_Number_III/230_Single_Number_III.cpp) 1. XOR. 2. Split to two subarray.  3. XOR for two subarray, resepctively.
| 56_02 其他数字都出现三次的数字中唯一只出现一次的数字 | 137 [Single Number II](https://leetcode-cn.com/problems/single-number-ii/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/137_Single_Number_II/137_Single_Number_II.cpp) SUM all and mod 3 for every single bit|
| 57 和为s的数字|1 [Two Sum](https://leetcode-cn.com/problems/two-sum/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/1_Two_Sum/1_Two_Sum.cpp) |
| 57_02 和为s的连续正数序列|829 [Consecutive Numbers Sum](https://leetcode-cn.com/problems/consecutive-numbers-sum/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/829_Consecutive_Numbers_Sum/829_Consecutive_Numbers_Sum.cpp) |
| 58_01 翻转单词顺序| 151 [Reverse Words In A String](https://leetcode-cn.com/problems/reverse-words-in-a-string/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/151_Reverse_Words_In_A_String/151_Reverse_Words_In_A_String.cpp) |
| 58_02 左旋转字符串|189 [Rotate Array](https://leetcode-cn.com/problems/rotate-array/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/189_Rotate_Array/189_Rotate_Array.cpp)  |
| 59_01 滑动窗口的最大值 | 239 [Sliding Window Maximum](https://leetcode-cn.com/problems/sliding-window-maximum/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/239_Sliding_Window_Maximum/239_Sliding_Window_Maximum.cpp) |
| 59_02 队列的最大值|没找到||
| 60 n个骰子的点数|1155 [Number Of Dice Rolls With Target Sum](https://leetcode-cn.com/problems/number-of-dice-rolls-with-target-sum/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/1155_Number_Of_Dice_Rolls_With_Target_Sum/1155_Number_Of_Dice_Rolls_With_Target_Sum.cpp)|
| 61 扑克牌中的顺子||模拟法，注意细节即可 ~~(其实还是因为没找到)~~|
| 62 圆圈中最后剩下的数字|没找到||
| 63 股票的最大利润|121 [Best Time To Buy And Sell Stock](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/ ) | [C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/121_Best_Time_To_Buy_And_Sell_Stock/121_Best_Time_To_Buy_And_Sell_Stock.cpp) |
| 64 求1+2+..+n||[C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/coding_interview_64_Accumulate/coding_interview_64_Accumulate.cpp) 照着敲了一下第一种方法；补充了一种利用逻辑断路来做的方法。|
| 65 不用加减乘除做加法||[C++](https://github.com/codename1995/leetcodehub/blob/master/cpp/coding_interview_65_Add/coding_interview_65_Add.cpp) |
| *66 构建乘积数组|||
| 67 把字符串转换成整数|||
| 68 树中两个节点的最低公共祖先|||

# Tag
按Tag整理常见解题思路。存放在[这里](https://github.com/codename1995/LeetCodeHub/tree/master/Tag)  
以 VS Code + Markdown Perview Enhanced 打开会更好。

<!-- |   | [](https://leetcode-cn.com/problems/ | [C++](),[Python]()  | -->
<!-- [C++](),[Python]() -->
<!-- [](https://leetcode-cn.com/problems/) -->