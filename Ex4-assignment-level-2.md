## Example readCode

```js
let age = 21;
if (age > 18) {
  alert("You are an adult.");
}
```

```js
let age = 21;
age > 18 && alert("You are an adult.");
```

- Above two code examples are equivalent. You can use `&&` on the place of `if` statement.
- `&&` looks for first `falsey` value so `alert` will only execute if the fist expression is a truthy statement.

## writeCode

Logical operations with variables. Solve the following examples using logical operations. `(<, >, &&, ||)`.

```js
var vegetablesPrice = 54;
var cerealsPrice = 149;
```

- Find which one is costlier?
- Which item is cheaper?
- Check if the prices of both the items are equal.
- Define a new variable. Assign the price of vegetables to it.
- Calculate the average price of these two commodities.

## writeTextAnswer
vegetablesPrice && cerealsPrice;
vegetablesPrice || cerealsPrice;
vegetablesPrice == cerealsPrice;
var veggies =vegetablePrice;
var avg = (vegetablesPrice + cerealsPrice) / 2  ; 

What are the different types of type conversions. Explain in your own words with few examples.

## writeQuiz

There are two types of conversions namely implicit type conversion and explicit type conversion.



Implicit type conversions means the system or browser automatically converts the value type (or data type) from one to another type.For example: 
    true + true; // 2 (boolean to number)
      Here the system automatically changes true value to 1 resulting to 2.
    1 + "2" + 21; // "1221" (number to string)
      Here the system automatically changes 1 and 21 to string "1" and "21" resulting to "1221"
    


Explicit type conversions means the user deliberately changes the value type (or data type) from one to another to get desired output.For example:
    Number(true); // 1 (boolean to number)
      Here we want a number output,so Number prior to true does the work for us forcibly.
    Number("1"); // 1 (string to number)
      Here it forcibly changes the value type (or data type) to number giving us 1 as number value type.
    


Q. What will be the output of the following code.

```js
var num = 1011;
if (num === 1011) {
  var num = 205;
  console.log(num);
}
```

- [ ] 1011
- [ ] 1000
- [ ] `error`
- [x] 205

## writeTextAnswer

`3 + '4'` in this code first value `3` is a Number data type and `'4'` is a String. Because both values are not same `implicit type conversion` will happen to bring both the value in the same data type. So `string` will be converted to `number` because of preference of number. `Number('4')` is equal to `4`. Now `3` and `4` is number and result is `7`.

Similarly write explaining how this conversion will happen. And what will be the output.

1. `3 * "3"`

`3 + "3"` in this code first value `3` is a Number data type and `"3"` is a String. Because both values are not same `implicit type conversion` will happen to bring both the value in the same data type. So `string` will be converted to `number` because of preference of number. `Number('3')` is equal to `3`. Now `3` and `3` is number and result is `9`.

2. `1 + "2" + 1`

`1 + "2" +1` in this code first value `1` is a Number data type, `"2"` is a String and last '1' is a Number data type. Because all values are not same `implicit type conversion` will happen to bring all the value in the same data type. So `string` will be converted to `number` because of preference of number. `Number('2')` is equal to `2`. Now `1` , '2' and `1` is number and result is `4`.

## writeCode

What's the output of the following, write the output next to the code as comment

1. 5 \* "5" =  ? //output :
2. 6 + "7" = ? //output :67
3. 1 + "JS" = ? //output : 1JS
4. 1 \* "JS" = ? //output :
5. 5 + true = ? //output :6
6. 6 - true = ? //output :5
7. 7 - false = ? //output :7
8. 8 + false = ? //output :8
9. true + true = ? //output :2
10. true + false = ? //output :1

## writeCode

Output of each line of code :

- `3 * '8'`
- 1 + '21' + 32
- "string" ? 4 : 1
- undefined ? 4 : 1
- 4 \* Number("")
- 4 \* 0
- 4 / '2'
- 4 + true
- 3 \* false
- 3 \* ""
- 3 + ""

## Operators-writeCode

Output of the following line of code.

```js
"NaN" && "undefined" && 0; // output :0
"AT" && "" && false; // output : ""
"AT" && " " && false; // output : false
"AT" || 5; // output : "AT"
" " || "AT" || false; // output :" "
!{}; //output :false
!""; //output : true
!"OK"; //output : false
!false; //output : true
!true; //output : false
```

## == and === writeTextAnswer

What is the difference between double equal and tripal equal comparision operator. Explain with example.

double equal operator(==) allows implicit conversions but triple equal (===) operator doesn't.
var a=5,b="5";
a == b; //true
a===b; //false

## Double and Tripal equal-writeCode

```js
var a = 5,
  b = 10,
  c = "5";
var x = a;
```

What will be the output of the code below on the basis of above code.

```js
a == c; // output :true
a === c; // output : false
a == x; // output : true
a != b; // output :true
a > b; // output :false
a < b; // output :true
a >= b; // output :false
a <= b; // output :true
a >= c; // output :true
a <= c; // output :true
```

```js
var a = 5,
  b = 10;
```

What will be the output of the code below on the basis of above code.

```js
a != b && a < b; //output :true
a > b || a == b; //output :false
a < b || a == b; //output true
!(a < b); //output :false
!(a > b); //output :true
```

## writeTextAnswer

What is the difference between `if` statement and ternary operator. Explain with example.

ternary operator'?' is a expresson whereas if is a statement.
ternary is faster as compared to if.
For example:
Ternary :
(condition)? value1: value2;
Here condition is true then value1 is evaluated else value2 is evaluated.

IF:
if(conditon){
  true block;
}else {
  false block;
}
Here the conditon is checked if it is true, true block is executed else false block.

## writeCode

Take two value using prompt and store them in variables `num1` and `num2`. Check whether they are equal or not.

- if the input value is anything like `true`, `null` or `undefined` alert saying `Enter a valid value`.

Example:

```js
21, 21; // true
21, "21"; // true
"21", "21"; // true
"hello", -21; // false
```
var num1 = prompt("enter any value1");
var num2  = prompt("enter any value2");
if(num1 == num2){
  console.log("they are equal");
}else if(( num == true) || (num == null) || (num == undefined)){
  alert('enter a valid value');
}else {
  alert("they are not equal");
}

## writeCode

Given a positive integer `n`. Print one word in format of heeeello(letter 'e' must be repeated `n` times). Take input from prompt and print the result in alert.

Example:

```
for n = 1
result should be hello.
for n = 7,
result should be heeeeeeello (e repeated 7 times).
```
var str=prompt("enter a string");
var n=Number(prompt("enter n"));
var end=str.slice(2);
var rpt=str[1].repeat(n);
alert(str[0] + rpt +end);

## writeTextAnswer

```js
true == 0; // output : false
true == 1; // output : true
true == 2; // output : false 
true == 3; // output : false
true == 100; // output : false
true == 1000; // output : false
```
