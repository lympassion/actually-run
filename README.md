# actually-run
代码实际操作

**date:**  2023/5/21

**Motivation**: 论文阅读过程中作者提到的算法，需要自己复现，不管是作者有没有提供源代码，复现过程中都会遇到各种各样的问题，为了避免此过程的重复，大家可以提交代码从最开始到最后实际跑通过程的记录，方便彼此交流学习。



### 代码提交格式

1. 首先自己的代码都放到一个目录，如`ASTGCN`，找一个领域，如`traffic forecasting`，并将`ASTGCN`放入对应领域下，不能重复创建领域。

2. 以`ASTGCN`为例，必须包含以下文件

   * `run.txt`，运行命令，如`python train.py --config configurations/PEMS08.conf --force True`.  ✅

   * `requirements.txt`。*可以用`pipreqs ./ --encoding=utf8`生成* 	✅

   * `record.md`。记录代码复现过程。  ✅

     > 1）如果是直接运行前人的代码，该文件必须给出前人代码连接。
     >
     > 2）主要是自己遇到了哪些问题（代码报错），如何解决的（改动描述），该记录必须具有**新手可操作性**。

   * 原论文  ✅

   * 数据集  ✅

     > 如果数据集太大或者不方便提供，也需要提供数据集样例和数据集说明。

   * 实验结果  ✅







