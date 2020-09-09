# 总决篇

## 什么是递归？

（来自labladong）

Heap(堆)的用法

申明size，堆的插入规则：
PriorityQueue<Character> heap = new PriorityQueue<>(size, (a, b) -> Integer.compare(letters[b], letters[a]));

<>里面的是计数的对象，PQ后面的是比较的方法。

注意用的是尖头,compare前为先。

上图是b-a > 0 的时候b先输出。

堆的方法：
1. heap.offer() : 插入

2. heap.poll(): 拿出

3. heap.peak(): 看最上面



