# javascript
JavaScript Assignment


FAQ

Q: Approach to attempt these questions?
Ans: Create a new folder and inside that you have to create folder based on the question number (01 Question) then create the required files inside that to solve the problem.

Q: Where we have to submit it?
Ans: Push your folder on github and submit the repo link inside the dashboard of ineuron.



JavaScript Questions:-

## Question 1

01. Create a variable.js file and declare variables and assign string, boolean, undefined and null data types, Display all the value with their data type.

#### Topics 

	- Declaring a variable, assign string, boolean, undefined and null data types, displaying value with data type

#### Code
``` javascript
var name = "Diki Dev";
var isMarried = true;
var age;
var children = null;

console.log("Name: ", name, "Data Type: ", typeof name);
console.log("Is Married: ", isMarried, "Data Type: ", typeof isMarried);
console.log("Age: ", age, "Data Type: ", typeof age);
console.log("Children: ", children, "Data Type: ", typeof children);


```

### Output Explained
This code declares four variables: name, isMarried, age, and children. It then assigns values to the name and isMarried variables, leaving the age variable as undefined and the children variable as null. Finally, the code uses console.log to display the value and data type of each variable.

## Question 2

02. Declare variables to store your first name, last name, marital status, country and age and display them using interploation method.

### Topics
	- declare variables, intrepolation 

### Code
``` javascript
var firstName = "Diki";
var lastName = "Dev";
var maritalStatus = "Married";
var country = "Ireland";
var age = 33;

console.log(`My name is ${firstName} ${lastName}. My marital status is ${maritalStatus}. I am from ${country} and I am ${age} years old.`);
```

### Output Explained
This code declares five variables: firstName, lastName, marital status, country, age. The output forms a sentence of these variables to form a sentence. 


## Question 3
03. Declare a variable and assign string value to it and change all the string characters to capital letters using toUpperCase() method.

#### Topics
	- declare variable, assign string value, toUpperCase() method 
#### Code 
``` javascript
var message = "hello world";
message = message.toUpperCase();
console.log(message);
```

#### Output Explained
Output will be the message in caps letters. HELLO WORLD


## Question 4
04. Declare a variable and assign string value to it and check if the string contains a word Script using includes() method.
#### Topics
	- declare variable, assign string value, includes() method

#### Code 
``` javascript
var message = "Hello, welcome to the world of JavaScript";
var word = "Script";
var result = message.includes(word);
console.log(result);
```

#### Output Explained
Output will false
#### Notes
The includes() method is case-sensitive, so if you wanted to perform a case-insensitive search, you would need to convert both the string and the search word to the same case before using includes().


## Question 5
05. Declare a variable and assign string value to it and then split it into an array using split() method
#### Topics
	- declare vaiable, assign string, split() into array

#### Code 
``` javascript
let message = "Hello, welcome to the world of JavaScript";
let words = message.split(" ");
console.log(words);
```

#### Output Explained
``` javascript 
[ 'Hello,', 'welcome', 'to', 'the', 'world', 'of', 'JavaScript' ]
```

In this example, the split() method is used to split the string message into an array of words, using a space character as the separator. The resulting array is stored in the variable words.

## Question 6
06. 'Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon' split the string at the comma and change it to an array.
#### Topics
	- split() method, change string to array

#### Code 
``` javascript
let companies = "Facebook, Google, Microsoft, Apple, IBM, Oracle, Amazon";
let companyList = companies.split(", ");
console.log(companyList);
```

#### Output Explained
``` javascript
[ 'Facebook', 'Google', 'Microsoft', 'Apple', 'IBM', 'Oracle', 'Amazon' ]
```

The split() method is used to split the string companies at each comma and space, creating an array of separate company names, which is stored in the variable companyList.

## Question 7
07. Declare an array containing the multiple values and use lastIndexOf to determine the position of the first and last occurrence of a word "pw skills".
#### Topics
	- declare array, lastIndexOf, determine first and last occurance of value in array

#### Code 
``` javascript
var courses = ["javascript", "nodejs", "pw skills", "mongodb", "pw skills", "expressjs"];
var firstIndex = courses.indexOf("pw skills");
var lastIndex = courses.lastIndexOf("pw skills");
console.log("First occurrence of 'pw skills' at index: ", firstIndex);
console.log("Last occurrence of 'pw skills' at index: ", lastIndex);

```

#### Output Explained
``` javascript
First occurrence of 'pw skills' at index: 2
Last occurrence of 'pw skills' at index: 4
```

