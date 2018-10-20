# Transfer-Learning-map
- 对抗迁移
  - Partial Transfer Learning with Selective Adversarial Networks
    - 分类：基于样本的迁移学习方法；解决的是在源域的标签空间包含目标域的标签空间情况下，迁移学习的问题，其中目标域无标记数据，源域中有大量的标记数据。
    - 方法:利用gan的判别器来选择与目标域样本相近的源域实现迁移
    - 数据：
        - 1.网络架构：G_f特征提取（feature extractor）和 G_y标签预测（label predictor）.其中G_y包含判别器D
        - 2.流程：源域和目标域的数据经过cnn网络提取特征，判别器该特征是否属于源域还是目标域
        最小化源域分类器loss和
        
    - [论文地址](http://ise.thss.tsinghua.edu.cn/~mlong/doc/selective-adversarial-networks-cvpr18.pdf)
    - [代码](https://github.com/thuml)
  

