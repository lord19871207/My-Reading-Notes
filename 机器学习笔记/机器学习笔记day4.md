
多变量线性回归
Python 代码：

def computeCost(X, y, theta):
    inner = np.power(((X * theta.T) - y), 2)
    return np.sum(inner) / (2 * len(X))
    
len(X)   size(X)   shape(X)
的区别。  len返回行数和列数 中较大的那一个 ， size 返回元素个数 shape 返回行列数（x,y）



一般表达式中 常用 小写字母表示向量，大写字母表示矩阵

矩阵加法
同纬度各元素相加
不同纬度矩阵无法相加

数和矩阵的乘法
矩阵中每个元素执行乘法


矩阵与向量的乘法  
结果为向量
m行n列矩阵 乘以n行一列矩阵  结果为m行一列矩阵


矩阵与矩阵相乘

