#Bonfire: Check for Palindromes
<a href="http://freecodecamp.com/challenges/Bonfire:%20Check%20for%20Palindromes?solution=%2F*%0AReturn%20true%20if%20the%20given%20string%20is%20a%20palindrome.%20Otherwise%2C%20return%20false.%0AA%20palindrome%20is%20a%20word%20or%20sentence%20that%27s%20spelled%20the%20same%20way%20both%20forward%20and%20%0Abackward%2C%20ignoring%20punctuation%2C%20case%2C%20and%20spacing.%20You%27ll%20need%20to%20remove%20%0Apunctuation%20and%20turn%20everything%20lower%20case%20in%20order%20to%20check%20for%20palindromes.%0AWe%27ll%20pass%20strings%20with%20varying%20formats%2C%20such%20as%20%22racecar%22%2C%20%22RaceCar%22%2C%20and%20%22race%20CAR%22%20among%20others.%0A*%2F%0A%0Afunction%20palindrome(str)%20%7B%0A%20%20%2F%2F%20Good%20luck!%0A%0A%20%20%2F%2F%20convert%20string%20to%20lower%20case.%20Remove%20non-word%20characters%20and%20underscores%20%27_%27.%0A%20%20str%20%3D%20str.replace(%2F(%5CW%2B%7C_)%2Fgi%2C%20%22%22).toLowerCase()%3B%0A%20%20%0A%20%20%2F%2F%20Reverse%20the%20string%20and%20compare%20to%20non-reversed%20to%20determine%20if%20palindrome.%0A%20%20if(str.split(%27%27).reverse().join(%27%27)%20%3D%3D%20str)%20%7B%0A%20%20%20%20return%20true%3B%0A%20%20%7D%20else%20%7B%0A%20%20%20%20return%20false%3B%0A%20%20%7D%0A%7D%0Apalindrome(%22eye%22)%3B" target="_blank">Click here</a> to see the solution on the freeCodeCamp website.


####Instructions:
<p class="wrappable negative-10">Return true if the given string is a palindrome. Otherwise, return false.</p><p class="wrappable negative-10">A palindrome is a word or sentence that&apos;s spelled the same way both forward and backward, ignoring punctuation, case, and spacing.</p><p class="wrappable negative-10">You&apos;ll need to remove punctuation and turn everything lower case in order to check for palindromes.</p><p class="wrappable negative-10">We&apos;ll pass strings with varying formats, such as &quot;racecar&quot;, &quot;RaceCar&quot;, and &quot;race CAR&quot; among others.</p><p class="wrappable negative-10">Remember to use <a href="//github.com/FreeCodeCamp/freecodecamp/wiki/How-to-get-help-when-you-get-stuck" target="_blank">Read-Search-Ask</a> if you get stuck. Write your own code.</p><div class="negative-30-bottom"><div id="MDN-links"><p class="negative-10">Here are some helpful links:</p><div class="negative-10"><ul><li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace" target="_blank">String.replace()</a></li></ul></div><div class="negative-10"><ul><li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/toLowerCase" target="_blank">String.toLowerCase()</a></li></ul></div></div></div>


####Answer:
```javascript
/*
Return true if the given string is a palindrome. Otherwise, return false.
A palindrome is a word or sentence that's spelled the same way both forward and 
backward, ignoring punctuation, case, and spacing. You'll need to remove 
punctuation and turn everything lower case in order to check for palindromes.
We'll pass strings with varying formats, such as "racecar", "RaceCar", and "race CAR" among others.
*/

function palindrome(str) {
  // Good luck!

  // convert string to lower case. Remove non-word characters and underscores '_'.
  str = str.replace(/(\W+|_)/gi, "").toLowerCase();
  
  // Reverse the string and compare to non-reversed to determine if palindrome.
  if(str.split('').reverse().join('') == str) {
    return true;
  } else {
    return false;
  }
}
palindrome("eye");
```