# millemeter-radar-and-gesture-detection
prp project

第一次组会记录
一 现有的手势识别产品
1.Google Soli project:
采用基于毫米波雷达的Soli手势识别技术
Soli雷达的作用：发射信号并从天线接收信号，将接收到的信号进行低通过滤
Soli雷达实现了：微型化和低功耗
Soli雷达的技术关键：采用了FMCW调制格式（具体技术原理可见NVDIA论文fmcw_rd15.pdf）

Google对手势识别算法进行了一系列强大优化，Soli project在第三方开发者处已经拓展出了很多应用。

Question to explore: 
在整个Soli技术中我们所研究的毫米波雷达参与了手势识别过程的哪些步骤？采用的雷达的组成结构？这些组成结构又分别负责什么？有哪些模拟电路的元器件？
搜索所用英飞凌的芯片型号，可以从此入手研究。

2.Samsung的新专利（在触摸板附近做空中手势）
Question to explore: 可能由毫米波雷达实现，可以跟进查看具体专利情况


二 关于功率
可以考虑射频电路功率降低的方法：赵所说的锁相环论文等

主要考虑在雷达收发（RX/TX）阶段考虑怎样降低功耗
Question to explore: 整个信号收发过程涉及哪些步骤？哪些可以省去？——可以考虑手势识别的容错率较大/ 可以收集不同毫米波雷达的data sheet比较性能表现



