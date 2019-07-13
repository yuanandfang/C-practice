# C++ 数据类型

## 内置类型：

布尔型  bool          字符型 char

整型 int              浮点型 float

双浮点型 double       无类型 void

宽字符型 wchar_t   typedef short int wchar_t;

## typedef声明:

可以使用 typedef 为一个已有的类型取一个新的名字。下面是使用 typedef 定义一个新类型的语法：

typedef type newname;

一个叫"newname"的“type”类型的变量。

## 枚举类型:

枚举类型(enumeration)是C++中的一种派生数据类型，它是由用户定义的若干枚举常量的集合。

如果一个变量只有几种可能的值，可以定义为枚举(enumeration)类型。

所谓"枚举"是指将变量的值一一列举出来，变量的值只能在列举出来的值的范围内。

创建枚举，需要使用关键字 enum。枚举类型的一般形式为

```
enum 枚举名{ 
     标识符[=整型常数], 
     标识符[=整型常数], 
... 
    标识符[=整型常数]
} 枚举变量;
    
```
如果枚举没有初始化, 即省掉"=整型常数"时, 则从第一个标识符开始。

例如，下面的代码定义了一个颜色枚举，变量 c 的类型为 color。最后，c 被赋值为 "blue"。
```
enum color { red, green, blue } c;
c = blue;
```
