# Recognition
面部表情识别-人工智能大作业

## 部署
本项目基于Python3和Keras2（TensorFlow后端），具体依赖安装如下（本人使用conda虚拟环境）。
```
git clone https://github.com/cutedr/Recognition.git
cd Recognition
conda create -n FER python=3.7 -y
conda activate FER
pip install -r requirements.txt
```
## 训练
运行train.py即可进行训练，默认数据集为fer2013
## 检测
1.运行gui.py即可使用GUI界面选择图片检测
2.运行recognition_camera即可使用摄像头实时检测
