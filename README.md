# mask_recognition

基于 tf.keras 的训练模型 MobileNetV2 搭建一个深度卷积神经网络进行人脸口罩检测识别, 使用 1070Ti 训练 15 个 epoch 准确率达 96%.

## 环境

* Python 3.7
* tensorflow 2.2.0
* CUDA Version 10.1.243

## 数据集

数据集全部来自于网络公开数据.

## 效果

### 佩戴口罩
![masked](https://github.com/Leviathan1995/mask_recognition/blob/master/images/masked.png?raw=true)

### 未佩戴口罩
![unmasked](https://github.com/Leviathan1995/mask_recognition/blob/master/images/unmasked.png?raw=true)

## 使用

 * `mask_recongnition_model`: 训练完成的模型, 可直接`load_model`调用
 * `mask_recognition.ipynb`: 模型训练代码
 * `mask_recognition_demo.ipynb`: 使用测试图片验证模型
