# ANSWERS

## Bash (Terminal)
pwd = `$ ~/buffy`

1. Make two directories inside `~/buffy`: `scoobies` and `vamps`. 
`mkdir scoobies vamps`

2. Make files in scoobies named `buffy.txt`, `giles.txt` and `angel.txt`.
`touch scoobies/buffy.txt giles.txt angel.txt`

3. Copy `angel.txt` into the `vamps` directory.
`cp scoobies/angel.txt ../vamps`

Delete the `vamps` directory and everything inside it.
`rm -rf vamps`

## JS Variables

1. Assign the string "Jack" to a variable called captain.
`var captain = "Jack"`

2. Using the captain variable, use string concatenation to form the string:
    `"Oh Jack, my Jack!"`, assigning it to a variable named phrase.
`console.log("Oh " + captain + ", my " + captain + "!");`

## JS Conditionals
`var souls = 3;`
`var lifeRafts = 2;`

Write an if statement that console.logs `"SOS!"` if there are more souls than lifeRafts.

`if (souls > 2) {`
    `console.log("SOS!");`
`}`

## Data Structures - JS Arrays
1. Create an array named `weekend` with just `'Saturday'` in it.
`var weekend = ['Saturday'];`

2. Add 'Sunday' to the end of the `weekend` array.
`weekend.push('Sunday')`
So:
`var weekend = ['Saturday', 'Sunday'];`

3. Add 'Friday' to the front of the `weekend` array.
`weekend.unshift('Friday')`
So:
`var weekend = ['Friday', 'Saturday', 'Sunday'];`

4. Access 'Saturday' in the array and assign to a variable named `day`.
`var day = weekend[1];`

5. Remove 'Friday' from the array.
`weekend.shift();`

## Data Structures - JS Objects
1. Write an object literal named `brain` having a property of `energyLevel` with a value of `10` as a number.
`var brain = {`
    `energyLevel: 10`
`}`

2. Assign the property of `energyLevel` to a variable named `energy`. 
`brain.energyLevel = 'energy'`
So:
`var brain = {`
    `energyLevel: 'energy'`
`}`

3. Add a `dream` property to the `brain` object that holds the string `'electric sheep'`. 
`brain.dream = 'electric sheep'`
So:
`var brain = {`
    `energyLevel: 'energy'`
    `brain.dream = 'electric sheep'`
`}`

4. Add a `dayDream` property to the `brain` object that holds the object `{ lunch: ['burger', 'beer'] }
`brain.dayDream = {lunch: ['burger', 'beer']}`
So:
`var brain = {`
    `energyLevel: 'energy'`
    `brain.dream = 'electric sheep'`
    `dayDream = {lunch: ['burger', 'beer']}`
`}`

5. Add another element `pudding` to the lunch array inside the `brain` object.
`brain.dayDream.lunch.push('pudding')`
So:
`var brain = {`
    `energyLevel: 'energy'`
    `brain.dream = 'electric sheep'`
    `dayDream = {lunch: ['burger', 'beer', 'pudding']}`
`}`

## JS Functions
1. Write a function to return the area of a rectangle (the product of its length and its width).
`var rectangleArea = function(length, width) {`
    `return (length * width)`
`}`

2. Invoke the function with 3 and 4 as arguments and save it to a variable named `result`.
`var result = rectangleArea(3, 4)`
`console.log(result);`

&copy; Daniel Marroquin Mwahahahaahhahahahahhahahahahaha.