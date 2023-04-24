 💻 Day 2: Exercises

Exercise: Level 1

1. Declare a variable named challenge and assign it to an initial value '30 Days Of JavaScript'.
 
```javascript 
let challenge = '30 Days Of JavaScript';
```

2. Print the string on the browser console using console.log()

```javascript
let challenge = '30 Days Of JavaScript';
console.log(challenge);

```
3. Print the length of the string on the browser console using console.log()

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.length); // 21
```
4. Change all the string characters to capital letters using toUpperCase() method

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.toUpperCase()); //30 DAYS OF JAVASCRIPT
```

5. Change all the string characters to lowercase letters using toLowerCase() method

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.toLowerCase()); //30 days of javascript

```
6. Cut (slice) out the first word of the string using substr() or substring() method


```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.substring(0, 2)); // 30

```
```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.substr(0, 2)); // 30

```

7. Slice out the phrase Days Of JavaScript from 30 Days Of JavaScript.

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.substring(3)); // "Days Of JavaScript"

```
```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.substr(3)); // "Days Of JavaScript"

```

8. Check if the string contains a word Script using includes() method

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.includes('Script')); // true

```
9. Split the string into an array using split() method

```javascript 
let challenge = '30 Days Of JavaScript';
let challengeArray = challenge.split(' ');
console.log(challengeArray); // ["30", "Days", "Of", "JavaScript"]

```
10. Split the string 30 Days Of JavaScript at the space using split() method

```javascript 
let challenge = '30 Days Of JavaScript';
let challengeArray = challenge.split(' ');
console.log(challengeArray); // ["30", "Days", "Of", "JavaScript"]

```
11. 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' split the string at the comma and change it to an array.


```javascript 
let companyNames = 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon';
let companies = companyNames.split(', ');
console.log(companies); // ["Facebook", "Google", "Microsoft", "Apple", "IBM", "Oracle", "Amazon"]

```
12. Change 30 Days Of JavaScript to 30 Days Of Python using replace() method.

```javascript 
let challenge = '30 Days Of JavaScript';
let newChallenge = challenge.replace('JavaScript', 'Python');
console.log(newChallenge); // "30 Days Of Python"

```
13. What is character at index 15 in '30 Days Of JavaScript' string? Use charAt() method.

```javascript 
let string = '30 Days Of JavaScript'
console.log(string.charAt(15)) // S

```
14. What is the character code of J in '30 Days Of JavaScript' string using charCodeAt()

```javascript 
let string = '30 Days Of Javascript';
console.log(string.charCodeAt(11)); // 74

```
15. Use indexOf to determine the position of the first occurrence of a in 30 Days Of JavaScript

```javascript 
let challenge = '30 Days of JavaScript';
console.log(challenge.indexOf('a')); // 4

```
16. Use lastIndexOf to determine the position of the last occurrence of a in 30 Days Of JavaScript.


```javascript 
let challenge = '30 Days of JavaScript';
console.log(challenge.lastIndexOf('a')); // 14

```
17. Use indexOf to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'


```javascript 
let string = 'You cannot end a sentence with because because because is a conjunction';
let index = string.indexOf('because');
console.log(index); // 31
```

18. Use lastIndexOf to find the position of the last occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```javascript 
let string = "You cannot end a sentence with because because because is a conjunction";
let lastIndex = string.lastIndexOf('because');
console.log(lastIndex); // 47

```

19. Use search to find the position of the first occurrence of the word because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```javascript 
let string = "You cannot end a sentence with because because because is a conjunction";
let index = string.search('because');
console.log(index); // 31

```
20. Use trim() to remove any trailing whitespace at the beginning and the end of a string.E.g ' 30 Days Of JavaScript '.

```javascript 
let challenge = ' 30 Days Of JavaScript ';
console.log(challenge.trim()); // '30 Days Of JavaScript'

```
21. Use startsWith() method with the string 30 Days Of JavaScript and make the result true

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.startsWith('30 Days')); // true

```
22. Use endsWith() method with the string 30 Days Of JavaScript and make the result true

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.endsWith('JavaScript')); // true
```
23. Use match() method to find all the a’s in 30 Days Of JavaScript

```javascript 
let challenge = "30 Days Of Javascript";
let index = challenge.match(/a/g);
console.log(index); // [ 'a', 'a', 'a' ]

```
24. Use concat() and merge '30 Days of' and 'JavaScript' to a single string, '30 Days Of JavaScript'

```javascript 
let string1 = '30 Days of';
let string2 = ' JavaScript';
let challenge = string1.concat(string2);
console.log(challenge); // "30 Days of JavaScript"

