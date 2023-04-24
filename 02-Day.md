💻 Gün 2: Egzersizleri

Exercise: Seviye 1

1. Challenge adında bir değişken tanımlayın ve '30 Days Of JavaScript' başlangıç ​​değerine atayın.
 
```javascript 
let Challenge = '30 Days Of JavaScript';
```

2. console.log() kullanarak tarayıcı konsolunda değişkeni yazdırın,

```javascript
let Challenge = '30 Days Of JavaScript';
console.log(Challenge);

```
3. console.log() kullanarak tarayıcı konsolunda dizenin length değerini yazdırın,

```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.length); // 21
```
4. toUpperCase() yöntemini kullanarak tüm dize karakterlerini büyük harflerle değiştirin,

```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.toUpperCase()); //30 DAYS OF JAVASCRIPT
```

5. toLowerCase() yöntemini kullanarak tüm dize karakterlerini küçük harflerle değiştirin,

```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.toLowerCase()); //30 days of javascript

```
6. substr() veya substring() yöntemini kullanarak string'in ilk kelimesini kesin-silin (dilimleyin)

```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.substring(0, 2)); // 30

```
```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.substr(0, 2)); // 30

```

7. Days Of JavaScript ifadesini 30 Days Of JavaScript'ten ayırın.

```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.substring(3)); // "Days Of JavaScript"

```
```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.substr(3)); // "Days Of JavaScript"

```

8. includes() yöntemini kullanarak string'in Script kelimesini içerip içermediğini kontrol edin

```javascript 
let Challenge = '30 Days Of JavaScript';
console.log(Challenge.includes('Script')); // true

```
9. split() yöntemini kullanarak string öğesini bir array'ye bölün

```javascript 
let Challenge = '30 Days Of JavaScript';
let ChallengeArray = Challenge.split(' ');
console.log(ChallengeArray); // ["30", "Days", "Of", "JavaScript"]

```
10. 30 Days Of JavaScript dizesini split() yöntemini kullanarak boşlukta bölün

```javascript 
let Challenge = '30 Days Of JavaScript';
let ChallengeArray = Challenge.split(' ');
console.log(ChallengeArray); // ["30", "Days", "Of", "JavaScript"]

```
11. 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' dizeyi virgülden split ve bir dizi olarak değiştirin.


```javascript 
let companyNames = 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon';
let companies = companyNames.split(', ');
console.log(companies); // ["Facebook", "Google", "Microsoft", "Apple", "IBM", "Oracle", "Amazon"]

```
12. replace() yöntemini kullanarak 30 Days of JavaScript'i 30 Days of Python olarak değiştirin.

```javascript 
let challenge = '30 Days Of JavaScript';
let newChallenge = challenge.replace('JavaScript', 'Python');
console.log(newChallenge); // "30 Days Of Python"

```
13. 'JavaScript'in 30 Günü' dizesinde dizin 15'teki karakter nedir? charAt() yöntemini kullanın.

```javascript 
let string = '30 Days Of JavaScript'
console.log(string.charAt(15)) // S

```
14. charCodeAt() kullanan 'JavaScript'in 30 Günü' dizesindeki J karakter kodu nedir?

```javascript 
let string = '30 Days Of Javascript';
console.log(string.charCodeAt(11)); // 74

```
15. 30 Days of JavaScript'te a öğesinin ilk oluşumunun konumunu belirlemek için indexOf kullanın

```javascript 
let Challenge = '30 Days of JavaScript';
console.log(Challenge.indexOf('a')); // 4

```
16. 30 Days of JavaScript'te a öğesinin son oluşumunun konumunu belirlemek için lastIndexOf kullanın.

```javascript 
let Challenge = '30 Days of JavaScript';
console.log(Challenge.lastIndexOf('a')); // 15

```
17. Aşağıdaki cümlede çünkü kelimesinin ilk geçtiği yeri bulmak için indexOf kullanın: 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır'


```javascript 
let string = 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır';
let index = string.indexOf('çünkü');
console.log(index); // 12
```

18. Aşağıdaki cümlede çünkü kelimesinin son geçtiği yeri bulmak için lastIndexOf kullanın: 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır'

```javascript 
let string = 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır';
let lastIndex = string.lastIndexOf('çünkü');
console.log(lastIndex); // 43

```

19. Aşağıdaki cümlede çünkü kelimesinin ilk geçtiği yeri bulmak için search kullanın: 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır'

```javascript 
let string = 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır';
let index = string.search('çünkü');
console.log(index); // 12

```
20. Bir dizgenin başındaki ve sonundaki boşlukları kaldırmak için trim() kullanın. Örneğin '30 Days Of JavaScript'.

```javascript 
let challenge = ' 30 Days Of JavaScript ';
console.log(challenge.trim()); // '30 Days Of JavaScript'

```
21. 30 Days Of JavaScript dizesiyle startsWith() yöntemini kullanın ve sonucu doğru yapın

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.startsWith('30')); // true

```
22. 30 Days Of JavaScript dizesiyle endsWith() yöntemini kullanın ve sonucu doğru yapın

```javascript 
let challenge = '30 Days Of JavaScript';
console.log(challenge.endsWith('JavaScript')); // true
```
23. JavaScript'in 30 Günü'ndeki tüm a'leri bulmak için match() yöntemini kullanın

```javascript 
let challenge = "30 Days Of Javascript";
let index = challenge.match(/a/g);
console.log(index); // [ 'a', 'a', 'a' ]

