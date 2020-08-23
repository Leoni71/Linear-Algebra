# Linear-Algebra
My lecture note on linear algebra. (基于所学和参考，对线性代数的理解与总结)

_在找工作的准备过程当中，打算重温一下机器学习的一些数学基础，从线性代数开始。当前repo是自己在重新上了Coursera的[Mathematics for Machine Learning: Linear Algebra](https://www.coursera.org/learn/linear-algebra-machine-learning/home/welcome)后基于笔记和其他相关文章（例如[如何理解线性代数](https://www.zhihu.com/question/20534668)）形成的总结，一方面有助于自己加深印象和理解，另一方面希望能帮助到正在学习或复习这门课的人。个人认为国内大部分高校的线性代数课程质量还是有待提高的，不能否认老师兢兢业业授课，但是教学思路大多还是照本宣科，并不能够帮助学生系统性地理解这门学科的知识。因此，打算按照自己的理解梳理一下部分知识点，大致从某个概念的理解，性质与运算这三个方面展开，不会有全篇幅的定义或定理公式，不希望写成期末总结或Cheat sheet的形式（万一写着写着真成了也没办法），想看定义还是查书比较好。不到之处既可（最好）联系本人也可忽略不见_

## Menu
[向量](https://github.com/Leoni71/Linear-Algebra#%E5%90%91%E9%87%8F-vector)

## 向量 (Vector)
顾名思义，即“有方向的量”，用中学教材的说法就是--同时具有大小与方向的量，与其相对的就是**标量(scalar)** 。

通常提到向量，指的是列向量，行向量视为（列）向量的转置
向量本身没有什么特殊的性质，也容易理解，需要留意的是，如同数轴有单位刻度一样，向量中的每个**元素(element)** 可以理解为n个**基向量/单位向量(basis)** 的叠加。
如：

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.1.png)

当然，我们默认这里的两个单位向量是正交的(orthogonal)

与此同时，也就能够通过勾股定理知道向量的长度，也就是一般所说的**向量的模(modulus)** 

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.0.png)

由此也引出了有关向量的基本运算(operations on vector)和一些性质：

#### 向量与标量相乘(scalar multiplication):

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.2.png)

#### 向量加减(addition&subtraction):

平行四边形法则 以及 减法是加法的逆运算
![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.3.png)

#### 内积(inner product): 

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.4.png)

#### Associativity over Addition & Scalar Multiplication: 

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.5.png)

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.6.png)

#### Commutativity over Addition & Multiplication:

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.7.png)

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.8.png)

#### Distributivity:

![image](https://github.com/Leoni71/Linear-Algebra/blob/master/img/1.9.png)

