# C&C++ 学习笔记
## C语言
### 一、数据类型
|     类型     |                |        |                   | 所占内存/字节 |                 表示范围                 |
| :----------: | :------------: | :----: | :---------------: | :-----------: | :--------------------------------------: |
|   基本类型   | 字符类型(char) |        |                   |       1       |                 -128~127                 |
|       ^      |    数值类型    |  整型  |   短整型(short)   |       2       |               -32768~32767               |
|       ^      |        ^       |    ^   |     整型(int)     |       4       |          -2147483648~2147483647          |
|       ^      |        ^       |    ^   |    长整型(long)   |  4(32位系统)  |          -2147483648~2147483647          |
|       ^      |        ^       |    ^   |         ^         |  8(64位系统)  | -9223372036854775808~9223372036854775807 |
|       ^      |        ^       |    ^   | 长整型(long long) |       8       | -9223372036854775808~9223372036854775807 |
|       ^      |        ^       | 浮点型 |  单精度型(float)  |       4       |                     /                    |
|       ^      |        ^       |    ^   |  双精度型(double) |       8       |                     /                    |
|   构造类型   |      数组      |        |                   |       /       |                                          |
|       ^      | 结构体(struct) |        |                   |       /       |                                          |
|       ^      |  共用体(union) |        |                   |       /       |                                          |
|       ^      | 枚举类型(enum) |        |                   |       /       |                                          |
|   指针类型   |                |        |                   |       /       |                                          |
| 空类型(void) |                |        |                   |       /       |                                          |
### 二、运算符
|优先级|运算符|含义|运算对象个数|结合方向|
|:---:|:---:|:---:|:---:|:---:|
|1|( )|圆括号|/|从左到右|
|^|[]|数组下标运算符|^|^|
|^|->|指向结构成员运算符|^|^|
|^|.|结构体成员运算符|^|^|
|2|!|逻辑非运算符|1个（单目运算符）|从右到左|
|^|~|按位取非运算符|^|^|
