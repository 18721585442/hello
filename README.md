# hello

#putty��ʹ�÷�����
����putty
1.����putty.exe�Ŀ�ݷ�ʽ������
2.���п�ݷ�ʽ������host name ,port,��saved sessions ���������ӵ����֣����� test������Ȼ��رմ���
3.�Ҽ��򿪿�ݷ�ʽ�����ԣ���Ŀ�������ϲ�����
-load "test" -ssh -l {��¼��} -pw {��¼����}������ر�

Ĭ���Ҽ����ֱ�����ճ�����ܣ�ʱ����ɲ��㣬����������������ԣ�
�ڶ������п�ݷ�ʽ��ѡ��windows->selection,control use of mouseѡ��windows(middle extends,right brings up ,menu),���������վ�

#laya�������΢���ٵĶ�λҳ��Ԫ�أ�����̨����
document.body.style.fontSize="16px";
var script=document.createElement("script"); 
script.setAttribute("type", "text/javascript"); 
script.setAttribute("src", "/files/game/layaair/1.7.15/laya.debugtool.js"); 
document.documentElement.appendChild(script);
script.onload = function() { Laya.DebugPanel.init() };

#���������δ�ӡ������ֵĵط�������Ҹ�ҳ��д�룺
<script>
window.onerror = function(errorMessage, scriptURI, lineNumber,columnNumber,errorObj) { 
    alert("������Ϣ��" , errorMessage); 
    alert("�����ļ���" , scriptURI); 
    alert("�����кţ�" , lineNumber); 
    alert("�����кţ�" , columnNumber); 
    alert("�������飺" , errorObj); 
} 
</script>

#vscode����δ��ļ�ʱʱ����tab�򿪣������Ḳ�ǵ�ǰ���ļ���
file->preferences->settings->����enablePreview
���ֵĵ�������ѡȥ����
Workbench->Editor:Enable Preview
Workbench->Editor:Enable Preview From Qucik Open


