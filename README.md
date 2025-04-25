# Code


### Requirements

Recommended:  create an Anaconda environment

（1）mindquantum==0.9.11

    https://www.mindspore.cn/mindquantum/docs/zh-CN/r0.9/mindquantum_install.html

（2）mindspore==2.2.12

    https://www.mindspore.cn/install/


### Instructions

（1）Graphs： Minimum vertex cover graph data

    https://github.com/QAOAKit/data/tree/bdd9220486b456ce93727d75ede9308a4fc8a9c8/qaoa-dataset-version1/Graphs

Specifically from：

    https://users.cecs.anu.edu.au/~bdm/data/graphs.html

（2）Graph Data： Optimization parameters

opt.csv: Optimization parameters for all graphs in Graphs(p=7、8、9).

（3）Code Files

1_.py : Graph data format conversion.

2_.py : QAOA solves mvcp to get the optimal parameters.

3_.py : Scaling parameters to get the optimal transferable parameters.

4_.py ：Selecting the intermediate parameters.

5_.py : The scaling parameters are used as the initial parameters of WMVCP and solved.

