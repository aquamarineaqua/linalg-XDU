# linalg-XDU
**西安电子科技大学课程《实用大众线性代数(MATLAB版)》课后习题Python代码实现**

这里是西安电子科技大学的课程《实用大众线性代数(MATLAB版)》课后习题Python代码实现（基于Sympy）。<br>
MATLAB能非常方便地实现线性代数的工程运用问题，但考虑到MATLAB面向个人用户普及率不高，本着陈老线性代数面向计算机工具、面向工科应用的思想，以及目前Python开源、免费、日益完善的生态系统，个人试着将课程基本所有的课后习题用Python代码复现了一遍。<br>
代码主要使用了Python的Sympy模块，并用Jupyter notebook实现。<br>
作者目前也是机器学习基础努力自学中，复现的同时也学习了Python的Sympy代数计算库的应用，在代码注释里会尽量解释使用的原理方法，努力让像我这样的小白也能秒懂^ ^。<br>
课程原作者为陈怀琛教授和杨威教授，向教授们致敬，也向陈老对于线性代数教育在工科领域的开拓创新的努力致敬。<br>
<br><br>
课程原地址：https://www.icourse163.org/course/XDU-1001775006<br>
参考资料：①https://www.sympy.org/en/index.html 、②《实用大众线性代数(MATLAB版)》陈怀琛 著<br><br>

===================================================================<br><br>

关于matlab与sympy模块对比，发现sympy使用时的一些问题：<br>
1.【详见题4.5】matlab的绘图直观方便，且能方便地显示相交情况。反观sympy绘图虽然继承了matlab式的便捷的绘图方式，但是不能很好地绘制多个3d图形的情形，有时需要matplotlib取代之。<br>并且在展示相交情况方面，python的几个绘图工具表现得都不算好。<br>
2.【详见题4.17】在matlab求解矩阵行列式时，算得行列式无限接近于0但不等于0的情况下，用sympy算行列式有可能出现求得行列式为0的情况，这会造成结果的错误。题4.17解中使用了solve方法来直接求方程组解，避免因行列式算成0导致无法求解的情况。<br><br>

===================================================================<br><br>

预览：<br>
![image](https://github.com/aquamarineaqua/linalg-XDU/blob/main/image2.png)
![image](https://github.com/aquamarineaqua/linalg-XDU/blob/main/image3.png)
