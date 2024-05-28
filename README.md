# FMOT（Field and Matrix Operator Tool）
FMOT的matlab基础开发版本，目前主要功能是simple和piso算法的实现。

可以新建立main.m把test中的.mlx内容复制到新的main.m中，调试更方便。

方程构建和组装的风格是参考OpenFOAM的方式，希望能对OF的初学者有一定的帮助。

算子离散的实现是采用全向量化的方式进行组装，需要一定的基础来理解。

当前大部分封装函数具有帮助说明，可右键点击查看。

注意：

    对流项的边界条件目前存在一定问题，对所有第一类和第二类边界条件不完全通用；
    
    SIMPLE的残差输出colorbar存在问题；
    
    PISO的残差类的实现是不完整的，请不要使用。
    
    test文件中的LidDriven(p)存在一点问题，先不要使用。

有问题可以联系：fmot_2024@163.com
