# FashionMNIST Challenge大作业

### 一. [数据集划分成训练集、验证集、测试集并存储成TFRecord文件](https://github.com/m-L-0/17b-MaYanbo-2015/blob/master/FashionMNIST_Challenge/Transtotfr.ipynb)
        通过官网提供的读取数据方法读取数据后，自己定义函数进行TFRecord格式的转化

### 二. [TFRecord中的样本数据进行可视化](https://github.com/m-L-0/17b-MaYanbo-2015/blob/master/FashionMNIST_Challenge/Transtotfr.ipynb)
        利用matplotlib包进行可视化
        先将训练集中的image与label的提取出来，再通过matplotlib方法可视化样本数据，可通过图片结果看出裤子 鞋等特征
        
### 三. [设计并训练KNN算法对图片进行分类](https://github.com/m-L-0/17b-MaYanbo-2015/blob/master/FashionMNIST_Challenge/knn.ipynb)
        先定义读取TFRecord格式数据的函数,再利用读取的数据训练KNN算法进行分类
        KNN，英文全称为K-nearst neighbor，中文名称为K近邻算法,是通过测量不同特征值之间的距离进行分类
        KNN算法中利用到欧式距离公式：d=sqrt( ∑(xi1-xi2)^ ) i=1,2..n 
        
### 四. [设计并训练K-Means算法对图片进行聚类](https://github.com/m-L-0/17b-MaYanbo-2015/blob/master/FashionMNIST_Challenge/KMeans.ipynb)
        1. 随机选取k个聚类质心点为 u1,u2,...uk
        2. 重复下面过程直到收敛:
           对于每一个样本i计算其应该属于的类 
           对于每一个类 uj，重新计算该类的质心

### 五. [设计并训练CNN算法对图片进行分类](https://github.com/m-L-0/17b-MaYanbo-2015/blob/master/FashionMNIST_Challenge/CNN.ipynb)
        1. 下载并加载数据。
        2. 定义四个函数，分别用于初始化权值W，初始化偏置项b, 构建卷积层和构建池化层。
        3. 构建网络。整个网络由两个卷积层（包含激活层和池化层），一个全连接层，一个dropout层和一个softmax层组成。
        4. 训练数据并验证。
