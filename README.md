# -
人工智能综合实验课程作业
小组成员：冯江锴 付旭煜 黄沛吉 胡幸源 朱泽宇
使用说明：
 1、使用了path = os.getcwd()函数获取文件路径，故请将本文件置于train与test数据集所在路径运行
 2、我们使用的训练数据集中手动删除了study82样本所对应的txt文件与jpg图片（此样本只有10个label），
    并修改了study168样本中其中一个label的错误'identification'值（将'T11-T12'改为'T12-L1'）
 3、由于我们剔除了部分不符规范的样本，运行前请手动修改/删除上述两个样本，确保train数据集样本数为149，test数据集样本数为51
