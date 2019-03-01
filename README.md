# hello

#putty的使用方法：
下载putty
1.创建putty.exe的快捷方式到桌面
2.运行快捷方式，输入host name ,port,在saved sessions 处输入连接的名字，例如 test，保存然后关闭窗口
3.右键打开快捷方式的属性，在目标后面加上参数：
-load "test" -ssh -l {登录名} -pw {登录密码}，保存关闭

默认右键点击直接完成粘贴功能，时常造成不便，如果不想这样，可以：
第二步运行快捷方式，选择windows->selection,control use of mouse选中windows(middle extends,right brings up ,menu),后续操作照旧

#laya下如何稍微快速的定位页面元素，控制台输入
document.body.style.fontSize="16px";
var script=document.createElement("script"); 
script.setAttribute("type", "text/javascript"); 
script.setAttribute("src", "/files/game/layaair/1.7.15/laya.debugtool.js"); 
document.documentElement.appendChild(script);
script.onload = function() { Laya.DebugPanel.init() };

#浏览器中如何打印错误出现的地方，随便找个页面写入：
<script>
window.onerror = function(errorMessage, scriptURI, lineNumber,columnNumber,errorObj) { 
    alert("错误信息：" , errorMessage); 
    alert("出错文件：" , scriptURI); 
    alert("出错行号：" , lineNumber); 
    alert("出错列号：" , columnNumber); 
    alert("错误详情：" , errorObj); 
} 
</script>

#vscode中如何打开文件时时以新tab打开，而不会覆盖当前的文件：
file->preferences->settings->搜索enablePreview
出现的的两个勾选去掉：
Workbench->Editor:Enable Preview
Workbench->Editor:Enable Preview From Qucik Open


