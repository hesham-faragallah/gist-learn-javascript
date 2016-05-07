#gist-learn-javascript
Summary of BasicTutorial javascript

List basic course

1 - variable <br>
2 - array <br>
3 - condition (if & else) <br>
4 - switch <br>
5 - loop <br>
6 - while <br>
7 - function <br>
8 - event<br>
<br><br>
I used the following link websie to reference<br> 
http://www.w3schools.com/ <br>
http://developer.mozilla.org<br>

1- variable <br>

"variables are containers for storing data values " 
example :
<script>
  
var name = "hesham"; 
alert("my name is"+name); 
</script>
----- 
<script>
var x = 5; 
var y = 6; 
var z = x + y; 
alert(z);
</script>

2- arrays 
" arrays are used to store multiple values in a single variable " <br>
example : <br>
<script>
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

</script>

3-condition 
"if statement to specify a block of JavaScript code to be executed if a condition is true else if statement to specify a new condition if the first condition is false "</br> 

example :<br> 
<script>
function myFunction() {
var hour = new Date().getHours(); var greeting;

if (hour > 18) { greeting = "Good day"; } 
else { greeting = "Good evening"; } 

document.getElementById("demo").innerHTML = greeting; }
</script>
--------


<script>
    var firstName = "Greg";

    if (firstName === "Greg") {
        document.getElementById("demo").innerHTML = "Hello John!";
    }
    // --------- case normal condition------
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

   //   --------- nasty condition ------
   
   if (condition1)
       statement1
    else
       if (condition2)
          statement2
       else
          if (condition3)

//   ---------mark ------------------
  
  if (x > 5)
  if (cipher_char === from_char) 
  if (cipher_char == from_char) 
  if (x = y)
</script>
