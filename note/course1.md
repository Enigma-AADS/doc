### 第一次课内容大纲：
                     
![基本数据结构](https://github.com/Enigma-AADS/docs/blob/master/image/note/course1/abstractdatetype.png?raw=true)
              
- 数组、链表（Array、LinkedList）
- 堆栈、队列（Stack、Queue）
- 优先队列（PriorityQueue）
- 哈希表（HashTable）
- 高频面试题讲解：2-sum、3-sum、有序列合并、括号配对、链表反转、滑动窗口
- 机器学习：介绍ML中基础数据模块 numpy 中关于array、list的高级操作


**课上编程**：[http://collabedit.com/suhav](http://collabedit.com/suhav)（老师随机code review）  
**算法练习**：[https://leetcode.com/problemset/algorithms](https://leetcode.com/problemset/algorithms)  
**入门练习（经典）**：[two-sum](https://leetcode.com/problems/two-sum)，[3sum](https://leetcode.com/problems/3sum)  
**python工具**：pycharm


----------

### 课程内容：
#### 1. 时间复杂度O(N)和基础介绍[14:00-23:00]

#### 2. LinkedList链表数组[23:00-42:00]：
- 插入删除快、查询慢
- 关键：两个节点间保存关联

##### 2.1 练习（答案在url加上/discuss）：
- 反转链表：[reverse-linked-list](https://leetcode.com/problems/reverse-linked-list/description)
- 两两节点反转链表：[swap-nodes-in-pairs](https://leetcode.com/problems/swap-nodes-in-pairs)
- 判断环链表：[linked-list-cycle](https://leetcode.com/problems/linked-list-cycle)

#### 3. Stack&Queue[42:00]：
- stack：last in first out先入后出
- queue：first in first out先入先出

##### 3.1 Priority Queue(heap)优先队列[07:00]
- 二叉堆、优先队列
- [heap介绍](https://zh.wikipedia.org/wiki/%E5%A0%86_(%E6%95%B0%E6%8D%AE%E7%BB%93%E6%9E%84))


#### 4. Hash[16:00]：
- 重点：哈希函数（除留余数法易理解），桶bucket大小
- 问题：判断是否重复（[可考虑java的HashMap为什么需要key](http://www.importnew.com/7099.html)）

> “如果两个键的hashcode相同，你如何获取值对象？”    
> 当我们调用get()方法，HashMap会使用键对象的hashcode找到bucket位置，然后获取值对象。如果有两个值对象储存在同一个bucket，将会遍历链表直到找到值对象。
> 
> 重要知识点：找到bucket位置之后，会调用keys.equals()方法去找到链表中正确的节点，最终找到要找的值对象。完美的答案！
    
##### 4.1 练习：
- 有序列合并：[merge-sorted-array](https://leetcode.com/problems/merge-sorted-array)
- 正整数缺失：[first-missing-positive/](https://leetcode.com/problems/first-missing-positive)
- 3Sum：[3sum](https://leetcode.com/problems/first-missing-positive)
- 括号配对（语法分析器）：[valid-parentheses](https://leetcode.com/problems/valid-parentheses/description)

#### 总结：
- 减少时间复杂度：考虑hash函数，3Sum练习（可考虑hash时间复杂度为什么是1）
- 基本理论讲解在前面70分钟，简单介绍上述的数据结构，后面以习题为主，以张钧泳录制视频时间为准
- 下节知识点：sliding window滑动窗口
- 关键字：qinchao个人感想、Strengths Finder盖洛普、夹逼方法