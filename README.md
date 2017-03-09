### caffe-test-script
一些常见的与caffe有关的测试脚本   


lfw-evaluate-new.py:   
使用caffe的python接口提取指定layer的特征并在lfw上进行人脸验证精确度的测试

label-original.txt:   
根据lfw官方pair.txt中6000对数据修改之后的label标签  
其中0代表不是同一个人，1代表是同一个人
