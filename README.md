# OCR-GUI-demo

![](https://github.com/17513146506/Text-recognition-of-flying-paddles/blob/main/%E4%BD%9C%E5%93%81%E6%88%AA%E5%9B%BE/1.png)
#### 介绍
图像文字识别OCR工具v1.1，含GUI界面。

![image-demo](guiocr/imgs/demo2.gif)

### 功能特性
- 文本区域检测+文字识别
- 文本区域可视化
- 文字内容列表
- 图像、文件夹加载
- 图像滚轮缩放查看
- 选取文本识别结果

#### 使用说明
运行以下命令，即可启动软件。
```shell
python main.py
```
使用流程：
1. 打开图片 
2. 选择语言模型（默认ch中文）
3. 选择文本检测+识别
4. 点击开始按钮
5. 检测完的文本区域会自动画框，并在右侧识别结果列表中显示。

#### TODO List
- 绘制区域、编辑区域
- 增加自主框选
- 增加版面分析
- 增加自动翻译
- 增加程序打包
- 增加不同格式保存
