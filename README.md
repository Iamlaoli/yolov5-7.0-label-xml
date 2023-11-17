# yolov5-7.0-label-xml

### 使用yolov5-7.0实现的一个预标注程序

1. 将预训练好的权重放入models/weights中，修改demo.py文件中的(.pt)；

2. 在demo.py中配置需要标注的图片路径和要保存xml路径；
   
3. 修改config.py中的权重路径；

4. 运行demo.py文件生成xml标签；

5. 使用labelimg进行微调；

本项目基于yolov5-7.0推理进行修改,仿照yolov5-label-xml-main进行编写；



### 配置说明：

见 requirements.txt 环境配置
