1a)  
  1) values added: 20  
  2) final result: 20  
  3) values added: 20
  4) The code will return an error because the let result variable is declared in the if statement block & line 13 is outside of the if statement block. And we know that when you declare a variable with the let keyword, that variable only has block scope so we won't be able to access result and print it.
  5) The code will return an error because you aren't supposed to reassign the result value after it is set as 0 since it is of type const. 
  6) Again, the code will return an error because you aren't supposed to reassign the result value after it is set as 0 since it is of type const. Since we call sumValues(10,10, true), we will run the if statement which will attempt to change the value of result, but we can't do that since it is a const.

  
