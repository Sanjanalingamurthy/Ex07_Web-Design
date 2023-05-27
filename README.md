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
![cal1](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/c25ef601-58b6-41d9-b4fe-67fbd57233ce)
![cal2](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/dbb57c1f-7396-4f43-a294-0f4f55f8e29c)
![cal3](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/ed987a0c-c78a-48bb-9295-bcfc10c24ba6)
![cal4](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/7f4b28b0-9181-47cb-bdfd-b8124f828e58)
![cal5](https://github.com/Sanjanalingamurthy/Ex07_Web-Design/assets/127816526/9f99400a-a392-42ec-b488-828ea1a1ec70)



## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
