# Numpy
NumPy是一个Python库，用于在Python中进行高性能科学计算和数据分析。它提供了多维数组对象、各种派生对象（如掩码数组和矩阵）、快速的数学运算函数以及线性代数、傅里叶变换和随机数生成函数等工具。NumPy被广泛应用于各种领域，如数据分析、机器学习、科学计算、图像处理等。其核心是ndarray对象，可以高效地存储和操作大规模数据集。

NumPy提供了众多的方法和函数，以下是一些常用的：

* 创建数组：np.array(), np.zeros(), np.ones(), np.arange(), np.linspace()
* 数组操作：索引和切片、数组形状变换、数组拼接、数组分裂
* 数组计算：加减乘除、矩阵乘法、广播运算、逻辑运算
* 统计计算：求和、均值、标准差、方差、最小值、最大值等
* 线性代数：矩阵求逆、行列式、特征值、特征向量、奇异值分解等
* 随机数生成：np.random模块中提供的各种随机数生成函数
* 文件读写：np.load(), np.save(), np.loadtxt(), np.savetxt()等
* 高级应用：FFT变换、卷积操作、图像处理、时间序列分析等。

以上只是NumPy的一部分功能，它还有许多其他强大的功能可以满足科学计算和数据分析的需求。

----

## 一.创建数组
np.array()：使用给定的列表、元组或其他序列创建一个ndarray数组。
