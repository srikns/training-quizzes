# Day 1 Quiz 3

**1. What is a module in JavaScript?**

YOUR ANSWER: its similar to lib in c++

**2. Create a simple module with three functions; doThis(), doThat(), and didStuff(). For doThis() return a string of your choosing, for doThat() return another string of your choosing and for didStuff() add two parameters that will be multiplied together and returned with a string concatenated to the end of the result like result + " are the values multipled.". Be sure to have each of these functions exported via the module.exports.**

YOUR ANSWER:

var exports = module.exports = {};

exports.doThis = function() {
	return "doThis";
};

exports.doThat = function() {
	return "doThat";
};

exports.didThis = function( val1, val2) {
	return " result of mult is " + val1*val2;
};

**3. When declaring and using the module created in question 2, enter the code that would allow you to call each of the functions and write the results to the console.**

YOUR ANSWER:

var myMod = require("./Day1Quize2.js");

console.log ( "test is " + myMod.doThis());

console.log ( "test is " + myMod.doThat());

console.log ( "test is " + myMod.didThis(3,4));

FINISHED? When you are done, commit your answer and submit a pull request back to the main repository you forked inside of a branch with your name as the name of the branch.
