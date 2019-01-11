# 项目名称
合肥工业大学 计算机与信息学院 情感计算研究所 自然语言处理团队 多模态情感语料库
# Sentiment Classification Via Galvanic Skin Response Based on Deep Learning Models 

# Table of Contents  

- [Introduction](#intro1)
- [MDSTC](#mdstc2)
- [Preprocessed](#PROCESS3)
- [Denoising](#denoising4)
- [Contact](#Contact5)

<a name="intro1"></a>
## Sentiment Classification Via Galvanic Skin Response ##
### Introduction
We collected a a multimodal dataset for sentiment classification, the dataset is showed in MDSTC. The Facial Expression of the MDSTC folder contains facial expressions of volunteers watching emotional stimulation clips. The GSR and Pulse File folder contains Galvanic Skin Response and Pulse of volunteers. In this paper, we used Galvanic Skin Response for sentiment classificaiton


<a name="mdstc2"></a>
## MDSTC ##
In this section, we will show the detail of MDSTC.
This image shows the Galvanic Skin Response and Pulse of volunteers watching six types of inspired videos.

![image](https://github.com/HTDPNJ/Sentiment-Classification-Via-Galvanic-Skin-Response-Based-on-Deep-Learning-Models/blob/master/Pic/git.png)

This image shows the facial expressions of volunteers watching six types of inspired videos. In the XML file, "Person_info" record the personal information of volunteer, "Film_name" denotes the name of stimulation clips, "PIDIAN" recorded the Galvanic Skin Response, "MAIBO" recorded the pulse.

![image](https://github.com/HTDPNJ/Sentiment-Classification-Via-Galvanic-Skin-Response-Based-on-Deep-Learning-Models/blob/master/Pic/xml.png)

<a name="PROCESS3"></a>
## Preprocessed ##
If a small amount of data is missing, we fill it with adjacent data. If a large amount of data is missing in a, we delete the data.


<a name="denoising4"></a>
## Denoising and Data standardization ##
We use the Butterworth filter to denoise the signal, enhance the useful information, and recover the information degradation caused by the interference.
This image shows the Pulse of volunteer.

![image](https://github.com/HTDPNJ/Sentiment-Classification-Via-Galvanic-Skin-Response-Based-on-Deep-Learning-Models/blob/master/Pic/maibo.png)

This image shows the raw GSR and GSR after denoising and data standardizationof volunteer.
![image](https://github.com/HTDPNJ/Sentiment-Classification-Via-Galvanic-Skin-Response-Based-on-Deep-Learning-Models/blob/master/Pic/data_denoise.png)
Here, you can get more data, link：https://pan.baidu.com/s/1JZCpRxmHl_zeR58AOUrJKg code：pbkr   
If you need more data, please connect us.    

<a name="Contact5"></a>
## Contact ##
[Xiao Sun] E-mail address: (sunx@hfut.edu.cn);   Emotional Computing and Advanced
Intelligent Machine Lab, School of Computer and Information, Hefei University
of Technology, Hefei, Anhui, China.    
[Tao Hong] E-mail address: (TOliverQueen1@163.com)      