In this example, the indexOf() method is used to find the first occurrence of the word "pw skills" in the array courses, and the lastIndexOf() method is used to find the last occurrence. The result is then logged to the console.

## Question 8
08. Demonstrate the use of trim() to remove any trailing whitespace at the beginning and the end of a string.
#### Topics
	- trim(), removing white space in a string

#### Code 
``` javascript
let message = "  Hello, welcome to the world of JavaScript  ";
message = message.trim();
console.log(message);
```

#### Output Explained
In this example, the trim() method is used to remove any leading or trailing whitespace from the string stored in the message variable. The trimmed string is then stored back in the message variable, and the result is logged to the console.

## Question 9
09. Boolean value is either true or false.
    - Write three JavaScript statement example which provide truthy value.
    - Write three JavaScript statement example which provide falsy value.
#### Topics
	- truthy and falsy, boolean

#### Code 
``` javascript
//Truthy values:
let name = "Diki Dev"; // any non-empty string is considered truthy in JavaScript.
let count = 32; // any non-zero number is considered truthy in JavaScript.
let isValid = true; // the boolean value true is considered truthy.

//Falsy values:
let name = ""; // an empty string is considered falsy in JavaScript.
let count = 0; // the number 0 is considered falsy in JavaScript.
let isValid = false; // the boolean value false is considered falsy.
```

#### Output Explained
Truthy is non-empty strings, non-zero numbers, boolean true
Falsy is a empty string, the number 0 and boolean false

## Question 10
10. Figure out the result of the following comparison expression first without using console.log(). After you decide the result confirm it using console.log()
    - 4 > 3
    - 4 >= 3
    - 4 < 3
    - 4 <= 3
    - 4 == 4
    - 4 === 4
    - 4 != 4
    - 4 !== 4
    - 4 != '4'
    - 4 == '4'
    - 4 === '4'
    - Find the length of python and jargon and make a falsy comparison statement.

#### Topics
	- truthy and falsy, comparison statement

#### Code 
``` javascript
4 > 3 is true.
4 >= 3 is true.
4 < 3 is false.
4 <= 3 is false.
4 == 4 is true.
4 === 4 is true.
4 != 4 is false.
4 !== 4 is false.
4 != '4' is false.
4 == '4' is true.
4 === '4' is false.
```
And for the length of the words "python" and "jargon", you can write the following comparison:
``` javascript
let word1 = "python";
let word2 = "jargon";

console.log(word1.length !== word2.length);

```

#### Output Explained
	- false

The length of the two words is compared using the !== operator, which returns true if the values are not equal. The result is then logged to the console.


## Question 11
11. Use the Date object to do the following activities
    - What is the year today?
    - What is the month today as a number?
    - What is the date today?
    - What is the day today as a number?
    - What is the hours now?
    - What is the minutes now?
    - Find out the numbers of seconds elapsed from January 1, 1970 to now.

#### Topics 
	- Date()

#### Code
``` javascript
let today = new Date();

console.log("Year: ", today.getFullYear());
console.log("Month: ", today.getMonth() + 1);
console.log("Date: ", today.getDate());
console.log("Day: ", today.getDay());
console.log("Hours: ", today.getHours());
console.log("Minutes: ", today.getMinutes());
console.log("Seconds since January 1, 1970: ", today.getTime() / 1000);

```

#### Output Explained 
This code creates a Date object and stores it in the today variable. The various methods like getFullYear(), getMonth(), getDate(), getDay(), getHours(), and getMinutes() are then used to get the year, month, date, day, hours, and minutes, respectively. The getTime() method returns the number of milliseconds elapsed since January 1, 1970, so it is divided by 1000 to get the number of seconds. The result of each method is logged to the console.

## Question 12
12. Create a human readable time format using the Date time object
    - YYYY-MM-DD HH:mm
    - DD-MM-YYYY HH:mm
    - DD/MM/YYYY HH:mm
#### Topics
	- Date(), getFullYear(), getMonth(), getDate(), getHours(), and getMinutes() methods

