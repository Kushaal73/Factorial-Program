# Factorial-Program
Done in JAVASCRIPT.This program takes in the user input,which is the number they want to find the factorial of.Once we have the input we execute a function to find the factorial of the number given.It will log the answer to the console.
-----------------------------------------------------------------------------------------------------------------------------------------------------

let number = prompt("number?"); //this will be the last number of the loop
function factorial(num) {
  let start = 1; //this is tge number from which the loops starts
  let total = 1; //this number will change

  while (start < num) {
    start = start + 1;
    total = total * start;
    console.log(total);
  }
  //the loop multiplies the total with a number(start) one greater than its previous constantly until the
  //number(start) reaches num.

  console.log(num, "factorial is equal to", total);
}

factorial(number);
