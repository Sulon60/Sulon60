<html>
<head>
<tittle>calculator</tittle>
<style> 
body{
background:white;
}
*{
box-sizing:border-box;
-webkit-box-sizing;border-box;
-moz-box-sizing:border-box;
}
.wrap{
width:300px;
margin:auto;
height:400px;
background:gray;
border:3px solid black;
padding:10px;
border-radius:20px;
}
input[type=text]{
background-color:lightsteelblue;
width:100%;
padding:5px;
font-size:22px;
font-height:bold;
margin-top:20px;
border-radius:5px;
border-color:black;
}
input[type=button]{
background-color:brown;
color:white;
width:63px;
padding:5px;
font-height:bold;
border-radius:5px;
border-co;or:black;
}
#del{
width:48%;
}
input:hover{
background-color:skyblue;
color:black;
}
</style>
</head>
<div class="wrap">
<form name="cal">
<input type="text" name="display">
<br><br>
<input type="button" value="7" onclick="cal.display.value+='7">
<input type="button" value="8" onclick="cal.display.value+='8">
<input type="button" value="9" onclick="cal.display.value+='9">
<input type="button" value="+" onclick="cal.display.value+='+">
<br><br>
<input type="button" value="4" onclick="cal.display.value+='4">
<input type="button" value="5" onclick="cal.display.value+='5">
<input type="button" value="6" onclick="cal.display.value+='6">
<input type="button" value="-" onclick="cal.display.value+='-">
<br><br>
<input type="button" value="1" onclick="cal.display.value+='1">
<input type="button" value="2" onclick="cal.display.value+='2">
<input type="button" value="3" onclick="cal.display.value+='3">
<input type="button" value="*" onclick="cal.display.value+='*">
<br><br>
<input type="button" value="0" onclick="cal.display.value+='0">
<input type="button" value="/" onclick="cal.display.value+='/">
<input type="button" value="%" onclick="cal.display.value+='%">
<input type="button" value="=" onclick="cal.display.value=eval(cal.display.value">
<br><br>
<inpute type="button" value="DELETE" onclick="cal.display.value=""id="del">
<inpute type="button" value="^" onclick="sq()">
<inpute type="button" value="." onclick="cal.display.value+='.">
</form>
<script>
j
function sq(){
cal.display.value=math.sqrt(cal.display.value);
}
</script>
<body>
</body>
</html>
