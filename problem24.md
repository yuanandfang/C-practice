# CCF试题练习笔记

二十四点问题

#include<stack> 包含栈的头文件

栈的定义 

    * 栈被实现为容器适配器，它是使用特定容器类的封装对象作为其基础容器的类，
    * 提供了一组特定的成员函数来访问其元素。 元素从特定容器的“后面”被推入/弹出，这被称为堆栈的顶部。


## Member functions 成员函数
### (constructor) 构造函数
Construct stack (public member function )
### empty 空
Test whether container is empty (public member function )
### size 返回栈的大小
Return size (public member function )
### top  访问下一个元素
Access next element (public member function )
### push 推入新的元素
Insert element (public member function )
### emplace 构造和插入元素
Construct and insert element (public member function )
### pop 移除顶部元素
Remove top element (public member function )
### swap 交换
Swap contents (public member function )


## Non-member function overloads 非成员函数重载

### relational operators 关系运算符

### Relational operators for stack (function ) 堆栈(函数)的关系运算符
 
### swap (stack)  交换(堆栈)
Exchange contents of stacks (public member function ) 堆栈的交换内容（公共成员功能）

## Non-member class specializations
### uses_allocator<stack>
### Uses allocator for stack (class template 类模板 )


版权声明：本文为CSDN博主「wardseptember」的原创文章，遵循CC 4.0 by-sa版权协议，转载请附上原文出处链接及本声明。

原文链接：https://blog.csdn.net/wardseptember/article/details/80642846
