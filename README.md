# random-text
random-text's effect
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>random-text</title>
	<style type="text/css">
		.text_style{
			font-size: 10rem;
			background: blue; 
			width: 100%;
			height: 300px;
			color:#fff;
		}
	</style>

</head>
<body>


     <div id="div_dandom_text"></div>
     <script type="text/javascript">

     function text(){
	     
	      var arr = new Array("AWESOME","COOL","SILLYMK","BLOWING","ASPIRE");
	      var dandomStyle = document.getElementById("div_dandom_text").classList.add("text_style");
	      var n = Math.floor(Math.random()*5);
	     //contentStyle.style.visibility="visible";
	     //contentStyle.innerHTML="<BR>"+arr[n];
	      div_dandom_text.innerHTML = arr[n];

}

setInterval("text()",130);
</script>
</body>
</body>
</html>
