# ocr_ctpn_crnn_windows
Chinese+English+Numbers text-detection and text-recognization algorithms based on CTPN+CRNN especially on Windows
# 前言
Windows下，ctpn文本检测+crnn文本识别，形成对一张照片的检测识别。
# 运行环境
请阅读requirement.txt，其中tf和torch都需要，tf的版本要1.7.0不能安装最新的
# 测试
ctpn部分测试 --> crnn_test.py  
crnn部分测试 --> ctpn_test.py  
整体测试 --> test.py  
“互联网+”比赛 --> for_internet.py 修改其中的单张测试部分的im_path,然后命令行运行即可
# 预训练模型
链接：https://pan.baidu.com/s/1Yjf3qMi82Qmy2vGTTuHZmA 
提取码：i753 

# Reference
CTPN+Densenet OCR Solution https://github.com/YCG09/chinese_ocr
文本识别 https://github.com/yinchangchang/ocr_densenet  
自动文本生成程序，用于训练集的生成 https://github.com/Sanster/text_renderer

