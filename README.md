# calculator

<!-- Name: Brittany Gould
Calculator Assignment
-->
<!DOCTYPE html>
<html>

<head>
<style>
body {

background-color: powderblue;}

</style>
</head>

<body>

<h2><u>Calculator</u></h2>


<button onclick=add1()>Press to Add</button>
<p id="res1"> </p>
<button onclick=sub1()>Press to Subtract</button>
<p id="res2"> </p>
<button onclick=div1()>Press to Divide</button>
<p id="res3"> </p>
<button onclick=mult1()>Press to Multiply</button>
<p id="res4"> </p>

<script>
    //for addition
    function add1()
    {
    num1=parseFloat(prompt("Enter First Number:"));
    num2=parseFloat(prompt("Enter First Number:"));
    
    document.getElementById("res1").innerHTML="Addition Result = " + add(num1,num2);
   
    // actual calculation and result using return
    function add(num1,num2)
    {return num1+num2;}

    }

    // for subtraction
    function sub1()
    {
    num1=parseFloat(prompt("Enter First Number:"));
    num2=parseFloat(prompt("Enter First Number:"));
    document.getElementById("res2").innerHTML="Subtraction Result = " + sub(num1,num2);
 
    function sub(num1,num2)
    {return num1-num2;}

    }
    // for multiplication
    function mult1()
    {
    num1=parseFloat(prompt("Enter First Number:"));
    num2=parseFloat(prompt("Enter First Number:"));
    document.getElementById("res3").innerHTML="Multiplication Result = " + mult(num1,num2);
 
    function mult(num1,num2)
    {return num1*num2;}

    }

    //for division
    function div1()
    {
    num1=parseFloat(prompt("Enter First Number:"));
    num2=parseFloat(prompt("Enter First Number:"));
    document.getElementById("res2").innerHTML="Division Result = " + div(num1,num2);
 
    function div(num1,num2)
    {return num1/num2;}
    }
</script>