```
```javascript 
let challenge = '30 Days of'.concat(' JavaScript');
console.log(challenge ); // "30 Days of JavaScript"

```

25. Use repeat() method to print 30 Days Of JavaScript 2 times

```javascript
let challenge = '30 Days Of JavaScript';
console.log(challenge.repeat(2));

```
Exercise: Level 2

1. Using console.log() print out the following statement:

```js
The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.
```
```javascript
console.log("The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.");
```

2. Using console.log() print out the following quote by Mother Teresa:
```js
"Love is not patronizing and charity isn't about pity, it is about love. Charity and love are the same -- with charity you give love, so don't just give money but reach out your hand instead."
```

```javascript
console.log('"Love is not patronizing and charity isn\'t about pity, it is about love. Charity and love are the same -- with charity you give love, so don\'t just give money but reach out your hand instead." - Mother Teresa');
```

3. Check if typeof '10' is exactly equal to 10. If not make it exactly equal.

```javascript
// Step-1
let num1 ='10';
let num2 = 10;
console.log(num1 == num2); // false

```
```js
// Step-2
let num2 = 10;
let num1 = parseInt('10');

console.log(num1 == num2); // true

```

4. Check if parseFloat('9.8') is equal to 10 if not make it exactly equal with 10.

```js
let num1 = parseFloat('9.8');
console.log(num1 == 10);
```
```js
let num2 = parseInt(num1 = "10");
console.log(num2 == 10);
```

5. Check if 'on' is found in both python and jargon

```js
let str1 = "Python";
console.log(str1.includes("on")); // true

let str2 = "Jargon";
console.log(str2.includes("on")); // true
```

```js
let str1 = "Python";
let str2 = "Jargon";

console.log(str1.includes("on") && str2.includes("on")); // true
```

6. I hope this course is not full of jargon. Check if jargon is in the sentence.

```js
let sentence = "I hope this course is not full of jargon";
console.log(sentence.includes("jargon")); // true
```

7. Generate a random number between 0 and 100 inclusively.

```js
const randomNumber = Math.floor(Math.random() * 101); 
console.log(randomNumber); // a random number between 0 and 100 
```
8. Generate a random number between 50 and 100 inclusively.

```js
let randomNumber = Math.floor(Math.random() * 51) + 50; 
console.log(randomNumber); // a random number between 50 and 100 
```


9. Generate a random number between 0 and 255 inclusively.

```js
let randomNumber = Math.floor(Math.random() * 256);
console.log(randomNumber); // a random number between 0 and 255 
```

10. Access the 'JavaScript' string characters using a random number.

```js
let str = "Javascript";
let randomNum = Math.floor(Math.random() * str.length);
let randomChar = str[randomNum];
console.log(randomChar); // random letter
```

11. Use console.log() and escape characters to print the following pattern.

```js
1 1 1 1 1
2 1 2 4 8
3 1 3 9 27
4 1 4 16 64
5 1 5 25 125
```

```js
console.log('1 1 1 1 1\n2 1 2 4 8\n3 1 3 9 27\n4 1 4 16 64\n5 1 5 25 125');
```

12. Use substr to slice out the phrase because because because from the following sentence:'You cannot end a sentence with because because because is a conjunction'

```js
let sentence = 'You cannot end a sentence with because because because is a conjunction';
let result = sentence.substr(28, 23); 
console.log(result); // because because because
```

Exercises: Level 3

1. 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Count the number of word love in this sentence.

```js
let sentence = 'Love is the best thing in this world. Some found their love and some are still looking for their love.';
let index = (sentence.match(/love/gi) || []).length;
console.log(index); // 3
````

2. Use match() to count the number of all because in the following sentence:'You cannot end a sentence with because because because is a conjunction'

```js
let sentence = "You cannot end a sentence with because because because is a conjunction";
let index = (sentence.match(/because/g) || []).length;
console.log(index); // 3
 // 3
```

3. Clean the following text and find the most frequent word (hint, use replace and regular expressions).

```js 
// bu sorudan emin değilim
```

```js
const sentence = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
```
4. Calculate the total annual income of the person by extracting the numbers from the following text. 'He earns 5000 euro from salary per month, 10000 euro annual bonus, 15000 euro online courses per month.'


```js
const monthlySalary = 5000;
const onlineCourseIncome = 15000;
const annualBonus = 10000;

const annualIncome = (monthlySalary + onlineCourseIncome) * 12 + annualBonus;

console.log(`Yearly total: ${annualIncome} euro`);

```

































