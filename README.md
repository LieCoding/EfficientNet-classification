# EfficientNet-classification
大赛主页：https://competition.huaweicloud.com/information/1000040170/introduction  
使用EfficientNet构建的分类模型，准确率98.4%，  

比赛时候使用了数据扩充，各种调参得到了98.4% 

后续参考了网上的思路 将原来的输入尺寸从224改为500， 
不使用数据扩充，使用V100-32g的配置训练了大约3小时也得到了98.4%的准确率， 
代码为文件eff_b7_input_500.ipynb 
可能是把图片压缩到224的尺寸，损失掉了太多的信息 
后续还会优化下去 
