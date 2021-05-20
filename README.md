# Data structure and algorithm
一些关于C++中的数据结构与算法的笔记。  
  
文件"STL and Data Struecture" 主要是一些常用的STL模板类的使用说明，包括声明一个标准模板类的对象，并且访问这个对象里的数据，以及以及一些常用的方法。  
除了STL，这个文件中还包括一些其他的数据结构的笔记，比如树、二叉树、二叉查找树、平衡树AVL_tree、以及堆的笔记。这些笔记的内容主要是如何实现这些数据结构以及其相关操作，包括创建一个这样的数据结构、访问这个数据结构中的数据、增删某个数据结构中的数据。  
  
"STL and Data Structure" 的目录：
- [vector类](./STL%20and%20Data%20Structure.md#vector)：可以将vector视为一种变长数组  
- [set类](./STL%20and%20Data%20Structure.md#set)：set类的特性是自动去重并排序  
- [string类](./STL%20and%20Data%20Structure.md#string)：string是C++中比较常用的字符串类型  
- [map类](./STL%20and%20Data%20Structure.md#map)：可以将map类看作是一种关联数组，即用于存储从一种类型到另一种类型的映射的“键-值”对数组  
- [queue类](./STL%20and%20Data%20Structure.md#queue)：队列特性是“先进先出”，用push()方法添加数据，front()和back()方法访问队首队尾，pop()方法删除队首  
- [stack类](./STL%20and%20Data%20Structure.md#stack)：栈的特性是“先进后出”，用push()方法添加数据，top()方法访问队首，然后使用pop()方法删除栈顶元素  
- [栈和队列的应用](./STL%20and%20Data%20Structure.md#stack&queue)：栈与队列的使用示例，使用栈和队列实现一个简单的计算器  
- [链表的处理](./STL%20and%20Data%20Structure.md#linked_table)：C++中动态链表的创建以及一些常见操作的实现  
- [树与二叉树](./STL%20and%20Data%20Structure.md#binary_tree)：树的定义以及关于二叉树的一些常见操作的实现  
- [树的遍历](./STL%20and%20Data%20Structure.md#tree)：两种遍历树的思想，即深度优先遍历（递归法）和广度优先遍历（层序法，使用队列）  
- [二叉查找树](./STL%20and%20Data%20Structure.md#bst)：二叉查找树的实现以及关于二叉查找树的相关操作的实现  
- [平衡二叉树](./STL%20and%20Data%20Structure.md#AVL_tree)：将一个二叉查找树调整成为“平衡”的二叉查找树  
- [并查集](./STL%20and%20Data%20Structure.md#union_and_find_set)：一种用于维护集合的数据结构  
- [堆](./STL%20and%20Data%20Structure.md#heap)：堆的定义，以及一些常见方法和堆排序的实现  
- [priority_queue类](./STL%20and%20Data%20Structure.md#priority_queue)：优先队列的特性是优先级最高的元素始终放在队首，priority_queue类的底层是通过堆来实现的  
  
文件“Algorithm Notes I”的主要内容是一些算法的笔记，该文件的目录如下：
- [排序算法](./Algorithm%20Notes%20I.md#)：介绍了一些时间复杂度为`O(n^2)`的排序算法，包括冒泡排序，选择排序和插入排序
- [关于散列]()：对散列思想以及一些常规的散列算法进行了一个简单的介绍
- [递归算法]()：这部分内容主要是介绍递归算法，通过递归算法解决全排列问题以及“n-皇后”问题
- [贪心算法]()：这里主要是介绍通过子问题的最优解达到主问题的最优解的算法思想
- [二分算法]()：这一部分内容主要是通过二分算法解决一些问题，比如通过二分搜索计算$\sqrt{2}$以及快速幂
- [two pointers]()：two pointers是一种算法思想，这里介绍了一些使用这个思想来降低时间复杂度的排序算法，比如归并排序和快速排序
- [随机选择]()：承接上一节的快速排序，为了避免快速排序最糟糕情况的出现，需要使用随机选择的主要进行排序
- [搜索算法]()：介绍了几种搜索算法，用于找到某个顺序结构中某个目标的位置
