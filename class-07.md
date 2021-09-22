## Domain Modeling
a construcor is basically a template that will later be filled with information provided.<br>
after construcor is made 
```
{
  var **constructorname** = function(Info1, info2) {
  this.info1 = info1;
  this.info2 = info2;
}

var **variable1** = new COONSTRUCTORNAME(7, false);
var **variable2** = new CONSTRUCTORNAME(4, true);

console.log(variable1); (this will log 7=info1 and false=info2)
console.log(variable2); (this will log 4 = info1 and true = info2)
}
```

## HTML - Tables

```
  <table> creates table
  <tr> begins new table row
  <td> each cell is recognized as table data
  <th> same as td but used as table heading
  <thead> headings of the table
  <tfoot> footer belongs here
```
    
## JS - Functions, Methods, Objects

inside a constructor the information for constructor are called properties and functions inside are called methods<br>
> **this** is a keyword to reference the object that the function is created inside. 
THere are mulitple ways to store data
- variables (just one key)
- arrays (multiple pieces of informations)
- Objects
- Object constructor (to hold multiple objects)

#### Math object
```
Math.round() - rounds to nearest integer
Math.sqrt() - returns sq root of positive number
Math.ceil() - rounds up to nearest integer
Math.floor() - rounds down to nearest integer
Math.random() - generates random number
```