```
24. concat() kullanın ve '30 Days of' ve 'JavaScript'i tek bir dize olan '30 Days of JavaScript' ile birleştirin

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

25. 30 Gün JavaScript'i 2 kez yazdırmak için repeat() yöntemini kullanın

```javascript
let challenge = '30 Gün JavaScript';
console.log(challenge.repeat(2));

```
Egzersiz: Seviye 2

1. console.log() kullanarak aşağıdaki ifadeyi yazdırın:

```javascript
console.log("The quote 'There is no exercise better for the heart than reaching down and lifting people up.' by John Holmes teaches us to help one another.");
```

2. console.log()'u kullanarak Rahibe Teresa'nın aşağıdaki alıntısını yazdırın:

```javascript
console.log('"Love is not patronizing and charity isn\'t about pity, it is about love. Charity and love are the same -- with charity you give love, so don\'t just give money but reach out your hand instead."');
```

3. '10' tipinin tam olarak 10'a eşit olup olmadığını kontrol edin. Değilse tam olarak eşit yapın.

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

4. parseFloat('9.8') 10'a tam olarak eşit değilse, 10'a eşit olup olmadığını kontrol edin.


```js
let num = parseFloat('9.8');
console.log(num == 10);
```

5. Hem python hem de jargonda 'on' ifadesinin bulunup bulunmadığını kontrol edin

```js
let str = "Python";
console.log(str.includes("on")); // true

str = "Jargon";
console.log(str.includes("on")); // true
```

6. Umarım bu kurs jargonla dolu değildir. Cümlede jargon olup olmadığını kontrol edin.

```js
let str = "Umarım bu kurs jargonla dolu değildir.";
console.log(str.includes("jargon")); // true
```

7. 0 ile 100 arasında rastgele bir sayı üretin.

```js
const randomNumber = Math.floor(Math.random() * 101); 
console.log(randomNumber); // 0 ile 100 arasında bir tamsayı verir
```
8. 50 ile 100 arasında rastgele bir sayı üretin.

```js
let randomNumber = Math.floor(Math.random() * 51) + 50; 
console.log(randomNumber); // 50 ile 100 arasında bir tamsayı verir.
```


9. Dahil olmak üzere 0 ile 255 arasında rastgele bir sayı oluşturun.

```js
let randomNumber = Math.floor(Math.random() * 256);
console.log(randomNumber); // 0 ile 255 arasında bir tamsayı verir.

```

10. Rastgele bir sayı kullanarak 'JavaScript' dize karakterlerine erişin.

```js
let str = "Javascript";
let randomNum = Math.floor(Math.random() * str.length);
let randomChar = str[randomNum];
console.log(randomChar); // random harf verir
```
11. Aşağıdaki kalıbı yazdırmak için console.log() ve kaçış karakterlerini kullanın.

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

12. substr kullanarak çünkü çünkü ifadesini aşağıdaki cümleden ayırın:'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır'

```js
// bu soruyu yanlış anlamış olabilirim.
let sentence = "Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır";
let index = sentence.indexOf("çünkü çünkü");
let newSentence = sentence.substr(0, index) + sentence.substr(index + "çünkü çünkü".length);

console.log(newSentence); // Bir cümleyi çünkü ile bitiremezsiniz  bir bağlaçtır
```

Egzersiz: Seviye 3

1. 'Love is the best thing in this world. Some found their love and some are still looking for their love.' Bu cümledeki love kelimesini sayın.

```js
let sentence = 'Love is the best thing in this world. Some found their love and some are still looking for their love.';
let index = (sentence.match(/love/gi) || []).length;
console.log(index); // 3
````

2. Aşağıdaki cümledeki tüm çünkü sayısını saymak için match() kullanın:'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır'

```js
let sentence = 'Bir cümleyi çünkü ile bitiremezsiniz çünkü çünkü bir bağlaçtır';
let index = (sentence.match(/çünkü/g) || []).length;
console.log(index); // 3
```

3. Aşağıdaki metni temizleyin ve en sık kullanılan kelimeyi bulun (ipucu, değiştirme ve normal ifadeleri kullanın).

```js 
// bu sorudan emin değilim
```

```js
const sentence = '%I $am@% a %tea@cher%, &and& I lo%#ve %te@a@ching%;. The@re $is no@th@ing; &as& mo@re rewarding as educa@ting &and& @emp%o@weri@ng peo@ple. ;I found tea@ching m%o@re interesting tha@n any ot#her %jo@bs. %Do@es thi%s mo@tiv#ate yo@u to be a tea@cher!? %Th#is 30#Days&OfJavaScript &is al@so $the $resu@lt of &love& of tea&ching'
```
4. Aşağıdaki metinden sayıları çıkararak kişinin yıllık toplam gelirini hesaplayın.

'Aylık maaşından 5000 euro, yıllık 10000 euro ikramiye, ayda 15000 euro online kurstan kazanıyor.'

```js
const monthlySalary = 5000;
const onlineCourseIncome = 15000;
const annualBonus = 10000;

const annualIncome = (monthlySalary + onlineCourseIncome) * 12 + annualBonus;

console.log(`Kişinin yıllık toplam geliri: ${annualIncome} euro`);

```

