#### Code
```javascript
let today = new Date();

let year = today.getFullYear();
let month = today.getMonth() + 1;
let date = today.getDate();
let hours = today.getHours();
let minutes = today.getMinutes();

let formattedDate1 = `${year}-${month < 10 ? "0" + month : month}-${date < 10 ? "0" + date : date} ${hours < 10 ? "0" + hours : hours}:${minutes < 10 ? "0" + minutes : minutes}`;
let formattedDate2 = `${date < 10 ? "0" + date : date}-${month < 10 ? "0" + month : month}-${year} ${hours < 10 ? "0" + hours : hours}:${minutes < 10 ? "0" + minutes : minutes}`;
let formattedDate3 = `${date < 10 ? "0" + date : date}/${month < 10 ? "0" + month : month}/${year} ${hours < 10 ? "0" + hours : hours}:${minutes < 10 ? "0" + minutes : minutes}`;

console.log(formattedDate1);
console.log(formattedDate2);
console.log(formattedDate3);

```
#### Output Explained 
	- In this code, a Date object is created and stored in the today variable. The year, month, date, hours, and minutes are extracted using the getFullYear(), getMonth(), getDate(), getHours(), and getMinutes() methods, respectively. The date and time values are then formatted into strings using string concatenation and the ternary operator (? :). The if condition inside the ternary operator checks if the values are less than 10 and adds a leading 0 if necessary. Finally, the formatted strings are logged to the console. 

## Question 13
13. Get user input using prompt(“Enter your age:”). If user is 18 or older , give feedback:'You are old enough to drive' but if not 18 give another feedback stating to wait for the number of years he needs to turn 18.

#### topics
	- prompt(),parseInt()

#### code
```javascript
let age = prompt("Enter your age:");
age = parseInt(age);

if (age >= 18) {
  console.log("You are old enough to drive");
} else {
  console.log(`You need to wait for ${18 - age} years to turn 18`);
}

```

#### output explained
	- In this code, the prompt() method is used to get the user's age and store it in the age variable. The parseInt() function is used to convert the string value to an integer. The if statement checks if the user's age is greater than or equal to 18, and if so, outputs the message "You are old enough to drive". If the user's age is less than 18, the message "You need to wait for X years to turn 18" is output, where X is the number of years until the user turns 18.

## Question 14
14. Even numbers are divisible by 2 and the remainder is zero. How do you check, if a number is even or not using JavaScript? Create a program which checks that the given number is even or odd.

#### topics 
	- prompt(),  parseInt(), string to integer, 

#### code
```javascript
let number = prompt("Enter a number:");
number = parseInt(number);

if (number % 2 === 0) {
  console.log(`${number} is an even number`);
} else {
  console.log(`${number} is an odd number`);
}
```

#### output explained
In this code, the prompt() method is used to get the number and store it in the number variable. The parseInt() function is used to convert the string value to an integer. The if statement checks if the number is divisible by 2 and has no remainder (number % 2 === 0), and if so, outputs the message "X is an even number", where X is the number. If the number is not divisible by 2 and has a remainder, the message "X is an odd number" is output.

## Question 15
15. Write a program which can give grades to students according to theirs scores:
    - 80-100, A
    - 70-89, B
    - 60-69, C
    - 50-59, D
    - 0-49, F

#### topics
	- prompt(), parseInt(), if, else

#### code
```javascript 
let score = prompt("Enter your score:");
score = parseInt(score);

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
  console.log("Invalid score");
}
```

#### output explained
In this code, the prompt() method is used to get the student's score and store it in the score variable. The parseInt() function is used to convert the string value to an integer. The if statement checks the student's score against the different ranges of scores, and outputs the corresponding grade. If the score is outside of the range 0 to 100, an "Invalid score" message is output.

## Question 16
16. Check if the season is Autumn, Winter, Spring or Summer. If the user input is :
    - September, October or November, the season is Autumn.
    - December, January or February, the season is Winter.
    - March, April or May, the season is Spring
    - June, July or August, the season is Summer

#### topics
	- prompt(), store input in variable, cheack value of variable against others, if, else

#### code
```javascript
let month = prompt("Enter a month (e.g. January, February, etc):");

if (month === "September" || month === "October" || month === "November") {
  console.log("The season is Autumn");
} else if (month === "December" || month === "January" || month === "February") {
  console.log("The season is Winter");
} else if (month === "March" || month === "April" || month === "May") {
  console.log("The season is Spring");
} else if (month === "June" || month === "July" || month === "August") {
  console.log("The season is Summer");
} else {
  console.log("Invalid month");
}
```

#### output explained
The prompt() method is used to get the user's input and store it in the month variable. The if statement checks the value of the month variable against the different months, and outputs the corresponding season. If the input is not a valid month, an "Invalid month" message is output.

## Question 17
17. Write a program which tells the number of days in a month.

#### topics

