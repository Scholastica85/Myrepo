# My 90 Days of Learning JavaScript 

## Day One
*Will Update note later* 

## Day Two
*Will Update note later* 

## Day Three
*Will Update note later* 

## Day Four
**Agenda - JavaScript syntax, including whitespace, statements, identifiers, comments, expressions, and keywords**

## Day Five
*Will Update note later*

## Day Six
**More on Variable**
- In JavaScript, you can store a value in a variable with the assignment operator (=).

```myVariable = 5;```

- After a value is assigned to a variable using the assignment operator, you can assign the value of that variable to another variable using the assignment operator.
  
```var myVar;
myVar = 5;
var myNum;
myNum = myVar;
```

**Understanding Case Sensitivity in Variables**

- In JavaScript all variables and function names are case sensitive. This means that capitalization matters.
- MYVAR is not the same as MyVar nor myvar. It is possible to have multiple distinct variables with the same name but different casing. It is strongly recommended that for the sake of clarity, you do not use this language feature.

**Best Practice**

- Write variable names in JavaScript in camelCase. Example ```var someVariable;```

**Number operations**
- + sign for addition
- (-) sign for substraction
- (*) sign for multiplication
- (/) sign for division

**Increment a Number with JavaScript**
- You can easily increment or add one to a variable with the ++ operator.
Example
```i++;```
is the equivalent of
```i = i + 1;```
**Decrement a Number with JavaScript**
- You can easily decrement or decrease a variable by one with the -- operator.
Example
i--;
is the equivalent of

i = i - 1;
Note: The entire line becomes i--;, eliminating the need for the equal sign.

## Day Seven
**More on Variable**
- We can store decimal numbers in variables too. Decimal numbers are sometimes referred to as floating point numbers or floats.
- Note: when you compute numbers, they are computed with finite precision. Operations using floating points may lead to different results than the desired outcome. one can also perform calculations like addition, substration and multiplication with decimal numbers, just like whole numbers.
- In programming, it is common to use assignments to modify the contents of a variable. Remember that everything to the right of the equals sign is evaluated first, so we can say:

```myVar = myVar + 5;```

- Though there are operators which do both a mathematical operation and assignment in one step.

- One such operator is the += operator.
  
```let myVar = 1;
myVar += 5;
console.log(myVar);
6 would be displayed in the console.
```

 - Like the += operator, -= subtracts, /= division and *= multiplication  of a  number from a variable.

```myVar -= 5; //will substract a myVar by 5. 

myVar *= 5; //will multiply myVar by 5.

myVar /= 5; //Will divide myVar by 5.
```

## Day Eight 
**Escaping Literal Quotes in Strings** 
- When you are defining a string you must start and end with a single or double quote. What happens when you need a literal quote: " or ' inside of your string?

- In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.

- Example

```const sampleStr = "Alan said, \"Alan said, \"Peter is learning JavaScript\".";
```

**Escape Sequences in Strings**
- Quotes are not the only characters that can be escaped inside a string. Escape sequences allow you to use characters you may not otherwise be able to use in a string.

```Code	Output
\'	single quote
\"	double quote
\\	backslash
\n	newline
\t	tab
\r	carriage return
\b	backspace
\f	form feed
```

