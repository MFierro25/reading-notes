## HTML

#### Chapter 2 - "Text"
below are some examples of tags
<br>
h1 - h6 = heading size text <br>
p = start a paragraph <br>
b / i - Bold and italics<br>
sup / sub - sup and subscript<br>
br - break <br>
hr - horizontal line<br>
strong / em - same effects as bold and italic<br>
blockquote / q - quotes <br>

> all these tags are used to describe structure of the page
  
#### Chapter 10 - Intro to CSS
  
##### How Css works 
  > imagine a box around each elemnt and css allows to contgrol each box. Css givesd rules how each element or text should be displayed.
   
##### how to write 
 > you can use internal or external (links) css. you use selector to choose what element you want to configure, like ID, Class, type. It is best practice to 
  use a seperate style sheet for all CSS. 
  
##### Examples 
  H1 {
  font-family: arial;
  }
  <br>
  (below styles class)<br>
  .page {
    background-color: blue;
  }<br>
  (below styles ID)<br>
  #intro {
   {border: 5px solid #665544;
  }
      
## JS
 
### CH 2 - Basic JS structures 
Rules to follow
  - statements should end with semicolon ;
  - curly braces {} start indicate start and end of codeblock
  - writing comments helps to explain what code should do
  - when naming a variable it cannot start with a number, do not use dash or period
  - variables are case sensitive
  - when putting quotes '' around a number it becomes a string
 Variables 
 -  Declare  (give name) = Set Value
 > Data types can be Numeric, String or boolean (true/false) <br>
 
 Arrays
  - starts at 0 not 1 
  - .length is the property that holds the number of items in the array.
  - can single out a certain thing by [#]
  - anything pushed goes to the end of array
  
### CH 4 - Decisions and loops
<p>Think of a script as a flow chart,
things start somewhere and certain conditions need to be met before moving along to the next step.
  things can equal, be greater or less than, or compare two things. 
  You can also use logical operators to test more than one condition (&&) or at least one condition (||)
  you can use (!) to invert a boolean, making something the opposite.
  Use if and else if statements to show the flow of the script. for example IF this happens follow this code
  ELSE IF (so if a different thing happens) Follow this script instead.

