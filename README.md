# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>

## OUTPUT
![cal1](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/ab0325f3-cabe-4717-87f1-fe9ed5dd72aa)
![cal2](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/0d06105b-57cc-4253-bcb0-ab21d7c08f51)
![cal3](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/587fcec6-584e-41f4-95da-6b13f3bd5696)
![cal4](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/1f1324c7-bc51-46db-800a-67fc4348faa8)
![cal5](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/64db9ec3-358f-4856-bc14-d0a013629e7b)



## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
