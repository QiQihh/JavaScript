学习javascript												
												
一、运用方式  												
												
	"1、直接套用，使用script标签（可以在head,body,body外）"											
	<script></script>											
												
	2、链接js文件使用											
	<script src="Login.js"></script>											
												
二、新建变量，对象												
												
	1、变量 	（会根据赋值自动确认变量类型）										
	var a = 2											
												
	2、对象											
	"var people = {name:""nancy"",sex:""wenam"",age:18}"											
												
三、输出												
	1、输出在页面											
	document.write();											
												
	<script>											
	 document.getElementById("demo").innerHTML = 5 + 6;											
	</script>											
												
	2、输出在弹窗											
	alert(我是一个警告框);											
												
	comfirm("我是一个提示框");											
												
	proptm("你也喜欢宝宝吗？")											
												
	3、输出在浏览器控制台 											
	console.log();											
												
四、函数												
	function functionName(参数){执行命令}											
												
五、获取指定元素												
												
	1、按ID获取元素											
	var a = document.getElementById(‘’)											
												
	2、按class名获取											
	var a = document.getElementByClassName(‘’);											
												
	3、按标签名获取											
	var a = document.getElementByTagName('')[n];											
	n指该标签的第几个，从0开始。											
												
	4、获取所有class名为intro的p标签											
	var x = document.querySelectorAll("p.intro");											
												
六、通过js改变元素css样式												
												
	<p id="p1">我是p1标签</p>											
												
	<script>											
	var a;											
	function fun(){											
		a = document.getElementById("p1");										
		this.style.background="#000"										
	}											
	</script>											
												
	就可以把p1的背景改为黑色											
