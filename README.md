# jsfreecodecamp
This is the repository for javascript documentation. 
<h2>VARIABLES</h2>
Variables -> letters, numbers, dollar shign, and underscores <br>
            must not begin with number <br>
            can't contain spaces <br>
keywords: let  <br>eg: let hello; <br> <br>
When variables names are more than one word, use Camelcase: first word is entirely lowercase, but following words are all title-cased. <br>
eg: let variableOne; <br>
let secondVariable; <br>
let yetAnotherVariable; <br>
let thisIsAnAbsurdlyLongName; <br> <br>
When variable is declared without initializing it, it is considered uninitialized
eg:let secondCharacter; <br>
console.log(secondCharacter); <br>
output: undefined <br>
assign values using assignment operator = <br>
eg: let hello = "Hello"; <br>
variable declared with let can be reassigned(change value of) <br>
Note: When reassigning a variable, you do not use the let keyword again.  <br>
eg: let programmer = "Naomi"; <br>
programmer = "CamperChan"; <br>
One variable value can be assigned to another variable <br>
eg:let first = "One";<br>
let second = "Two";<br>
second = first; <br>

<h2> Arrays</h2>
<p>An array is a non-primitive data type that can hold a series of values. Non-primitive data types differ from primitive data types in that they can hold more complex data. Primitive data types like strings and numbers can only hold one value at a time.</p>
Arays are denoted using square brackets []. <br>
eg: let array = []; <br>
Array holds values separated by commas. eg: let array= ["first", "second"]; <br>
the order of values in array is important. <br>
strings are case-sensitive. <br> 
access the values inside an array using the index of the value. An index is a number representing the position of the value in the array, starting from 0 for the first value. <br>
Arrays are mutable, meaning you can change the values at an index directly. <br>
eg: let array = [1, 2, 3]; <br>
array[1] = 25; <br>
console.log(array); <br>
.length can be used to find length of the array, to get the last element 
<h2>7 Primitive Datatypes</h2>
<ol>
  <li>String</li>
  <p>enclosed in either single ' or " . <br> Strings are immutable; can't be changed once created</p>
</ol>

<h3>Console.log</h3>
<p>console.log(): allows to print and view javascript output. </p>

