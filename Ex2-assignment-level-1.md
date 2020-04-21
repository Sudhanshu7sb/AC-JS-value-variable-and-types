## writeCode

Define 5 values of types number and string and store it in a variable.
var str=["red",144,"blue",23,"white"];


## writeCode

- Declare a variable `user` and take the name using `prompt`. Display the value stored in `user` using `alert`.
var user=prompt("enter your name");
alert(user);
- Now re-assign the value stored in the above example into a new variable `userName`. Log the value of both `user` and `userName` in console using `console.log`.
- Declare `age` and `gender` in the same line as `userName` i.e. declare multiple variables in one line.
- Now change the value of `user` to "John" and log the value of both `user` and `userName`.
var userName=user,age,gender;
console.log(user,userName);
user="John";
console.log(user,userName);

## writeCode

Use `prompt` to take two numbers from user and store it in variable `numA` and `numB`. Create a third variable called `sum`, using `+` operator add numA and numB , store it in varible `sum` and using alert display `sum` in browser.

var numA = Number(prompt("enter a number"));
var numB = Number(prompt("enter a number"));
var sum = numA + numB;
alert(sum);

## writeCode

Define 10 variables and store any kind of value in it. Like name, age etc
var name="sudhanshu";
var num=10;
var decimal=1.11;
var age=25;
var adrress="dharamsala";
var height=5.4;
var weight=63;
var company="AltCampus;
var pincode=769005;
var district="kangra";



## writeTextAnswer

- Declare variables with the name `break`, `class`, `const`, `for`, `else`, `if`, `import` and `return`. Explain in your own words what did you observe.

unexpected token 'break'   : We cannot assign these above names to a variable because javascript have some reserved keywords that do specific tasks .

## writeTextAnswer

- What is a truthy and falsey values.

Truthy values are always true whenever we have to return something in boolean.We can also say the values which are not falsey are truthy.For example: 
if (true)
if ({})
if ([])
if (42)
if ("0")

Falsey values are always returns false when evaluated .Falsey value are false, 0, -0, 0n, "", null, undefined, and NaN. 

## writeTextAnswer

- What are falsey values?

Falsey values are always returns false when evaluated .Falsey value are false, 0, -0, 0n, "", null, undefined, and NaN.

## writeCode

- Declare three variables `name,` `newUser` and `isAdmin`.
var name,newUser,isAdmin;
  - Assign your name as the value of `name`.
  name="Sudhanshu";
  - Reassign the value `newUser` to `name`.
  prompt(newUser=name);
  - Set the value of `isAdmin` to `true`.
  isAdmin=true;
  - Prompt the values of all the three variables.
  alert(name);
  alert(newUser);
  alert(isAdmin);

  //FEEDBACK:'alert' instead of 'prompt'


## writeTextAnswer

What is the error in the given variable declaration:

```js
let user name = "John";//space is not allowed in varible name 
```

## writeQuiz

Q. What does the 'mkdir' command do?

- [x] "Welcome to JavaScript"
- [ ] 'Welcome to JavaScript"
- [ ] "Welcome to JavaScript'
- [ ] 'Welcome to JavaScript'

//create a new directory

## writeTextAnswer

Find out the `valid` and `invalid` variables. In case of `invalid` declarations give reasons. Just below every line.

- let monk; //valid
- let 1stName; //invalid
//variable name should not start with a number
- let places3; //valid
- let -name;  //invalid
//variable name cannot start with '-'
- let bigPanther; //valid
- let 35; //invalid
// variable name cannot start with number.
- let 43 = 30;//invalid
//variable name cannot start with number
- let \$48;//invalid
//  variable name cannot start with \
- var \*gt = 350;//invalid
//  variable name cannot start with \
- let userName; //valid
- let a, b, c; //valid
- let x = 3, y = 11, z = 13;//valid
- let x = 2 + 5 + 7; //valid
- let user = "Brienne of Tarth"; "Sansa Stark"; "Lyanna Mormont";//valid:"Lyanna Mormont is assigned to user

## writeCode

Follow instructions and write code. In case of an error write the error in your own words.

```js
var wiseMan = "Tyrion Lannister";
```

- Reassign the value of `wiseMan` to "Samwell Tarly"
wiseMan="Samwell Tarly";
- Declare a variable `userName` with value "Lysa Arryn"
var username = "Lysa Arryn";
- Declare a variable as `oddNumber` and assign a value `57`.
var oddNumber = 57;
- Reassign the value of `oddNumber` to 61
oddNumber = 61;

## writeCode

Using mathematical operations find the solutions. `(+, -, \*, / , etc.)`

```js
let amount = 4280;
```

- Declare a new variable `reducedAmount` . In it store the value that is 24 less than the value of amount.
var reducedAmount = amount - 24;
- Declare another variable `addedAmount` . Its value should be 32 more than the value of amount.
var addedAmount = amount +32;
- Declare a variable `multipleAmount` . Its value should be 7 times the value of amount.
var multipleAmount = amount * 7 ;
- Declare a variable `dividedAmount` . It should store the resultant of amount divided by 57.
var dividedAmount = amount % 57;

## typeof-writeCode

What will be the output of the following

1. `typeof NaN`  //number

2. `typeof phone` //undefined
3. `typeof null`  //object
4. `typeof undefined` //undefined
5. `typeof "abc"` //string
6. `typeof -0`  //number
7. `typeof 4` //number

