#Waypoint: Access Array Data with Indexes
<a href="http://freecodecamp.com/challenges/Waypoint:%20Access%20Array%20Data%20with%20Indexes?solution=%2F%2F%20var%20ourArray%20%3D%20%5B1%2C2%2C3%5D%3B%0A%2F%2F%20var%20ourData%20%3D%20ourArray%5B0%5D%3B%20%2F%2F%20equals%201%0A%0Avar%20myArray%20%3D%20%5B1%2C2%2C3%5D%3B%0A%2F%2F%20Only%20change%20code%20below%20this%20line.%0Avar%20myData%20%3D%20myArray%5B0%5D%3B%0A%0A%2F%2F%20Only%20change%20code%20above%20this%20line.%0A%2F%2F%20We%20use%20this%20function%20to%20show%20you%20the%20value%20of%20your%20variable%20in%20your%20output%20box.%0A%2F%2F%20You%27ll%20learn%20about%20functions%20soon.%0Aif(typeof(myArray)%20!%3D%3D%20%22undefined%22%20%26%26%20typeof(myData)%20!%3D%3D%20%22undefined%22)%7B(function(y%2Cz)%7Breturn%20%27myArray%20%3D%20%27%20%2B%20JSON.stringify(y)%20%2B%20%27%2C%20myData%20%3D%20%27%20%2B%20JSON.stringify(z)%3B%7D)(myArray%2C%20myData)%3B%7D%0A" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">We can access the data inside arrays using <code>indexes</code>.</p><p class="wrappable negative-10">Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array.</p><p class="wrappable negative-10">For example:</p><p class="wrappable negative-10"><code>var array = [1,2,3];</code></p><p class="wrappable negative-10"><code>array[0]; //equals 1</code></p><p class="wrappable negative-10"><code>var data = array[1];</code></p><p class="wrappable negative-10">Create a variable called <code>myData</code> and set it to equal the first value of <code>myArray</code>.</p><div class="negative-bottom-margin-30"><div id="MDN-links"><p class="negative-10">Here are some helpful links:</p></div></div>


####Answer:
```javascript
// var ourArray = [1,2,3];
// var ourData = ourArray[0]; // equals 1

var myArray = [1,2,3];
// Only change code below this line.
var myData = myArray[0];

// Only change code above this line.
// We use this function to show you the value of your variable in your output box.
// You'll learn about functions soon.
if(typeof(myArray) !== "undefined" && typeof(myData) !== "undefined"){(function(y,z){return 'myArray = ' + JSON.stringify(y) + ', myData = ' + JSON.stringify(z);})(myArray, myData);}

```