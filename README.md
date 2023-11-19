# CLF-CBF-QP Toolbox
## QP求解使用了yalmip工具箱。因此把所有文件添加到MATLAB搜索路径即可。

## 该工具箱给出基类ControlAffineSystem，已经实现了QP相关算法，但动态系统System，CLF，CBF的定义均为空实现，因此需要创建类并继承该基类，并给出相关函数的具体实现。工具箱提供一个双积分模型DI的案例仅供参考。

## 另外提供没有基于工具箱的单级倒立摆（CLF-QP），车辆模型（CBF-QP），自适应巡航控制（CLF-CBF-QP）仿真案例。

## 论文引用
胡腾飞. 基于控制障碍函数的安全攸关控制[D]. 东北大学, 2022.

## 其他相关论文
1. Z. Wang, T. Hu and L. Long, "Multi-UAV Safe Collaborative Transportation Based on Adaptive Control Barrier Function," in IEEE Transactions on Systems, Man, and Cybernetics: Systems, vol. 53, no. 11, pp. 6975-6983, Nov. 2023, doi: 10.1109/TSMC.2023.3292810.
2. 龙离军, 胡腾飞. CLF-CBF-QP新形式下非线性系统的安全攸关控制与优化[J]. 控制理论与应用, 2022, 39(8):1387-1396.
