三星OneUI时钟app在响铃前会对通话状态进行检测，如果检测到在通话中则不会响铃，此模块可以解除通话中闹钟不提醒不响铃的限制，原理是简单的hook了app里对通话状态的检测函数的返回值。

作用域：默认即可

另外，通话时用听筒模式会导致闹钟声音过小，建议闹钟要开震动。