ѧϰjavascript												
												
һ�����÷�ʽ  												
												
	"1��ֱ�����ã�ʹ��script��ǩ��������head,body,body�⣩"											
	<script></script>											
												
	2������js�ļ�ʹ��											
	<script src="Login.js"></script>											
												
�����½�����������												
												
	1������ 	������ݸ�ֵ�Զ�ȷ�ϱ������ͣ�										
	var a = 2											
												
	2������											
	"var people = {name:""nancy"",sex:""wenam"",age:18}"											
												
�������												
	1�������ҳ��											
	document.write();											
												
	<script>											
	 document.getElementById("demo").innerHTML = 5 + 6;											
	</script>											
												
	2������ڵ���											
	alert(����һ�������);											
												
	comfirm("����һ����ʾ��");											
												
	proptm("��Ҳϲ��������")											
												
	3����������������̨ 											
	console.log();											
												
�ġ�����												
	function functionName(����){ִ������}											
												
�塢��ȡָ��Ԫ��												
												
	1����ID��ȡԪ��											
	var a = document.getElementById(����)											
												
	2����class����ȡ											
	var a = document.getElementByClassName(����);											
												
	3������ǩ����ȡ											
	var a = document.getElementByTagName('')[n];											
	nָ�ñ�ǩ�ĵڼ�������0��ʼ��											
												
	4����ȡ����class��Ϊintro��p��ǩ											
	var x = document.querySelectorAll("p.intro");											
												
����ͨ��js�ı�Ԫ��css��ʽ												
												
	<p id="p1">����p1��ǩ</p>											
												
	<script>											
	var a;											
	function fun(){											
		a = document.getElementById("p1");										
		this.style.background="#000"										
	}											
	</script>											
												
	�Ϳ��԰�p1�ı�����Ϊ��ɫ											
