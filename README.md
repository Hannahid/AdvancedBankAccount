# AdvancedBankAccount

## _1_ 类和对象初步完成项目搭建
> 完成项目类的设计，初步实现基本功能（开户、存钱、取钱、结算利息)
## _2_ 数据的共享与保护改进
> 1.为SavingsAccount类增加一个静态数据成员total,用来记录各个账户的总金额，并为其增加相应的静态成员函数getTotal用来对其进行访问。<br><br>
> 2.将SavingsAccount类的诸如getBalance,accumulate这些不需要改变对象状态的成员函数声明为常成员函数。  <br><br>
> 3.对程序结构进行调整：将SavingsAccount类从主函数所在的源文件中分开，建立两个新的文件account.h和account.cpp,分别存放SavingsAccount类的定义和实现。<br>
## _3_ 数组、指针与字符串改进
> 将描述账号的数据类型由int改为了string，将描述日期的数据类型由int改为了新定义的Date类，并且为deposit,withdraw和settle三个函数都增加了一个用来存储该笔账目说明信息的string型的desc参数，并且增加了一个专用于输出错误信息的error函数。
## _4_ 继承与派生改进
## _5_ 多态性改进
## _6_ 群体类和群体数据的组织改进
> 
## _7_ 泛型程序设计与C++标准模板库改进
## _8_ 流类库与输入输出改进
## _9_ 异常处理改进
