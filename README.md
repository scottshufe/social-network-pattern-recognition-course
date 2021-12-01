# 社交媒体模式识别课程
## 主要使用的Python包:

- **networkx** 官方文档: https://networkx.github.io/documentation/stable/

## 参考数据集
- 斯坦福网络分析项目（SNAP）数据集: http://memetracker.org/data/index.html

## 第二讲实验代码与数据:
- 第二讲实验演示.ipynb:
1. 网络的生成与输出
2. 获取网络的邻接矩阵
3. 获取节点的邻居
4. 加权图最短路径算法（迪杰斯特拉）
5. 在真实网络数据集email-Eu-core上进行简单分析
6. 中心性计算

- 数据集：email-Eu-core.txt
## 第三讲实验代码
- 第三讲实验演示.ipynb:
1. networkx网络模型生成的四种方法
2. 网络图的可视化
3. 求网络图的最大连通模块
## 第四讲实验代码
- 第四讲实验演示.ipynb:
1. 团问题
2. 群组发现算法
3. 切割

- 数据集: football, cora
## 链路预测代码
- cora_link_prediction.ipynb
- 数据集：Cora
- 算法：Local information (jaccard coefficient, common neighbor, adar adamic index), node feature similarity, deepwalk, gcn