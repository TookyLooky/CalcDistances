<!DOCTYPE html>
<html lang="en">
 <head>
     <meta charset="UTF-8">
     <title>Height Measurement</title>

 </head>
 <h1>What is this website used for?</h1>
 <h2>This Website is an application that helps people to measure distance using various different methods</h2>
 <h3>Currently, our team is working on a length calculator</h3>
  <body>
<p>Click here to got to length calculator: </p>
<a href="Sub-parts/lenght-calculator.html">Length Calculator</a>


  </body>
</html>

const display = document.getElementById("display");

function appendToDisplay(input){
    display.value += input;
}

function clearDisplay(){
    display.value = "";
}

function calculate(){
    try{
        display.value = eval(display.value);
    }
    catch(error){
        display.value = "Error";
    }
}
