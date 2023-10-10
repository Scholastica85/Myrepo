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

```const sampleStr = "Alan said, \"Alan said, \"Peter is learning JavaScript\".";```

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

## Day Nine 
**Concatenating Strings with Plus Operator** 
- In JavaScript, when the + operator is used with a String value, it is called the concatenation operator. You can build a new string out of other strings by concatenating them together.

```Example

'My name is Alan,' + ' I concatenate.'
```
- We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.
```Example:
let ourStr = "I come first. ";
ourStr += "I come second.";
```
**Constructing Strings with Variables**
- Sometimes you will need to build a string. By using the concatenation operator (+), you can insert one or more variables into a string you're building.

```Example:
const ourName = "freeCodeCamp";
const ourStr = "Hello, our name is " + ourName + ", how are you?";
```
**Appending Variables to Strings**
- Just as we can build a string over multiple lines out of string literals, we can also append variables to a string using the plus equals (+=) operator.

```Example:
const anAdjective = "awesome!";
let ourStr = "freeCodeCamp is ";
ourStr += anAdjective;
```
## Day Ten 
**Find the Length of a String**
- You can find the length of a String value by writing .length after the string variable or string literal.
```console.log("Alan Peter".length);```
- The value 10 would be displayed in the console. Note that the space character between "Alan" and "Peter" is also counted.
- For example, if we created a variable const firstName = "Ada", we could find out how long the string Ada is by using the firstName.length property.

**Use Bracket Notation to Find the First Character in a String**

- Bracket notation is a way to get a character at a specific index within a string.

- Most modern programming languages, like JavaScript, don't start counting at 1 like humans do. They start at 0. This is referred to as Zero-based indexing.

- For example, the character at index 0 in the word Charles is C. So if const firstName = "Charles", you can get the value of the first letter of the string by using firstName[0].

```Example:
const firstName = "Charles";
const firstLetter = firstName[0];
firstLetter would have a value of the string C.
```
**Understand String Immutability**
- In JavaScript, String values are immutable, which means that they cannot be altered once created.
-For example, the following code will produce an error because the letter B in the string Bob cannot be changed to the letter J:
```let myStr = "Bob";
myStr[0] = "J";
Note that this does not mean that myStr could not be re-assigned. The only way to change myStr would be to assign it with a new value, like this:
let myStr = "Bob";
myStr = "Job";
```
**Use Bracket Notation to Find the Last Character in a String**
-In order to get the last letter of a string, you can subtract one from the string's length.
-For example, if const firstName = "Ada", you can get the value of the last letter of the string by using firstName[firstName.length - 1].

```Example:
const firstName = "Ada";
const lastLetter = firstName[firstName.length - 1];
lastLetter would have a value of the string a.
```
**Use Bracket Notation to Find the Nth-to-Last Character in a String**
- You can use the same principle we just used to retrieve the last character in a string to retrieve the Nth-to-last character.
- For example, you can get the value of the third-to-last letter of the const firstName = "Augusta" string by using firstName[firstName.length - 3]

```Example:
const firstName = "Augusta";
const thirdToLastLetter = firstName[firstName.length - 3];
thirdToLastLetter would have a value of the string s.
```
