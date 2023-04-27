Exercises: Level 1

1. Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.

* Enter your age: 30 <br>
* You are old enough to drive.

* Enter your age:15 <br>
* You are left with 3 years to drive.

```js
let age = prompt("Enter your age:");
let yearsLeft = 18 - age;

if (age >= 18) {
  console.log("You are old enough to drive.");
} else {
  console.log("You are left with " + yearsLeft + " years to drive.");
}
````

2. Compare the values of myAge and yourAge using if … else. Based on the comparison and log the result to console stating who is older (me or you). Use prompt(“Enter your age:”) to get the age as input.

* Enter your age: 30 <br>
* You are 5 years older than me.

```js
let myAge = 25; // You can change this value if needed
let yourAge = prompt("Enter your age:");

if (myAge > yourAge) {
  console.log("I am " + (myAge - yourAge) + " years older than you.");
} else if (myAge < yourAge) {
  console.log("You are " + (yourAge - myAge) + " years older than me.");
} else {
  console.log("We are the same age!");
}
```

3. If a is greater than b return 'a is greater than b' else 'a is less than b'. Try to implement it in to ways

* using if else <br>
* ternary operator. <br>
  * let a = 4 <br>
  * let b = 3 <br>
  * 4 is greater than 3
  
```js
// if else
let a = 4;
let b = 3;

if (a > b) {
  console.log("a is greater than b");
} else {
  console.log("a is less than b");
}

// ternary operator
let a = 4;
let b = 3;

let result = a > b ? "a is greater than b" : "a is less than b";
console.log(result);
```

4. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript?

* Enter a number: 2 <br>
* 2 is an even number <br>

* Enter a number: 9 <br>
* 9 is is an odd number.

```js
let num = prompt("Enter a number:");

if (num % 2 === 0) {
  console.log(num + " is an even number");
} else {
  console.log(num + " is an odd number");
}
```

Exercises: Level 2

1. Write a code which can give grades to students according to theirs scores:

* 80-100, A
* 70-89, B
* 60-69, C
* 50-59, D
* 0-49, F
  
```js
let score = prompt("Enter your score:");

if (score >= 80 && score <= 100) {
  console.log("Your grade is A");
} else if (score >= 70 && score <= 89) {
  console.log("Your grade is B");
} else if (score >= 60 && score <= 69) {
  console.log("Your grade is C");
} else if (score >= 50 && score <= 59) {
  console.log("Your grade is D");
} else if (score >= 0 && score <= 49) {
  console.log("Your grade is F");
} else {
  console.log("Invalid score. Please enter a score between 0 and 100.");
}
```
2. Check if the season is Autumn, Winter, Spring or Summer. If the user input is :
* September, October or November, the season is Autumn.
* December, January or February, the season is Winter.
* March, April or May, the season is Spring
* June, July or August, the season is Summer

```js
let month = prompt("Enter a month:");

if (month === "September" || month === "October" || month === "November") {
  console.log("The season is Autumn");
} else if (month === "December" || month === "January" || month === "February") {
  console.log("The season is Winter");
} else if (month === "March" || month === "April" || month === "May") {
  console.log("The season is Spring");
} else if (month === "June" || month === "July" || month === "August") {
  console.log("The season is Summer");
} else {
  console.log("Invalid input. Please enter a valid month name.");
}
```

3. Check if a day is weekend day or a working day. Your script will take day as an input.
    
    * What is the day  today? Saturday
    * Saturday is a weekend.

    * What is the day today? saturDaY
    * Saturday is a weekend.

    * What is the day today? Friday
    * Friday is a working day.

    * What is the day today? FrIDAy
    * Friday is a working day.
  
  ```js
  let day = prompt("What is the day today?").toLowerCase();

switch(day) {
  case "saturday":
  case "sunday":
    console.log(day.charAt(0).toUpperCase() + day.slice(1) + " is a weekend.");
    break;
  case "monday":
  case "tuesday":
  case "wednesday":
  case "thursday":
  case "friday":
    console.log(day.charAt(0).toUpperCase() + day.slice(1) + " is a working day.");
    break;
  default:
    console.log("Invalid input. Please enter a valid day name.");
}
```

Exercises: Level 3

1. Write a program which tells the number of days in a month.

  * Enter a month: January
  * January has 31 days.

  * Enter a month: JANUARY
  * January has 31 day

  * Enter a month: February
  * February has 28 days.

  * Enter a month: FEbruary
  * February has 28 days.
  
```js
// if else
let month = prompt("Enter a month:").toLowerCase();

if (month === "january" || month === "march" || month === "may" || month === "july" || month === "august" || month === "october" || month === "december") {
  console.log(month.charAt(0).toUpperCase() + month.slice(1) + " has 31 days.");
} else if (month === "april" || month === "june" || month === "september" || month === "november") {
  console.log(month.charAt(0).toUpperCase() + month.slice(1) + " has 30 days.");
} else if (month === "february") {
  console.log(month.charAt(0).toUpperCase() + month.slice(1) + " has 28 days.");
} else {
  console.log("Invalid input. Please enter a valid month name.");
}
````

```js
// switch case
let month = prompt("Enter a month:").toLowerCase();

switch(month) {
  case "january":
  case "march":
  case "may":
  case "july":
  case "august":
  case "october":
  case "december":
    console.log(month.charAt(0).toUpperCase() + month.slice(1) + " has 31 days.");
    break;
  case "april":
  case "june":
  case "september":
  case "november":
    console.log(month.charAt(0).toUpperCase() + month.slice(1) + " has 30 days.");
    break;
  case "february":
    console.log(month.charAt(0).toUpperCase() + month.slice(1) + " has 28 days.");
    break;
  default:
    console.log("Invalid input. Please enter a valid month name.");
}
````

2. Write a program which tells the number of days in a month, now consider leap year.

```js
let month = prompt("Enter a month:");
let year = prompt("Enter a year:");

let days;

if (month === "January" || month === "March" || month === "May" || month === "July" || month === "August" || month === "October" || month === "December") {
  days = 31;
} else if (month === "April" || month === "June" || month === "September" || month === "November") {
  days = 30;
} else if (month === "February") {
  if ((year % 4 == 0 && year % 100 != 0) || year % 400 == 0) {
    days = 29;
  } else {
    days = 28;
  }
} else {
  console.log("Invalid month name");
}

if (days) {
  console.log(`${month} has ${days} days.`);
}
````
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