#### code
```javascript
let month = prompt("Enter a month (e.g. January, February, etc):");
let year = prompt("Enter a year (e.g. 2020, 2021, etc):");
let numOfDays;

switch (month) {
  case "January":
  case "March":
  case "May":
  case "July":
  case "August":
  case "October":
  case "December":
    numOfDays = 31;
    break;
  case "February":
    if ((year % 4 === 0 && year % 100 !== 0) || year % 400 === 0) {
      numOfDays = 29;
    } else {
      numOfDays = 28;
    }
    break;
  case "April":
  case "June":
  case "September":
  case "November":
    numOfDays = 30;
    break;
  default:
    console.log("Invalid month");
    break;
}

if (numOfDays) {
  console.log(`The number of days in ${month} ${year} is ${numOfDays}.`);
}
```

#### output explained
The prompt() method is used to get the user's inputs for the month and year, which are then stored in the month and year variables respectively. A switch statement is used to determine the number of days in the month based on the value of month. If month is equal to "February", a separate check is performed to determine if the year is a leap year. If the year is a leap year, the number of days is 29, otherwise it is 28. If the input is not a valid month, an "Invalid month" message is output.

## Question 18
18. Write a program which tells the number of days in a month, now consider leap year.

#### topics

#### code

#### output explained

## Question 19
19. Create a countries.js file and store the countries name into this file, create a file web_techs.js and store the popular web technology names into this file. Access both file in a third file named main.js

#### topics

#### code

#### output explained

## Question 20
20. In the following shopping cart add, remove, edit items
    => const shoppingCart = ['Milk', 'Coffee', 'Tea', 'Honey']
    - add 'Meat' in the beginning of your shopping cart if it has not been already added
    - add Sugar at the end of your shopping cart if it has not been already added
    - remove 'Honey'
    - modify Tea to 'Green Tea'

#### topics

#### code

#### output explained

## Question 21
21. In countries array check if 'Ethiopia' exists in the array if it exists print 'ETHIOPIA'. If it does not exist add to the countries list.

#### topics

#### code

#### output explained

## Question 22
22. The following is an array of 10 students ages:
    => const ages = [19, 22, 19, 24, 20, 25, 26, 24, 25, 24]
    - Sort the array and find the min and max age
    - Find the median age(one middle item or two middle items divided by two)
    - Find the average age(all items divided by number of items)
    - Find the range of the ages(max minus min)
    - Compare the value of (min - average) and (max - average), use abs() method

#### topics

#### code

#### output explained

## Question 23
23. Write a program to check that the number given by the user is a prime number or not.

#### topics

#### code

#### output explained

## Question 24
24. Write a program to create two array "even" and "odd" having even and odd number between the 0 to 100 (0 and 100 included).

#### topics

#### code

#### output explained

## Question 25
25. Body mass index(BMI) is calculated as follows: bmi = weight in Kg / (height x height) in m2. Write a function which calculates bmi. BMI is used to broadly define different weight groups in adults 20 years old or older.Check if a person is underweight, normal, overweight or obese based the information given below.
    - The same groups apply to both men and women.
    - Underweight: BMI is less than 18.5
    - Normal weight: BMI is 18.5 to 24.9
    - Overweight: BMI is 25 to 29.9
    - Obese: BMI is 30 or more

#### topics

#### code

#### output explained


## Question 26
26. Write a program to print the table of any number given by the user. The format of the output should be smiliar to the below example-
	If the number given by the user is 2 then the output should look like this-
	2 * 1 = 2
	2 * 2 = 4
	2 * 3 = 6 and so on till 2 * 10 = 20.

#### topics

#### code

#### output explained

## Question 27
27. Write a program to print all the prime number between 0 to 100 (0 and 100 included).

#### topics

#### code

#### output explained

## Question 28
28. Write a program to print the given patterns using the loops-
	a. Print a triangle pattern, if the given input is 3 then the pattern should be similar to the given output
	   *
	   **
	   ***
	
	b. Print a square pattern, if the input is 3 then the output should be similar to the given output
	   ***
	   ***
	   ***

	c. Print a pyramid pattern, if the input is 3 then the output should be similar to the given output
	     *
	    ***
 	   *****

#### topics

#### code

#### output explained


## Question 29
29. Write a javascript program which takes the input of filename as string and prints the extension of the file in the console.

#### topics

#### code

#### output explained

## Question 30
30. Create a simple calculator program in JavaScript which can perform the addition, substraction, multiplication and division on given numbers.

#### topics

#### code

#### output explained
















8thJanJavaScript2.0Assg(Homework).txt
Displaying 8thJanJavaScript2.0Assg(Homework).txt.
