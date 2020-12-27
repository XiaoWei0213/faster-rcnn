### 自己动手实现Faster RCNN

faster rcnn的思路：

![image-20201227155104784](C:\Users\24284\AppData\Roaming\Typora\typora-user-images\image-20201227155104784.png)

（1）使用VGG16或者ResNet提取图片的特征

（2）RPN网络对目标区域进行提取

（3）ROI Pooling进行最后的分类和回归