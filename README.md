# daily-paper-reading

Short and daily paper reading

2022-11

<table style="width:100%">
  <tr>
    <th>Name</th>
    <th>Number</th>
    <th>Total</th>
  </tr>
  <tr>
    <td>Qingyue Wang</td>
    <td>0</td>
    <td rowspan=16>2</td>
  </tr>
  <tr>
    <td>Yanhe Fu</td>
    <td>0</td>
  </tr>
  <tr>
    <td>Wanyue Zhang</td>
    <td>2</td>
  </tr>
</table>

(Students are sorted by grade)


### No.3-ACL-2019-Towards **Empathetic** Open-domain Conversation Models: a New Benchmark and Dataset

<br>2022-11-08</br>
***title*:**
Towards **Empathetic** Open-domain Conversation Models: a New Benchmark and Dataset

*Authers*:

 Hannah Rashkin, Eric Michael Smith, Margaret Li, Y-Lan Boureau

*institute*: 

Paul G. Allen School of Computer Science & Engineering, University of Washington； Facebook AI Research

*Topic*: 

Empathetic Open-domain Conversation

***Motivation*:** 

对话主体面临的一个挑战是识别对话伙伴的感受并做出相应的回应，人工智能系统缺乏合适的公共可用数据集进行训练和评估。这项工作为移情对话生成和移情对话提出了一个新的基准，

***Details*:** 

![image-20221109134811583](C:\Users\23749\AppData\Roaming\Typora\typora-user-images\image-20221109134811583.png)

### No.4-Generating Responses with a Specific Emotion in Dialog

Zhenqiao Song, Xiaoqing Zheng, Lu Liu, Mu Xu and Xuanjing Huang

​		本文来自复旦大学和加州大学Santa Barbara分校。如果对话系统可以表达具体的情感，那么对可用性和用户满意度将会有很大提升，经过调研我们发现，至少有两种方式通过语言来表达情感，一是显式地采用较强的情感词，二是隐式地结合不同中立词来增加情感体验的强度。本文提出一个情感对话系统（EmoDS），一方面可以生成一致的、有意义的回复，另一方面可以显式或隐式地表达情感。实验表明，EmoDS在BLEU、多样性和情感表达质量上均优于baseline。

​		问题定义：给定输入的post和情感e，生成回复。具体结构如下，左下角利用双向LSTM对post进行编码，右下角利用attention得到当前的情感（显式地），左上角利用LSTM基于编码和情感进行解码生成回复（生成每个词的时候区分普通词和情感词），右上角预测生成回复的情感（仅用于训练过程）。模型的损失函数包括两部分：生成回复的交叉熵损失、情感预测的损失。

​	![image-20221107163832243](C:\Users\23749\AppData\Roaming\Typora\typora-user-images\image-20221107163832243.png)

实验结果样例如下：

![image-20221107163755191](C:\Users\23749\AppData\Roaming\Typora\typora-user-images\image-20221107163755191.png)



**by Wanyue Zhang**


