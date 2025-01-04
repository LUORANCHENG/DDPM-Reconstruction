# DDPM-Reconstruction
本代码是根据DDPM论文和网上相关参考资料，从零搭建自己的DDPM模型

# 参考资料

[DDPM原论文](https://arxiv.org/pdf/2006.11239)

[图科学实验室](https://mp.weixin.qq.com/s/Rj51LTCjbuX_bn7iALqMIg)

[大白话AI](https://www.bilibili.com/video/BV1tz4y1h7q1/?spm_id_from=333.337.search-card.all.click&vd_source=1a02178b1644ddc9b579739c3c1616b4)

[手写AI](https://www.bilibili.com/video/BV1BN41117NJ?spm_id_from=333.788.videopod.sections&vd_source=1a02178b1644ddc9b579739c3c1616b4)

# 环境配置

创建conda虚拟环境
```
conda create -n DDPM python=3.9
conda activate DDPM
```

安装pytorch
```
conda install pytorch==2.0.0 torchvision==0.15.0 torchaudio==2.0.0 pytorch-cuda=11.7 -c pytorch -c nvidia
```

安装剩下的依赖
```
pip install -r requirements.txt
```

# 注意事项

1.运行前请先修改```cfg.yaml```里面的参数。

2.如果选择的是```MNIST```或```FashionMNIST```数据集，运行代码时会自动下载数据集，无需自己手动下载。

