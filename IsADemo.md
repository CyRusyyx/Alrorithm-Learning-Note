# 优先队列的简单使用   



## 定义

###### 包含在头文件 <queue> 中 

```c++
#include <queue>
priority_queue<Type, Container, Functional>
```



###### 使用样例:

```c++
//升序队列 
priority_queue <int, vector<int>, greater<int> > q; 
//降序队列 
priority_queue <int, vector<int>, less<int> > q;
```



###### 常用函数:

```c++
top 访问队头元素
empty 队列是否为空
size 返回队列内元素个数
push 插入元素到队尾 (并排序)
emplace 原地构造一个元素并插入队列
pop 弹出队头元素
```
