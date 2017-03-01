<!DOCTYPE HTML>
<html>
<head>
<meta http-epuiv="Content-Type" content="text/html"; charset="utf-8"/>
<title>calculate</title>
</head>
<body>
<form>
<input type="button" value="number1" onclick="inputNum1()"/>
<input type="button" value="number2" onclick="inputNum2()"/>
<select  id="c_rule">
<option value="+">+</option>
<option value="-">-</option>
<option value="*">*</option>
<option value="/">/</option>
</select>
<input type="button" value="equal" onclick="sec()"/>
</form>
<script type="text/javascript">
function inputNum1(){
 mystr1=prompt("please input the first number:");
 mynum1=parseInt(mystr1);
}
function inputNum2(){
 mystr2=prompt("please input the second number:");
 mynum2=parseInt(mystr2);
}
function sec(){
var rule=document.getElementById("c_rule").value
switch(rule)
{
case "+":
result=mynum1+mynum2;
alert(result);
break;
case "-":
result=mynum1-mynum2;
alert(result);
break;
case "*":
result=mynum1*mynum2;
alert(result);
break;
case "/":
result=mynum1/mynum2;
alert(result);
break;
}
}
</script>
</body>
</html>
