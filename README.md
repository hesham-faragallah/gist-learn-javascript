#gist-learn-javascript
Summary of BasicTutorial javascript

List basic course

1 - variable 
2 - array 
3 - condition (if & else) 
4 - switch 
5 - loop <br>
6 - while 
7 - function 
8 - event

I used the following link websie to reference http://www.w3schools.com/ http://developer.mozilla.org

1- variable 

"variables are containers for storing data values " 
example : 
var name = "hesham"; 
alert("my name is"+name); 
----- 
var x = 5; 
var y = 6; 
var z = x + y; 
alert(z); 

2- arrays 
" arrays are used to store multiple values in a single variable " 
example : 
<!--single arrays --> 
var cars = ["Saab", "Volvo", "BMW"]; 
document.getElementById("demo").innerHTML = cars;
----- 
<!--muilty arrays --> 
var fruits = [ ["Apple", "0", "Donkey"] ["Apple", "1", "Donkey"] ["Apple", "2", "Donkey"] ]; 
alert(fruits[0]);
------- 
<!--method arrays --> 
var cars = new Array ["Saab", "Volvo", "BMW"];



3-condition 
"if statement to specify a block of JavaScript code to be executed if a condition is true else if statement to specify a new condition if the first condition is false " 

example : 

function myFunction() {
var hour = new Date().getHours(); var greeting;

if (hour > 18) { greeting = "Good day"; } 
else { greeting = "Good evening"; } 

document.getElementById("demo").innerHTML = greeting; } 
--------



    var firstName = "Greg";

    if (firstName === "Greg") {
        document.getElementById("demo").innerHTML = "Hello John!";
    }
    --------- case normal condition------
    "we can add Infinite number of "else if "
    if (condition1)
       statement1
    else if (condition2)
       statement2
    else if (condition3)
       statement3
    ...
    else
       statementN

   --------- nasty condition ------
   
   if (condition1)
       statement1
    else
       if (condition2)
          statement2
       else
          if (condition3)

  ---------mark ------------------
  
  if (x > 5)
  if (cipher_char === from_char) 
  if (cipher_char == from_char) 
  if (x = y)
