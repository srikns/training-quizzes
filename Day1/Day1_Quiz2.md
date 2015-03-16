# Day 1 Quiz 2

**1. Create a variable array and put the values Tom, Harry, Sally, and Janet in the array. Then write the code to print out each item in the array with a for loop, then a while loop, then a do while loop.**

YOUR ANSWER:
var names = ["Tom", "Harry", "Sally", "Janet"];

for ( name in names ) {
	console.log(" For loop name is " + name);

}

for ( var i = 0; i < names.length; i++) {
	console.log ( " For loop names is " + names[i]);
}

i=0;
while ( i < names.length ){
	console.log ( " For While names is " + names[i++]);
}

i=0;
do {
	console.log ( " For Do-While names is " + names[i]);
} while ( ++i < names.length )


**2. Using the typeof operator, determine if a variable is a string, and print out "This is a string", to the console. Use the same process to determine if something is a Number, an Object, and one of the data type of your choice from the typeof.js samples.**

YOUR ANSWER:

var names = ["Tom", "Harry", "Sally", "Janet"];

for ( name in names ) {
	console.log(" For loop name is " + name);

}

for ( var i = 0; i < names.length; i++) {
	console.log ( " For loop names is " + names[i]);
}

i=0;
while ( i < names.length ){
	console.log ( " For While names is " + names[i++]);
}

i=0;
do {
	console.log ( " For Do-While names is " + names[i]);
} while ( ++i < names.length )
	
	
var number = 123;
var string = "string";
var array = [1,2,3];

if ( typeof string == "string" ) {
	console.log ("this is a string")
}
if ( typeof number == "number" ) {
	console.log ("this is a number")
}
if ( typeof array == "object" ) {
	console.log ("this is a object")
}

FINISHED? When you are done, commit your answer and submit a pull request back to the main repository you forked inside of a branch with your name as the name of the branch.
