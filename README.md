# hello

#putty的使用方法：
下载putty
1.创建putty.exe的快捷方式到桌面
2.运行快捷方式，输入host name ,port,在saved sessions 处输入连接的名字，例如 test，保存然后关闭窗口
3.右键打开快捷方式的属性，在目标后面加上参数：
-load "test" -ssh -l {登录名} -pw {登录密码}，保存关闭

默认右键点击直接完成粘贴功能，时常造成不便，如果不想这样，可以：
第二步运行快捷方式，选择windows->selection,control use of mouse选中windows(middle extends,right brings up ,menu),后续操作照旧