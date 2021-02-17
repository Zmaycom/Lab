<!DOCTYPE html>
<html>
	<head>
		<script src="jquery-3.5.1.js"></script>
		<script>
		
		$(document).ready(function(){
			$("#btn1").click(function(){
				$("#txt").slideUp(3000);
						alert("Текст скрыт");
			})
			});
		
		</script>
	</head>
	
	<body>
	
		<input type="button" id="btn1" value="Скрыть текст"/>
		<div id="txt">
			Идти ему было; он даже не знал,
			сколько шагов от варот его дома: ровно семьсот тридцать.
			Как-то раз он сосчитал, когда уж очень размечтался.
			В то время он и сам еще не верил этим мечтам своим и только
			но соблазнительною дерзостью.
		</div>
	
	</body>
</html>
