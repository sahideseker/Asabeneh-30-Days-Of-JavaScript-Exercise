Day 3: Exercises

Exercises: Level 1

1. Declare firstName, lastName, country, city, age, isMarried, year variable and assign value to it and use the typeof operator to check different data types.


```js
let firstName = 'Sahide';
let lastName = 'Seker';
let country = 'Turkiye';
let city = 'Istanbul';
let age = 23;
let isMarried = false;
let year = 2023;

console.log(typeof firstName); // string
console.log(typeof lastName); // string
console.log(typeof country); // string
console.log(typeof city); // string
console.log(typeof age); // number
console.log(typeof isMarried); // boolean
console.log(typeof year); // number

```

2. Check if type of '10' is equal to 10

```js
console.log('10' === 10); // false
```

3. Check if parseInt('9.8') is equal to 10

```js
console.log(parseInt('9.8') === 10); // false

```

4. Boolean value is either true or false.

i.Write three JavaScript statement which provide truthy value. <br>
ii.Write three JavaScript statement which provide falsy value
```js
// i.truthy values
console.log(Boolean('hello')); // true
console.log(Boolean(10 > 5)); // true
console.log(Boolean(1)); // true

// ii.falsy values
console.log(Boolean('')); // false
console.log(Boolean(null)); // false
console.log(Boolean(undefined)); // false
```

5. Figure out the result of the following comparison expression first without using console.log(). After you decide the result confirm it using console.log()


4 > 3 <br>
4 >= 3  <br>
4 < 3 <br>
4 <= 3  <br>  
4 == 4  <br>
4 === 4 <br>
4 != 4  <br>
4 !== 4 <br>
4 != '4'  <br>
4 == '4'  <br>
4 === '4' <br>
Find the length of python and jargon and make a falsy comparison statement.

```js
console.log(4 > 3); // true
console.log(4 >= 3); // true
console.log(4 < 3); // false
console.log(4 <= 3); // false
console.log(4 == 4); // true
console.log(4 === 4); // true
console.log(4 != 4); // false
console.log(4 !== 4); // false
console.log(4 != '4'); // false
console.log(4 == '4'); // true
console.log(4 === '4'); // false
console.log('python'.length < 'jargon'.length); // false

```

6. Figure out the result of the following expressions first without using console.log(). After you decide the result confirm it by using console.log()


4 > 3 && 10 < 12  <br>
4 > 3 && 10 > 12  <br>
4 > 3 || 10 < 12  <br>
4 > 3 || 10 > 12  <br>
!(4 > 3)  <br>
!(4 < 3)  <br>
!(false)  <br>
!(4 > 3 && 10 < 12) <br>
!(4 > 3 && 10 > 12) <br>
!(4 === '4')  <br>
There is no 'on' in both dragon and python  <br>

```js
console.log(4 > 3 && 10 < 12); // true
console.log(4 > 3 && 10 > 12); // false
console.log(4 > 3 || 10 < 12); // true
console.log(4 > 3 || 10 > 12); // true
console.log(!(4 > 3)); // false
console.log(!(4 < 3)); // true
console.log(!(false)); // true
console.log(!(4 > 3 && 10 < 12)); // false
console.log(!(4 > 3 && 10 > 12)); // true
console.log(!(4 === '4')); // true
console.log(!('dragon'.includes('on') || 'python'.includes('on'))); // false

```

7. Use the Date object to do the following activities


What is the year today?<br>
What is the month today as a number?<br>
What is the date today?<br>
What is the day today as a number?<br>
What is the hours now?<br>
What is the minutes now?<br>
Find out the numbers of seconds elapsed from January 1, 1970 to now.

```js
const now = new Date();

const year = now.getFullYear();
console.log(year); // e.g. 2023

const month = now.getMonth() + 1; 
console.log(month); // e.g. 4 (for April)

const date = now.getDate();
console.log(date); // e.g. 27

const day = now.getDay(); // 0 for Sunday, 1 for Monday
console.log(day); // e.g. 4 (for Thursday)

const hours = now.getHours();
console.log(hours); // e.g. 14 (for 2:00 PM)

const minutes = now.getMinutes();
console.log(minutes); // e.g. 58

const secondsSince1970 = now.getTime() / 1000;
console.log(secondsSince1970); // e.g. 1680557484.261 (this value changes every second)
```

Exercises: Level 2

1. Write a script that prompt the user to enter base and height of the triangle and calculate an area of a triangle (area = 0.5 x b x h).


Enter base: 20<br>
Enter height: 10<br>
The area of the triangle is 100<br>

```js
let base = parseFloat(prompt('Enter base: '));
let height = parseFloat(prompt('Enter height: '));

let area = 0.5 * base * height;

console.log('The area of the triangle is ' + area);

```
2. Write a script that prompt the user to enter side a, side b, and side c of the triangle and and calculate the perimeter of triangle (perimeter = a + b + c)


Enter side a: 5<br>
Enter side b: 4<br>
Enter side c: 3<br>
The perimeter of the triangle is 12


```js
let sideA = parseFloat(prompt('Enter side a: '));
let sideB = parseFloat(prompt('Enter side b: '));
let sideC = parseFloat(prompt('Enter side c: '));

let perimeter = sideA + sideB + sideC;

console.log('The perimeter of the triangle is ' + perimeter);
```

