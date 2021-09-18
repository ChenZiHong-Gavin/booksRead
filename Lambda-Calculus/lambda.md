# λ演算

无类型纯λ演算

## 历史

希尔伯特 公理系统的相容性

许多数学家都在致力于给整个数学建立一个一致的公理基础

Alonzo Church λ演算

给逻辑学提供一个基础

它可以被看作一个简单的程序设计语言，也可以被看做一个数学对象，用于推导证明一些问题。



## 数学理论

我们从数学的函数讲起，因为我们大家都很熟悉函数：
$$
f(x,y)=x\times x+y\times y
$$
当然，我们也可以不需要f这个名字：
$$
(x,y)\rightarrow x\times x+y\times y
$$
我们把它作为一个函数赋值
$$
((x,y)\rightarrow x\times x+y\times y)(3,4)=25
$$
有下面一种形式的映射
$$
x \rightarrow(y \rightarrow x \times x+y \times y)
$$
我们现在来映射一下试试看
$$
((x \rightarrow(y \rightarrow x \times x+y \times y))(3))(4)
$$
结果还是一样的

其实，任意多参数函数都可以转换成单参数函数，这个转换叫柯里化





