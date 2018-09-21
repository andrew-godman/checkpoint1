# Week 1 Assessment

### Bash (Terminal)

#### Assume your present working directory is `$ ~/buffy`

1. Make two directories inside `~/buffy`: `scoobies` and `vamps`
<br><br><br>

$mkdir scoobies vamps

2. Make files in `scoobies` named `buffy.txt`, `giles.txt` and `angel.txt`
<br><br><br>

$touch scoobies/buffy.txt scoobies/giles.txt

3. Copy `angel.txt` into the `vamps` directory
<br><br>

$cp scoobies/angel.txt vamps/angle.txt

4. Delete the `vamps` directory and everything inside it
<br><br>

$rm -rf vamps/

### JS Variables

1. Assign the string "Jack" to a variable called `captain`
<br><br>

var captain = "Jack"

2. Using the `captain` variable, use string concatenation to form the string "Oh Jack, my Jack!", assigning it to a variable named `phrase`
<br><br>

var phrase = "Oh ".concat(captain).concat(", my ").concat(captain).concat("!")

### JS Conditionals
```js
var souls = 3;
var lifeRafts = 2;
```

1. Write an `if` statement that console.logs "SOS!" if there are more _souls_ than _lifeRafts_
<br><br>

if (souls > lifeRafts) {
  console.log("SOS!");
}


### Data Structures - JS Arrays

1. Create an array named `weekend` with just 'Saturday' in it
<br><br>

var weekend = ["Saturday"]

2. Add 'Sunday' to the end of the `weekend` array
<br><br>

weekend.push("Sunday")

3. Add 'Friday' to the front to the front of the `weekend` array
<br><br>

weekend.unshift("Friday")

4. Access 'Saturday' in the array and assign to a variable named `day`
<br><br>

var day = weekend[1]

5. Remove 'Friday' from the array
<br><br>

weekend.splice(0,1)

### Data Structures - JS Objects

1. Write an object literal named `brain` having a property of `energyLevel` with a value of `10` as a number
<br><br>

var brain = {
  energyLevel: 10
}

2. Assign the property of `energyLevel` to a variable named `energy`
<br><br>

var energy = brain.energyLevel

3. Add a `dream` property to the `brain` object that holds the string  'electric sheep'

var brain = {
  energyLevel: 10,
  dream: 'electric sheep',
};

4. Add a `dayDream` property to the `brain` object that holds the object `{ lunch: ['burger', 'beer'] }`
<br><br>

var brain = {
  energyLevel: 10,
  dream: 'electric sheep',
  dayDream: `{ lunch: ['burger', 'beer'] }`,
};

5. Add another element `pudding` to the lunch array inside the `brain` object
<br><br>



### JS Functions

1. Write a function to return the area of a rectangle (the product of its length and its width)
<br><br>

2. Invoke the function with `3` and `4` as arguments and save it to a variable named `result`
<br><br>