3. Get length and width using prompt and calculate an area of rectangle (area = length x width and the perimeter of rectangle (perimeter = 2 x (length + width))


```js
let length = parseFloat(prompt('Enter length: '));
let width = parseFloat(prompt('Enter width: '));

let area = length * width;
let perimeter = 2 * (length + width);

console.log('The area of the rectangle is ' + area);
console.log('The perimeter of the rectangle is ' + perimeter);

```
4. Get radius using prompt and calculate the area of a circle (area = pi x r x r) and circumference of a circle(c = 2 x pi x r) where pi = 3.14.

```js
let radius = parseFloat(prompt('Enter radius: '));
let pi = 3.14;

let area = pi * radius * radius;
let circumference = 2 * pi * radius;

console.log('The area of the circle is ' + area);
console.log('The circumference of the circle is ' + circumference);
```

5. Calculate the slope, x-intercept and y-intercept of y = 2x -2

```js
// emin değilim 
let y = "2x - 2";
let m = 2; // eğim
let x_intercept = -2; // x-kesişimi
let y_intercept = -2; // y-kesişimi

console.log("Slope (Eğim): " + m);
console.log("X-Kesişimi (X-Intercept): (" + x_intercept + ", 0)");
console.log("Y-Kesişimi (Y-Intercept): (0, " + y_intercept + ")");

```
6. Slope is m = (y2-y1)/(x2-x1). Find the slope between point (2, 2) and point(6,10)

```js
//emin değilim
let x1 = 2;
let y1 = 2;
let x2 = 6;
let y2 = 10;

let slope = (y2 - y1) / (x2 - x1);
console.log("The slope between point (" + x1 + ", " + y1 + ") and point (" + x2 + ", " + y2 + ") is " + slope); 
// The slope between point (2, 2) and point (6, 10) is 2

```
7. Compare the slope of above two questions.

```js

```

8. Calculate the value of y (y = x2 + 6x + 9). Try to use different x values and figure out at what x value y is 0.

```js
let x = prompt("Enter a value for x:");  // -3
let y = x*x + 6*x + 9; 
console.log("The value of y is:", y);  // 0
```

9. Writ a script that prompt a user to enter hours and rate per hour. Calculate pay of the person?


Enter hours: 40 <br>
Enter rate per hour: 28<br>
Your weekly earning is 1120<br>

```js
let hours = prompt("Enter hours:");
let rate = prompt("Enter rate per hour:");
let pay = hours * rate;

console.log("Your weekly earning is " + pay);

```

10. If the length of your name is greater than 7 say, your name is long else say your name is short.


```js
let name = prompt('enter your name');
name.length > 7
  ? console.log('your name is long')
  : console.log('your name is short')
```

11. Compare your first name length and your family name length and you should get this output.

```js
let firstName = 'Asabeneh'
let lastName = 'Yetayeh'
Your first name, Asabeneh is longer than your family name, Yetayeh
```
```js
let firstName = 'Sahide';
let lastName = 'Seker';

firstName.length > lastName.length ?
  console.log(`Your first name, ${firstName} is longer than your family name, ${lastName}`) :
  console.log(`Your family name, ${lastName} is longer than your first name, ${firstName}`);

```

12. Declare two variables myAge and yourAge and assign them initial values and myAge and yourAge.


let myAge = 250 <br>
let yourAge = 25<br>
I am 225 years older than you. <br>
```js
let myAge = 250;
let yourAge = 25;
let ageDiff = myAge - yourAge;
console.log(`I am ${ageDiff} years older than you.`);

```

13. Using prompt get the year the user was born and if the user is 18 or above allow the user to drive if not tell the user to wait a certain amount of years.


Enter birth year: 1995 <br>
You are 25. You are old enough to drive<br>


Enter birth year: 2005<br>
You are 15. You will be allowed to drive after 3 years.<br>

```js
const currentYear = new Date().getFullYear();
const birthYear = prompt('Enter birth year:');
const age = currentYear - birthYear;

age >= 18
  ? console.log(`You are ${age}. You are old enough to drive.`)
  : console.log(`You are ${age}. You will be allowed to drive after ${18 - age} years.`);

```

14. Write a script that prompt the user to enter number of years. Calculate the number of seconds a person can live. Assume some one lives just hundred years


Enter number of years you live: 100 <br>
You lived 3153600000 seconds. <br>
```js
let years = prompt("Enter number of years you live:");
let seconds = years * 365 * 24 * 60 * 60;
console.log(`You lived ${seconds} seconds.`);
 
```

15. Create a human readable time format using the Date time object


YYYY-MM-DD HH:mm <br>
DD-MM-YYYY HH:mm <br>
DD/MM/YYYY HH:mm <br>

```js
const now = new Date();
const year = now.getFullYear();
const month = now.getMonth() + 1;
const day = now.getDate();
const hour = now.getHours();
const minute = now.getMinutes();

const date1 = year + '-' + month + '-' + day + ' ' + hour + ':' + minute;
const date2 = day + '-' + month + '-' + year + ' ' + hour + ':' + minute;
const date3 = day + '/' + month + '/' + year + ' ' + hour + ':' + minute;

console.log(date1);
console.log(date2);
console.log(date3);

```
Exercises: Level 3

1. Create a human readable time format using the Date time object. The hour and the minute should be all the time two digits(7 hours should be 07 and 5 minutes should be 05 )

i. YYY-MM-DD HH:mm eg. 20120-01-02 07:05

```js
const now = new Date();
const year = now.getFullYear();
const month = ('0' + (now.getMonth() + 1)).slice(-2);
const day = ('0' + now.getDate()).slice(-2);
const hours = ('0' + now.getHours()).slice(-2);
const minutes = ('0' + now.getMinutes()).slice(-2);
const result = `${year}-${month}-${day} ${hours}:${minutes}`;

console.log(result);

```
