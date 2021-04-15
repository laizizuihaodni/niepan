<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
		<script>

			window.onload=function(){
					var A=document.getElementById("i4");
					A.onclick=function(){
						var B=document.getElementById("i1");
						var C=document.getElementById("i2");
						var D=document.getElementById("i3");
						alert("最大值是:"+Math.max(parseInt(B.value),parseInt(C.value),parseInt(D.value)));
						alert("最小值是:"+Math.min(parseInt(B.value),parseInt(C.value),parseInt(D.value)));
						}
						
			}
			
		</script>
	</head>
	<body>
		<input type="text" id="i1"/>
		<input type="text" id="i2"/>
		<input type="text" id="i3"/>
		<input type="button" value="比较" id="i4"/>
	</body>
</html>
