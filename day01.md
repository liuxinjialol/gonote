变量的声明
var stock,price int
常量的声明
const path string

iota，特殊常量，可以认为是一个可以被编译器修改的常量。
iota 在 const关键字出现时将被重置为 0(const 内部的第一行之前)，
const中每新增一行常量声明将使 iota 计数一次(iota 可理解为 const 语句块中的行索引)。

变量的类型
布尔类型
var b bool = true
数字类型
var age int8 = 20
字符类型
var name string = "tommy"
派生类型
(1) 指针类型（Pointer）
(2) 数组类型
(3) 结构化类型(struct)
(4) Channel 类型
(5) 函数类型
(6) 切片类型
(7) 接口类型（interface）
(8) Map 类型


运算符 &, |, 和 ^ 

