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
~~~

## OUTPUT
![cal1](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/c9a72f10-a810-4930-b967-8efeef2e5e45)
![cal2](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/9f77da31-c685-45e0-b538-10592aada8dc)
![cal3](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/57628fa8-812e-45e4-a68d-4d4e4b29c923)
![cal4](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/15ea85da-0660-411f-b390-555e84a96fda)
![cal5](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/79edf81a-80a5-43a5-a5d7-95d599f89465)



## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
