# gpib-cwinstr
使用labview提供的cwinstr.ocx控件来操作GPIB设备

常用的操作GPIB的方式是调用gpib.dll , 但是需要初始化很多必须的函数和参数, 就会很麻烦.
labview也提供了ocx控件的操作方式, 利用cwinstr可以很方便的操作gpib设备, 遗憾的是这个控件官方并没有提供很好的技术文档, 完全需要自己去摸索.
我这里列举的是自己摸索出来的一些方法 , 希望能帮助到用到的人.
aardio编程软件中操作ocx控件也很方便, 只需要 com.creatobj() 即可.
本文首发自: https://www.chengxu.xyz/t/385
