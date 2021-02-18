# 接口和类型兼容性

# 扩展类型-接口

> 扩展类型：类型别名、枚举、接口、类

Typescript的接口：用于约束类、对象、函数的契约（标准）

契约（标准）的形式：
    - API文档，弱标准
    - 代码约束，强标准

和类型别名一样，接口，不出现在编译结果中

1. 接口约束对象
2. 接口约束函数

**接口可以继承**

可以通过接口直接的继承，实现多种接口的组合

使用类型别名可以实现类似的组合效果，需要通过```&```，它叫做交叉类型

他们的区别
- 子接口不能覆盖父接口的成员
- 交叉类型会把相同成员类型进行交叉