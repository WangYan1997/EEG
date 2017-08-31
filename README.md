# EEG
## 脑电波分析背景意义
   脑是支配人和高级动物活动的司令部和信息中心，神经系统承担着感受外界刺激，产生、处理、传导和整合信号，实现各种认知活动
（如知觉、学习、记忆、情绪、语言、意思和思维等），以及运动控制等众多功能。神经系统的基本结构单元是神经元，其放电活动
 涉及复杂的物理化学过程，表现出丰富的非线性动力学行为。神经系统整体可视为由数目众多的神经元组成的庞大而复杂的信息网络，
 通过对信息的处理、编码、整合，转变为传出冲动，从而联络和调节机体的各系统和器官的功能。神经元对信息的处理和加工是神经
 元集群共同完成的，而神经元集群的同步形成较强的电信号就是脑电波。
      
   大脑意识和神经冲动的基础都是电信号，这些电信号是如何精确表达一连串复杂动作一直为科学家所热衷。一旦解析出这种信息密码就可以实现人机互动，
 甚至用电脑控制动物的行为。Miguel Nicolelis[1]在2011年10月完成了一个猕猴意识控制机械臂的试验。他们将一特殊装置的电极放置到猕猴大脑
 的运动皮质区和躯体感受皮质区，前者是发出运动信号的区域，后者负责身体其他部分传来的信息。该试验的目标是为瘫痪病人设计可以由大脑控制义肢
 行为的装置。
   该领域的研究目前处于起步阶段，特别是关于人脑的研究，远没有达到实际应用的阶段。所以进行脑电波分析的基础研究具有重要意义。
## 问题的难点
   与脑电波对颅内病变诊断不同的是，利用脑电波分析人（动物）的行为与脑电波之间的关系，并反过来通过脑电波确定或引导人的行为，具有更大的挑战性。脑电波信号是无数神经放电的混合，我们不可能也没有必要将单个神经放电分离出来。宏观意义上，控制某个特定行为或想法的脑电波是一系列众多神经放电的迭加。而我们测量所得到的脑电波信号又是由许许多多构成不同想法和控制行为的脑信号合成的。研究表明这些信号的强弱差别很大。在实现人机交互时，我们也许只关注若干个行为或思想，而对应的脑电波可能很弱。这在信号处理领域，相当于弱信号检测。在数学领域，这可能属于不适定的反问题。显然只有将脑电波信号很好地分离才能从中确定某种脑电波与某种行为相对应。这也可以理解为盲源分离或半盲信号分离问题。但通常的盲源分离技术在这里很难奏效，或误差太大，因为脑电波这一混合信号是由尺度差异很大的信号所构成的。


视觉感受区电位信号(LFP)与视觉刺激之间关系研究
## 视觉刺激
![image](https://github.com/Kevinwenya/EEG/blob/master/Full_Checker_10X6_1.bmp)
--------------------------------------------------------------------------------
![image](https://github.com/Kevinwenya/EEG/blob/master/Full_Checker_10X6_2.bmp)

