<html>

	<head>
		<meta charset="UTF-8">
		<script src="https://d3js.org/d3.v3.min.js"></script>
		<title>Project 1 - B.Downer</title>
	</head>

	<body>
		<script>

			var svgMargin = {top:0, bottom:0, left:0, right:0};			
			var width = window.innerWidth - svgMargin.left - svgMargin.right;
			var height = window.innerHeight - svgMargin.top - svgMargin.bottom;

			var xScale = d3.scaleLinear().domain().range()

			d3.json('streets.json', function(error, data){
				console.log(data[0])
				console.log(data[1]);
			});
	

		</script>
	</body>

</html>
