# Javascript
fundamentals of Javascript
# building blocks of Javascript
  1.DataTypes
  2.Variables
  3.EscapeSequence
  4.Concatenation & constant
  5.DialogBox
  
# 1. DataTypes
 DataTypes are divided into primitive DataTypes and Composite DataTypes in JS
 PRIMITIVE DT
   Numbers- integers,floats and NAN(Not a Number), inifinity
   strings- "hello world"/'hello world'
   boolean- binary value TRUE Or FALSE 
   null- represent no value i.e you have assigned a variable with Null value i.e var a = NULL
   undefined- this means we have defined a variable but not initialized a value i.e var a /* but the variable a has not been initailized with a value*/
 COMPOSITE DT
    Objects
    Arrays
    Functions
# 2.Variables
    the first character must be a letter or underscore
    var a = 10          var n (undefined)
    var a = "string"    var n =3.14(float)
    var a = TRUE
    depending upon the value the datatypes are determined at the memory level during compilation
    that y JS is known light-weight scripting language
 # 3.ESCAPE Sequence  
   if we want to use escape sequence like /n newlline we need to define a pre tag before script tag
 # 4.concatenation and constant
   we can do concatenation with the help of '+' operator;
   constant can be defined by const a = 10;
 # 5.Dailog Box
   it is used to get interactive input from the user ;
   There are three types of Dialog Box in JS
    1.alert("expression") ## This is used to display alert message only no input from the user ##
    2.prompt("expression","dumy value") ## This is used to get the value from the user in text box and ur giving a dumy value to it in       place of dumy value u should enter ur value ##
    3.confirm("expression") ## this will create a dialog box with ok and cancel option and u can play with ok and cancel ##
  # Arrays
  In javasscript arrays are of two types 1. Numeric Arrays 2. Associative Arrays
  1.Numeric Arrays - index is a number like 0,1,2...
  2.Associative ArrYA - index is a string like zero,one,two....
  # creating a Array
  Array is also considered as a object in JS because JS is purely Document Object Model(DOM)
  1.var color = new Array(4) # note here we are calling a constructor of class Array *** in Array A should be always capital because JS is case sensitive language
  2. var color = new Array('red','green','blue');
  3. var color = ['red','green','blue'];
