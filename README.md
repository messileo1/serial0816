# serial0816

0.写脚本 
1.roscore 
2.socat生成虚拟串口，端口号需为1。为的是防止其他端口号还需要重新改代码并编译。可以把终端关了再打开然后socat，多试几次 
3.把代码git下来 
4.根据生成的端口号去配置minicom（三处），并且让minicom执行脚本，相应的终端不能关闭。 
5.到代码的workspace下面：依次执行catkin_make source命令 roslaunch launch/start_serial.launch命令
