# Instructions  

** During lecture, exercises using lists  & loops **

_ Write code snippets or functions, then test them by calling them  _

## Reference

## Steps
For the below write a code snippet  or function  (note you are specifically asked to get input & print here, only do this inside a function if requested)
### First we will do some code in the console0 with lists
see the lists in main.py  (if you run it, you can use the lists in the console)
### Instructions  Use the cegeps list
1. Write a function to take a list of cegeps as a parameter it will display each element of the list with a text "you could go to " + the name of the cegep.
2. if the cegep contains the string "Dawson"  (hint `x in y` for strings) add "the best" at the end of the string,  for example:
```
you could go to JAC
you could go to Dawson the best
```
### Instructions  Use the grades list
1. Write a function to take a list of grades as a parameter & return the average grade (do not include any grades that are <0 or > 100)
### Instructions  Use the grades list
1. Write a function to take a list of grades as a parameter & return the largest grade (hint use a variable largest, start at 0 and hold the largest "so far" with each itteration of the loop
### Instructions  Roll the dice 
1. Write the snippet of code/function  to fill a list with 10 random numbers between 1 and 6  (if you want to use more sides to your dice that is fine)   <br>Hints: 
   * ` dicerolls = []   #empty list to start`  before the loop
   * use a for with a range ( 10 times )
   * inside the loop 
     * generate a random number
     * ` dicerolls.append(num)  #adds num to the end of the list `
   * use the list in the next steps
2. calculate the average 
3. find the largest number in the list
4. find the smallest number in the list

Do not use built-in functions