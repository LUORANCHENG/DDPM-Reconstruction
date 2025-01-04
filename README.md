# DDPM-Reconstruction
本代码是根据DDPM论文和网上相关参考资料，从零搭建自己的DDPM模型

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
