# Auto-control
此设计是一个单片机控制系统，在汽车做左转弯，右转弯，紧急刹车，停靠等，实现对汽车信号指示灯的控制，主要是对单片机的并行输入/输出口电路的应用，通过I/O口控制发光二极管的亮﹑灭﹑闪烁，加上一些复位电路﹑按键电路﹑驱动电路来模拟汽车灯的功能。
汽车在驾驶时有左转弯、右转弯、刹车、合紧急开关、停靠等操作。在左转弯或右转弯时，通过转弯操作杆应使左转开关或右转开关合上，从而使左头灯、仪表板左转弯灯、左尾灯或右头灯、仪表板右转弯灯、右尾灯闪烁；合紧急开关时要求前面所述的6个信号灯全部闪烁；汽车刹车时，两个尾灯点亮；如正当转
弯时刹车，则转弯时原应闪烁的信号灯仍应闪烁。以上闪烁，都是频率为1Hz的低频闪烁；在汽车停靠而停靠开关合上时，左头灯、右头灯、左尾灯、右尾灯按频率为30Hz的频率闪烁。
