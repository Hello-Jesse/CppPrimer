# 第1章 开始

C++常用编译器：GNU(g++)和微软Visual Studio编译器(cl) 

​	GNU: -Wall

​	cl: /W4

gcc & g++现在是gnu中最主要和最流行的c & c++编译器 。
g++是c++的命令，以.cpp为主，对于c语言后缀名一般为.c。这时候命令换做gcc即可。

编译：g++ -o test1_1.exe test1_1.cpp

运行： .\test1_1

编译器可以检查出：

语法错误（syntax error）

类型错误（type error）

声明错误（declaration error）

文件重定向 $ addItems <infile >outfile

# 第二章 变量和基本类型	

![image-20220602063608016](C:\Users\87975\AppData\Roaming\Typora\typora-user-images\image-20220602063608016.png)

可寻址的最小内存块称为“字节（byte）”，

存储的基本单元称为“字（word）”，它通常由几个字节组成

如何选择类型：

执行浮点数运算选用double，这是因为float通常精度不够而且双精度浮点数和单精度浮点数的计算代价相差无几。事实上，对于某些机器来说，双精度运算甚至比单精度还快。