## Number Type Conversion-writeCode

Output of the following code

1. `Number("6")` //6
2. `Number("6.76")` //6.76
3. `Number(" 6.76 ")` //6.76
4. `Number(" 6 . 7 6 ")` //NaN
5. `Number(" ")` //0
6. `Number("")` //0
7. `Number("5+6")` //11
8. `Number(true)` //1
9. `Number(false)` //0
10. `Number("text")` //NaN

## String Type Conversion-writeCode

Output of the following code

1. `String(456)` //"456"
2. `String(1.25)` //"1.25"
3. `String(10+20)` //"30"
4. `String(true)` //"true"
5. `String(false)` //"false"
6. `String(NaN)` //"NaN"
7. `String("text")` //"text"
8. `String("This", "is", "text")` //"This"
9. `String["This", "is", "text"]` //undefined
10. `String{"This", "is", "text"}` //uncaugth error { not allowed
11. `String("This"+"is"+"text")` //"Thisistext"

## Boolean Type Conversion-writeCode

Output of the following code

1. `Boolean(1)` //true
2. `Boolean(0)` //false
3. `Boolean(-5)` //true
4. `Boolean(5-5)` //false
5. `Boolean(undefined)` //false
6. `Boolean(null)` //false
7. `Boolean(NaN)` //false
8. `Boolean("text")`  //true
9. `Boolean(" ")` //true
10. `Boolean("")` //false

## Operators-writeCode

Output of the following line of code.

```js
20 > 5 && 5 < 20; //output : true
20 > 5 && 20 < 5; //output :false
NaN && NaN; //output :NaN
NaN && undefined; //output : NaN
undefined && " "; //output : undefined
"" && "Arya"; //output : ""
"Arya" && 5; //output : 5
10 && "Arya"; //output : "Arya"
" " && 10; //output : 10
NaN && undefined; //output : NaN
" " || 10; //output : " "
undefined || " "; //output : " "
10 || "Arya"; //output : 10
"" || "Arya"; //output : "Arya"
!undefined; //output : true
!null; //output : true
!20; //output : false
!0; //output : true
!NaN; //output : true
```

## writeQuiz

What is the value of x?

```js
var a = 5,
  b = 10,
  c = "5";
var x = a + "5";
```

- [ ] 5
- [ ] 10
- [ ] 15
- [x] 55 //output

## Condition-writeCode

Write a program that asks the user his/her age and check for the following conditions :

- `if` the age is between 12-55 then print the message "You can participate in the marathon".
- `if` the age is between 4-11 then print the message " You are too young to participate in the marathon".
- `if` the age is less than 4 then print the message " Hey Kiddo! Can You Walk ?"
- `if` the age is greater than 55 then print the message " You are too old to participate in the marthon".

var age = prompt("enter age");
if(age >=12 && age <=55){
  console.log("You can participate in the marathon");
}
if( age >=4 && age <= 11){
  console.log(" You are too young to participate in the marathon");
}
if(age <4){
  console.log(" Hey Kiddo! Can You Walk ?");
}
if( age > 55){
  console.log(" You are too old to participate in the marthon");
}

## writeCode

Write a program that asks the user for the house name and check the following conditions :

- `if` house name is "stark" then print the message " Winter is coming"
- `if` house name is "lannister" then print the message " A lannister always pays his debt"
- `else` print the message " All men must die"

var housename = prompt("enter house name");
if(housename == "stark"){
  console.log(" Winter is coming");
}
if(housename == "lannister"){
  console.log(" A lannister always pays his debt");
} else {
  " All men must die"

}


## writeCode

Write a program that asks the user for a number and check the following conditions :

- `if` the number is even print the message " number is even"
- `if` the number is odd print the message "number is odd"


var number = prompt("enter number");
if( number % 2 == 0){
  console.log(" number is even");
}
if ( number % 2 == 1){
  console.log( "number is odd");
}

### Convert the above code using `?` terniary operator
var number = prompt( " enter a number");
( number %2 == 0 )? "number is even":"number is odd ";

//FEEDBACK:convert all  3 questions in ternary or just the above code???

## writeCode

1. Print the odd numbers from 9 through 1(both inclusive) using a for loop. There is no input involved.

for(let i = 9; i > 0; i-=2){
      console.log(i);
}



2. Add numbers from 5 through 0(both inclusive) in descending order using a while loop. There is no input involved.

let i = 5;
let sum = 0;
while (i >= 0) {
  console.log(sum = sum + i);
  i--;
}




3. Program to calculate the sum of first n natural numbers(1,2,3...n are known as natural numbers). Prompt user to enter n(using prompt modal window) then based on input provided calculate and show result in alert modal window.


var n = prompt("enter a number");
let sum =0;
for ( let i = 0; i <= n; i++){
  
  sum = sum +i;
  console.log(sum);
}


4. Write a program to print from 1 to 10 but quit if multiple of 7 is encountered. There is no input involved.

for (let i = 1; i <=10; i++) {
  if(i % 7 == 0){
    break;
  }
  console.log(i);
}

## writeCode

Complete the following code to make the output be 0 2 4 6 8 10?

```js
for (let j = 0; j <= 10; j+=2){
   console.log(j);//j+=2 answer
}
```
