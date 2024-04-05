# Always remember to hit `commit changes` after writing an MD file, future self >:(

## With that out of the way, lets dive into methods and working with arrays. Now watered down and simplified for my pea brain.

Like how Python has lists, it seems Javascript has its own version strictly called "arrays", which function almost the same way as lists called by number values ordered by [0], [1], [2], etc whether they be strings or numbers (how you use them is your problem).

```
const numberList = [ "Zero", 1 , 2 , "three", 4 ];
console.log(numberList[0]);
// "zero"
```
alt ways of writing and calling arrays:
```
const guy = {
  name = "Jack Guyman"
  age = "23"
console.log (guy.name)
// prints guy's name
```
### Tampering Methods

Similar to Python's methods, you can use different methods to manipulate the arrays, either adding, removing, or even getting data to and from them.

continued from code above...
```
numbersList.push(5)
//adds a 5 to the array.
console.log(numbersList.pop()
//Removes the last value entered in an array, in this case the 5 we just added
```
