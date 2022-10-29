<div align="center">
  <h1> 30 Days Of JavaScript: Functions</h1>
  <a class="header-badge" target="_blank" href="https://www.linkedin.com/in/asabeneh/">
  <img src="https://img.shields.io/badge/style--5eba00.svg?label=LinkedIn&logo=linkedin&style=social">
  </a>
  <a class="header-badge" target="_blank" href="https://twitter.com/Asabeneh">
  <img alt="Twitter Follow" src="https://img.shields.io/twitter/follow/asabeneh?style=social">
  </a>

  <sub>Author:
  <a href="https://www.linkedin.com/in/asabeneh/" target="_blank">Asabeneh Yetayeh</a><br>
  <small> January, 2020</small>
  </sub>
</div>

[<< Day 6](../06_Day_Loops/06_day_loops.md) | [Day 8 >>](../08_Day_Objects/08_day_objects.md)

![Thirty Days Of JavaScript](../images/banners/day_1_7.png)

- [📔 Day 7](#-day-7)
	- [Functions](#functions)
		- [Function Declaration](#function-declaration)
		- [Function without a parameter and return](#function-without-a-parameter-and-return)
		- [Function returning value](#function-returning-value)
		- [Function with a parameter](#function-with-a-parameter)
		- [Function with two parameters](#function-with-two-parameters)
		- [Function with many parameters](#function-with-many-parameters)
		- [Function with unlimited number of parameters](#function-with-unlimited-number-of-parameters)
			- [Unlimited number of parameters in regular function](#unlimited-number-of-parameters-in-regular-function)
			- [Unlimited number of parameters in arrow function](#unlimited-number-of-parameters-in-arrow-function)
		- [Anonymous Function](#anonymous-function)
		- [Expression Function](#expression-function)
		- [Self Invoking Functions](#self-invoking-functions)
		- [Arrow Function](#arrow-function)
		- [Function with default parameters](#function-with-default-parameters)
		- [Function declaration versus Arrow function](#function-declaration-versus-arrow-function)
	- [💻 Exercises](#-exercises)
		- [Exercises: Level 1](#exercises-level-1)
		- [Exercises: Level 2](#exercises-level-2)
		- [Exercises: Level 3](#exercises-level-3)

# 📔 Day 7

## Funktionen

Bisher haben wir viele eingebaute JavaScript-Funktionen gesehen. In diesem Abschnitt werden wir uns auf benutzerdefinierte Funktionen konzentrieren. Was ist eine Funktion? Bevor wir mit der Erstellung von Funktionen beginnen, sollten wir verstehen, was eine Funktion ist und warum wir eine Funktion brauchen.

Eine Funktion ist ein wiederverwendbarer Block von Code oder Programmieranweisungen, der eine bestimmte Aufgabe erfüllt.
Eine Funktion wird durch ein Funktionsschlüsselwort deklariert, gefolgt von einem Namen und einer Klammer (). Eine Klammer kann einen Parameter enthalten. Wenn eine Funktion einen Parameter annimmt, wird sie mit einem Argument aufgerufen. Eine Funktion kann auch einen Standardparameter annehmen. Um Daten in einer Funktion zu speichern, muss eine Funktion bestimmte Datentypen zurückgeben. Um den Wert zu erhalten, rufen wir eine Funktion auf oder rufen sie auf.
Eine Funktion macht den Code:

- sauber und leicht zu lesen
- wiederverwendbar
- leicht zu testen

Eine Funktion kann auf mehrere Arten deklariert oder erstellt werden:

- _Declaration function_
- _Expression function_
- _Anonymous function_
- _Arrow function_

### Funktionsdeklaration

Sehen wir uns an, wie man eine Funktion deklariert und wie man eine Funktion aufruft.

```js
//Eine Funktion ohne Parameter deklarieren
function functionName() {
  // code goes here
}
functionName() // Aufruf der Funktion durch ihren Namen und mit Klammern
```

### Funktion ohne Parameter und Rückgabe

Eine Funktion kann ohne Parameter deklariert werden.

**Beispiel:**

```js
// Funktion ohne Parameter, eine Funktion, die eine Zahl quadratisch macht
function square() {
  let num = 2
  let sq = num * num
  console.log(sq)
}

square() // 4

// function without parameter
function addTwoNumbers() {
  let numOne = 10
  let numTwo = 20
  let sum = numOne + numTwo

  console.log(sum)
}

addTwoNumbers() // a function has to be called by its name to be executed 
```

```js
  function printFullName (){
      let firstName = 'Asabeneh'
      let lastName = 'Yetayeh'
      let space = ' '
      let fullName = firstName + space + lastName
      console.log(fullName)
}

printFullName() // calling a function
```

### Funktion gibt Wert zurück

Funktionen können auch Werte zurückgeben. Wenn eine Funktion keine Werte zurückgibt, ist der Wert der Funktion undefiniert. Schreiben wir die obigen Funktionen mit Rückgabe. Von nun an geben wir einen Wert an eine Funktion zurück, anstatt ihn auszugeben.

```js
function printFullName (){
      let firstName = 'Asabeneh'
      let lastName = 'Yetayeh'
      let space = ' '
      let fullName = firstName + space + lastName
      return fullName
}
console.log(printFullName())
```

```js

  function addTwoNumbers() {
      let numOne = 2
      let numTwo = 3
      let total = numOne + numTwo
      return total

  }

console.log(addTwoNumbers())
```

### Function with a parameter

In a function we can pass different data types(number, string, boolean, object, function) as a parameter.

```js
// function with one parameter
function functionName(parm1) {
  //code goes her
}
functionName(parm1) // during calling or invoking one argument needed

function areaOfCircle(r) {
  let area = Math.PI * r * r
  return area
}

console.log(areaOfCircle(10)) // should be called with one argument

function square(number) {
  return number * number
}

console.log(square(10))
```

### Function with two parameters

```js
// function with two parameters
function functionName(parm1, parm2) {
  //code goes her
}
functionName(parm1, parm2) // during calling or invoking two arguments needed
// Function without parameter doesn't take input, so lets make a function with parameters
function sumTwoNumbers(numOne, numTwo) {
  let sum = numOne + numTwo
  console.log(sum)
}
sumTwoNumbers(10, 20) // calling functions
// If a function doesn't return it doesn't store data, so it should return

function sumTwoNumbers(numOne, numTwo) {
  let sum = numOne + numTwo
  return sum
}

console.log(sumTwoNumbers(10, 20))
function printFullName(firstName, lastName) {
  return `${firstName} ${lastName}`
}
console.log(printFullName('Asabeneh', 'Yetayeh'))
```

### Function with many parameters

```js
// function with multiple parameters
function functionName(parm1, parm2, parm3,...){
  //code goes here
}
functionName(parm1,parm2,parm3,...) // during calling or invoking three arguments needed


// this function takes array as a parameter and sum up the numbers in the array
function sumArrayValues(arr) {
  let sum = 0;
  for (let i = 0; i < arr.length; i++) {
    sum = sum + arr[i];
  }
  return sum;
}
const numbers = [1, 2, 3, 4, 5];
    //calling a function
console.log(sumArrayValues(numbers));


    const areaOfCircle = (radius) => {
      let area = Math.PI * radius * radius;
      return area;
    }
console.log(areaOfCircle(10))

```

### Funktion mit unbegrenzter Anzahl von Parametern

Manchmal wissen wir nicht, wie viele Argumente der Benutzer übergeben wird. Daher sollten wir wissen, wie man eine Funktion schreibt, die eine unbegrenzte Anzahl von Argumenten annehmen kann. Die Art und Weise, wie wir dies tun, unterscheidet sich erheblich zwischen einer Funktionsdeklaration (reguläre Funktion) und einer Pfeilfunktion. Sehen wir uns Beispiele sowohl für die Funktionsdeklaration als auch für die Pfeilfunktion an.

#### Unbegrenzte Anzahl von Parametern in einer regulären Funktion

 Eine Funktionsdeklaration liefert ein funktionsspezifisches Argumenten-Array wie ein Objekt. Auf alles, was wir als Argument in der Funktion übergeben haben, kann über das Argumente-Objekt innerhalb der Funktionen zugegriffen werden. Hier ein Beispiel

 ```js
// Let us access the arguments object
​
function sumAllNums() {
  console.log(arguments)
}

sumAllNums(1, 2, 3, 4)
// Arguments(4) [1, 2, 3, 4, callee: ƒ, Symbol(Symbol.iterator): ƒ]

```

```js
// function declaration
​
function sumAllNums() {
  let sum = 0
  for (let i = 0; i < arguments.length; i++) {
    sum += arguments[i]
  }
  return sum
}

console.log(sumAllNums(1, 2, 3, 4)) // 10
console.log(sumAllNums(10, 20, 13, 40, 10))  // 93
console.log(sumAllNums(15, 20, 30, 25, 10, 33, 40))  // 173
```

#### Unbegrenzte Anzahl von Parametern in der Pfeilfunktion

 Die Pfeilfunktion verfügt nicht über ein Objekt mit funktionsspezifischen Argumenten. Um eine Funktion zu implementieren, die eine unbegrenzte Anzahl von Argumenten in eine Pfeilfunktion aufnimmt, verwenden wir den Spread-Operator gefolgt von einem beliebigen Parameternamen.  Alles, was wir als Argument in der Funktion übergeben haben, kann als Array in der Pfeilfunktion aufgerufen werden. Hier ein Beispiel

 ```js
// Let us access the arguments object
​
const sumAllNums = (...args) => {
  // console.log(arguments), arguments object not found in arrow function
  // instead we use a parameter followed by spread operator (...)
  console.log(args)
}

sumAllNums(1, 2, 3, 4)
// [1, 2, 3, 4]

```

```js
// function declaration
​
const sumAllNums = (...args) => {
  let sum = 0
  for (const element of args) {
    sum += element
  }
  return sum
}

console.log(sumAllNums(1, 2, 3, 4)) // 10
console.log(sumAllNums(10, 20, 13, 40, 10))  // 93
console.log(sumAllNums(15, 20, 30, 25, 10, 33, 40))  // 173
```

### Anonyme Funktion

Anonyme Funktion oder ohne Namen

```js
const anonymousFun = function() {
  console.log(
    'I am an anonymous function and my value is stored in anonymousFun'
  )
}
```

### Ausdrucksfunktion (Expression Function)

Ausdrucksfunktionen sind anonyme Funktionen. Nachdem wir eine Funktion ohne Namen erstellt haben, weisen wir sie einer Variablen zu. Um einen Wert aus der Funktion zurückzugeben, müssen wir die Variable aufrufen. Sehen Sie sich das folgende Beispiel an.

```js

// Function expression
const square = function(n) {
  return n * n
}

console.log(square(2)) // -> 4
```

### Selbstaufrufende Funktionen

Selbstaufrufende Funktionen sind anonyme Funktionen, die nicht aufgerufen werden müssen, um einen Wert zurückzugeben.

```js
(function(n) {
  console.log(n * n)
})(2) // 4, but instead of just printing if we want to return and store the data, we do as shown below

let squaredNum = (function(n) {
  return n * n
})(10)

console.log(squaredNum)
```

### Pfeilfunktion (Arrow Function)

Die Pfeilfunktion ist eine Alternative zur Funktionsdeklaration, allerdings gibt es zwischen der Funktionsdeklaration und der Pfeilfunktion einige kleine Unterschiede.

Die Pfeilfunktion verwendet den Pfeil anstelle des Schlüsselworts *Funktion*, um eine Funktion zu deklarieren. Schauen wir uns sowohl die Funktionsdeklaration als auch die Pfeilfunktion an.

```js
// So schreiben wir eine normale oder Deklarationsfunktion
// Ändern wir diese Deklarationsfunktion in eine Pfeilfunktion
function square(n) {
  return n * n
}

console.log(square(2)) // 4

const square = n => {
  return n * n
}

console.log(square(2))  // -> 4

// wenn wir nur eine Zeile im Codeblock haben, kann er wie folgt geschrieben werden, explizite Rückgabe
const square = n => n * n  // -> 4
```

```js
const changeToUpperCase = arr => {
  const newArr = []
  for (const element of arr) {
    newArr.push(element.toUpperCase())
  }
  return newArr
}

const countries = ['Finland', 'Sweden', 'Norway', 'Denmark', 'Iceland']
console.log(changeToUpperCase(countries))

// ["FINLAND", "SWEDEN", "NORWAY", "DENMARK", "ICELAND"]
```

```js
const printFullName = (firstName, lastName) => {
  return `${firstName} ${lastName}`
}

console.log(printFullName('Asabeneh', 'Yetayeh'))
```

The above function has only the return statement, therefore, we can explicitly return it as follows.

```js
const printFullName = (firstName, lastName) => `${firstName} ${lastName}`

console.log(printFullName('Asabeneh', 'Yetayeh'))
```

### Function with default parameters

Sometimes we pass default values to parameters, when we invoke the function if we do not pass an argument the default value will be used. Both function declaration and arrow function can have a default value or values.

```js
// syntax
// Declaring a function
function functionName(param = value) {
  //codes
}

// Calling function
functionName()
functionName(arg)
```

**Example:**

```js
function greetings(name = 'Peter') {
  let message = `${name}, welcome to 30 Days Of JavaScript!`
  return message
}

console.log(greetings())
console.log(greetings('Asabeneh'))
```

```js
function generateFullName(firstName = 'Asabeneh', lastName = 'Yetayeh') {
  let space = ' '
  let fullName = firstName + space + lastName
  return fullName
}

console.log(generateFullName())
console.log(generateFullName('David', 'Smith'))
```

```js
function calculateAge(birthYear, currentYear = 2019) {
  let age = currentYear - birthYear
  return age
}

console.log('Age: ', calculateAge(1819))
```

```js
function weightOfObject(mass, gravity = 9.81) {
  let weight = mass * gravity + ' N' // the value has to be changed to string first
  return weight
}

console.log('Weight of an object in Newton: ', weightOfObject(100)) // 9.81 gravity at the surface of Earth
console.log('Weight of an object in Newton: ', weightOfObject(100, 1.62)) // gravity at surface of Moon
```

Let us see how we write the above functions with arrow functions

```js
// syntax
// Declaring a function
const functionName = (param = value) => {
  //codes
}

// Calling function
functionName()
functionName(arg)
```

**Example:**

```js
const greetings = (name = 'Peter') => {
  let message = name + ', welcome to 30 Days Of JavaScript!'
  return message
}

console.log(greetings())
console.log(greetings('Asabeneh'))
```

```js
const generateFullName = (firstName = 'Asabeneh', lastName = 'Yetayeh') => {
  let space = ' '
  let fullName = firstName + space + lastName
  return fullName
}

console.log(generateFullName())
console.log(generateFullName('David', 'Smith'))
```

```js

const calculateAge = (birthYear, currentYear = 2019) => currentYear - birthYear
console.log('Age: ', calculateAge(1819))
```

```js
const weightOfObject = (mass, gravity = 9.81) => mass * gravity + ' N'
  
console.log('Weight of an object in Newton: ', weightOfObject(100)) // 9.81 gravity at the surface of Earth
console.log('Weight of an object in Newton: ', weightOfObject(100, 1.62)) // gravity at surface of Moon
```

### Function declaration versus Arrow function

It Will be covered in other section.

🌕 You are a rising star, now you knew function . Now, you are super charged with the power of functions. You have just completed day 7 challenges and you are 7 steps a head in to your way to greatness. Now do some exercises for your brain and for your muscle.



## 💻 Exercises

### Exercises: Level 1

1. Declare a function _fullName_ and it print out your full name.
2. Declare a function _fullName_ and now it takes firstName, lastName as a parameter and it returns your full - name.
3. Declare a function _addNumbers_ and it takes two two parameters and it returns sum.
4. An area of a rectangle is calculated as follows: _area = length x width_. Write a function which calculates _areaOfRectangle_.
5. A perimeter of a rectangle is calculated as follows: _perimeter= 2x(length + width)_. Write a function which calculates _perimeterOfRectangle_.
6. A volume of a rectangular prism is calculated as follows: _volume = length x width x height_. Write a function which calculates _volumeOfRectPrism_.
7. Area of a circle is calculated as follows: _area = π x r x r_. Write a function which calculates _areaOfCircle_
8. Circumference of a circle is calculated as follows: _circumference = 2πr_. Write a function which calculates _circumOfCircle_
9. Density of a substance is calculated as follows:_density= mass/volume_. Write a function which calculates _density_.
10. Speed is calculated by dividing the total distance covered by a moving object divided by the total amount of time taken. Write a function which calculates a speed of a moving object, _speed_.
11. Weight of a substance is calculated as follows: _weight = mass x gravity_. Write a function which calculates _weight_.
12. Temperature in oC can be converted to oF using this formula: _oF = (oC x 9/5) + 32_. Write a function which convert oC to oF _convertCelsiusToFahrenheit_.
13. Body mass index(BMI) is calculated as follows: _bmi = weight in Kg / (height x height) in m2_. Write a function which calculates _bmi_. BMI is used to broadly define different weight groups in adults 20 years old or older.Check if a person is _underweight, normal, overweight_ or _obese_ based the information given below.

    - The same groups apply to both men and women.
    - _Underweight_: BMI is less than 18.5
    - _Normal weight_: BMI is 18.5 to 24.9
    - _Overweight_: BMI is 25 to 29.9
    - _Obese_: BMI is 30 or more

14. Write a function called _checkSeason_, it takes a month parameter and returns the season:Autumn, Winter, Spring or Summer.
15. Math.max returns its largest argument. Write a function findMax that takes three arguments and returns their maximum with out using Math.max method.

    ```js
    console.log(findMax(0, 10, 5))
    10
    console.log(findMax(0, -10, -2))
    0
    ```
  
### Exercises: Level 2

1. Linear equation is calculated as follows: _ax + by + c = 0_. Write a function which calculates value of a linear equation, _solveLinEquation_.
1. Quadratic equation is calculated as follows: _ax2 + bx + c = 0_. Write a function which calculates value or values of a quadratic equation, _solveQuadEquation_.

    ```js
    console.log(solveQuadratic()) // {0}
    console.log(solveQuadratic(1, 4, 4)) // {-2}
    console.log(solveQuadratic(1, -1, -2)) // {2, -1}
    console.log(solveQuadratic(1, 7, 12)) // {-3, -4}
    console.log(solveQuadratic(1, 0, -4)) //{2, -2}
    console.log(solveQuadratic(1, -1, 0)) //{1, 0}
    ```

1. Declare a function name _printArray_. It takes array as a parameter and it prints out each value of the array.
1. Write a function name _showDateTime_ which shows time in this format: 08/01/2020 04:08 using the Date object.

    ```sh
    showDateTime()
    08/01/2020 04:08
    ```

1. Declare a function name _swapValues_. This function swaps value of x to y.

    ```js
    swapValues(3, 4) // x => 4, y=>3
    swapValues(4, 5) // x = 5, y = 4
    ```

1. Declare a function name _reverseArray_. It takes array as a parameter and it returns the reverse of the array (don't use method).

    ```js
    console.log(reverseArray([1, 2, 3, 4, 5]))
    //[5, 4, 3, 2, 1]
    console.log(reverseArray(['A', 'B', 'C']))
    //['C', 'B', 'A']
    ```

1. Declare a function name _capitalizeArray_. It takes array as a parameter and it returns the - capitalizedarray.
1. Declare a function name _addItem_. It takes an item parameter and it returns an array after adding the item
1. Declare a function name _removeItem_. It takes an index parameter and it returns an array after removing an item
1. Declare a function name _sumOfNumbers_. It takes a number parameter and it adds all the numbers in that range.
1. Declare a function name _sumOfOdds_. It takes a number parameter and it adds all the odd numbers in that - range.
1. Declare a function name _sumOfEven_. It takes a number parameter and it adds all the even numbers in that - range.
1. Declare a function name evensAndOdds . It takes a positive integer as parameter and it counts number of evens and odds in the number.

    ```sh
    evensAndOdds(100);
    The number of odds are 50.
    The number of evens are 51.
    ```

1. Write a function which takes any number of arguments and return the sum of the arguments

    ```js
    sum(1, 2, 3) // -> 6
    sum(1, 2, 3, 4) // -> 10
    ```

1. Writ a function which generates a _randomUserIp_.
1. Write a function which generates a _randomMacAddress_
1. Declare a function name _randomHexaNumberGenerator_. When this function is called it generates a random hexadecimal number. The function return the hexadecimal number.

    ```sh
    console.log(randomHexaNumberGenerator());
    '#ee33df'
    ```

1. Declare a function name _userIdGenerator_. When this function is called it generates seven character id. The function return the id.

    ```sh
    console.log(userIdGenerator());
    41XTDbE
    ```

### Exercises: Level 3

1. Modify the _userIdGenerator_ function. Declare a function name _userIdGeneratedByUser_. It doesn’t take any parameter but it takes two inputs using prompt(). One of the input is the number of characters and the second input is the number of ids which are supposed to be generated.

    ```sh
    userIdGeneratedByUser()
    'kcsy2
    SMFYb
    bWmeq
    ZXOYh
    2Rgxf
    '
    userIdGeneratedByUser()
    '1GCSgPLMaBAVQZ26
    YD7eFwNQKNs7qXaT
    ycArC5yrRupyG00S
    UbGxOFI7UXSWAyKN
    dIV0SSUTgAdKwStr
    '
    ```

1. Write a function name _rgbColorGenerator_ and it generates rgb colors.

    ```sh
    rgbColorGenerator()
    rgb(125,244,255)
    ```

1. Write a function **_arrayOfHexaColors_** which return any number of hexadecimal colors in an array.
1. Write a function **_arrayOfRgbColors_** which return any number of RGB colors in an array.
1. Write a function **_convertHexaToRgb_** which converts hexa color to rgb and it returns an rgb color.
1. Write a function **_convertRgbToHexa_** which converts rgb to hexa color and it returns an hexa color.
1. Write a function **_generateColors_** which can generate any number of hexa or rgb colors.

    ```js
    console.log(generateColors('hexa', 3)) // ['#a3e12f', '#03ed55', '#eb3d2b']
    console.log(generateColors('hexa', 1)) // '#b334ef'
    console.log(generateColors('rgb', 3)) // ['rgb(5, 55, 175)', 'rgb(50, 105, 100)', 'rgb(15, 26, 80)']
    console.log(generateColors('rgb', 1)) // 'rgb(33,79, 176)'
    ```

1. Call your function _shuffleArray_, it takes an array as a parameter and it returns a shuffled array
1. Call your function _factorial_, it takes a whole number as a parameter and it return a factorial of the number
1. Call your function _isEmpty_, it takes a parameter and it checks if it is empty or not
1. Call your function _sum_, it takes any number of arguments and it returns the sum.
1. Write a function called _sumOfArrayItems_, it takes an array parameter and return the sum of all the items. Check if all the array items are number types. If not give return reasonable feedback.
1. Write a function called _average_, it takes an array parameter and returns the average of the items. Check if all the array items are number types. If not give return reasonable feedback.
1. Write a function called _modifyArray_ takes array as parameter and modifies the fifth item of the array and return the array. If the array length is less than five it return 'item not found'.

    ```js
    console.log(modifyArray(['Avocado', 'Tomato', 'Potato','Mango', 'Lemon','Carrot']);
    ```

    ```sh
    ['Avocado', 'Tomato', 'Potato','Mango', 'LEMON', 'Carrot']
    ```

    ```js
    console.log(modifyArray(['Google', 'Facebook','Apple', 'Amazon','Microsoft',  'IBM']);
    ```

    ```sh
    ['Google', 'Facebook','Apple', 'Amazon','MICROSOFT',  'IBM']
    ```

    ```js
    console.log(modifyArray(['Google', 'Facebook','Apple', 'Amazon']);
    ```

    ```sh
      'Not Found'
    ```

1. Write a function called _isPrime_, which checks if a number is prime number.
1. Write a functions which checks if all items are unique in the array.
1. Write a function which checks if all the items of the array are the same data type.
1. JavaScript variable name does not support special characters or symbols except \$ or \_. Write a function **isValidVariable** which check if a variable is valid or invalid variable.
1. Write a function which returns array of seven random numbers in a range of 0-9. All the numbers must be unique.

    ```js
    sevenRandomNumbers()
    [(1, 4, 5, 7, 9, 8, 0)]
    ```

1. Write a function called reverseCountries, it takes countries array and first it copy the array and returns the reverse of the original array

🎉 CONGRATULATIONS ! 🎉

[<< Day 6](../06_Day_Loops/06_day_loops.md) | [Day 8 >>](../08_Day_Objects/08_day_objects.md)
