<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title></title>
	</head>
	<body>
		<div id="wrap">
			
		</div>
		<script type="text/javascript">
			var oDdiv=document.getElementById("wrap")
			debugger
			for(var i = 1;i <= 9; i++){
			  for(var j = 1;j <= i; j++){
				oDdiv.innerHTML+=j + "*" + i + "=" + i*j +" "+" "
				}
				oDdiv.innerHTML+="<br />"
			}
		</script>
	</body>
</html>
