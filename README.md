# javascript-2-3
act 2&amp;3
<!DOCTYPE html>
<html>
<head>
	<title>Javascript Activity2 - [Rey Anthony Baldado]</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
  * 
<body>
	
  </style>
</head>
<body>
<div class="container">
	<div class="row">
		<div class="col-sm-3"></div>
		<div class="col-sm-6">
			<form>
				<div class="form-group">
					<label >Value1</label>
					<input type="text" class="form-control" id="Value1">
				</div>
				<div class="form-group">
					<label>Value2:</label>
					<input type="text" class="form-control" id="Value2">
				</div>

				<input type="button" class="btn btn-primary" onclick="add()" value="+ Add">
				<input type="button" class="btn btn-primary" onclick="subtract()" value="- Subtract">
				<input type="button" class="btn btn-primary" onclick="multiply()" value="* Multiply">
				<input type="button" class="btn btn-primary" onclick="divide()" value="/ Divide">


			</form>
			<h3>The answer is: </h3> <h3 id="answer"></h3>
		</div>
		<div class="col-sm-3">
	</div>
</div>

<script type="text/javascript">
var Value1,Value2,result;
	function add()
	{
		var Value1 = Number(document.getElementById('Value1').value);
		var Value2 = Number(document.getElementById('Value2').value);
		var result = Value1+Value2; 
		document.getElementById('answer').innerHTML=result;
		if (isNaN(result)) 
		{
			alert("Invalid Number");
			var warning = document.getElementById("answer").innerHTML = "Invalid Number";
		}
		else 
		{
			alert("number")
		}
	}
	
	function subtract()
	{
		var Value1 = Number(document.getElementById('Value1').value);
		var Value2 = Number(document.getElementById('Value2').value);
		var result = Value1-Value2; 
		document.getElementById('answer').innerHTML=result;
		if (isNaN(result)) 
		{
			alert("Invalid Number");
			var warning = document.getElementById("answer").innerHTML = "Invalid Number";
		}
		else 
		{
			alert("number")
		}
	}
	function multiply()
	{
		var Value1 = Number(document.getElementById('Value1').value);
		var Value2 = Number(document.getElementById('Value2').value);
		var result = Value1*Value2; 
		document.getElementById('answer').innerHTML=result;
		if (isNaN(result)) 
		{
			alert("Invalid Number");
			var warning = document.getElementById("answer").innerHTML = "Invalid Number";
		}
		else 
		{
			alert("number")
		}
	}
	function divide()
	{
		var Value1 = Number(document.getElementById('Value1').value);
		var Value2 = Number(document.getElementById('Value2').value);
		var result = Value1/Value2; 
		document.getElementById('answer').innerHTML=result;
		if (isNaN(result)) 
		{
			alert("Invalid Number");
			var warning = document.getElementById("answer").innerHTML = "Invalid Number";
		}
		else 
		{
			alert("number")
		}
	}

</script>
</body>
</html>


act 3

<!DOCTYPE html>
<html>
<head>
	<title>Javascript Activity 3 - Rey Anthony Baldado</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link rel="stylesheet" type="text/css" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css">
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1"		>
</head>
<body>
<div class="container"
<label>Enter Grade:</label>
<input type="text" id='grd'>
<input type="button"value="GO!" onclick="search()">
<p>65-74:POOR</p>
<p>75-79:NICE</p>
<p>80-84:GOOD</p>
<p>85-94:VERY GOOD</p>
<p>95-98:EXCELLENT</p>
<h3>Grade Results:</h3>
<h3 id="result">
</div>
<script>
                                                                                            
function search()
{
	var grd=Number(document.getElementById('grd').value);
		
		if(isNaN('grd')==false)
		var bracket=""
	{
		if(grd>94)
		{
		document.getElementById('result').innerHTML="EXCELLENT";
		}
		else if(grd>84)
		{
		document.getElementById('result').innerHTML="VERY GOOD";
		}
		else if(grd>79)
		{
		document.getElementById('result').innerHTML="GOOD";
		}
		else if(grd>74)
		{
		document.getElementById('result').innerHTML="NICE";
		}
		else if(grd<75)
		{
		document.getElementById('result').innerHTML="POOR";
		}	
		else 
		{
		document.getElementById('result').innerHTML="INVALID VALUE";
		}

	}

}


</script>
</body>
