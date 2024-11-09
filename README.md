# PHP-Tutorial

- PHP is a server scripting language, and a powerful tool for making dynamic and interactive Web pages.

- PHP is a widely-used, free, and efficient alternative to competitors such as Microsoft's ASP.

## Example PHP Script:

```php
<!DOCTYPE html>
<html>
<body>
 
<?php
echo "My first PHP script!";
?>

</body>
</html>

```
## Example
## PHP Introduction

#  What You Should Already Know
Before you continue you should have a basic understanding of the following:

- HTML
- CSS
- JavaScript

## What is PHP?
- PHP is an acronym for "PHP: Hypertext Preprocessor"
- PHP is a widely-used, open source scripting language
- PHP scripts are executed on the server
- PHP is free to download and use

## PHP is an amazing and popular language!

- It is powerful enough to be at the core of the biggest blogging system on the web (WordPress)!
- It is deep enough to run large social networks!
- It is also easy enough to be a beginner's first server side language!

## What is a PHP File?
- PHP files can contain text, HTML, CSS, JavaScript, and PHP code
- PHP code is executed on the server, and the result is returned to the browser as plain HTML
- PHP files have extension ".php"

## What Can PHP Do?
- PHP can generate dynamic page content
- PHP can create, open, read, write, delete, and close files on the server
- PHP can collect form data
- PHP can send and receive cookies
- PHP can add, delete, modify data in your database
- PHP can be used to control user-access
- PHP can encrypt data
  
With PHP you are not limited to output HTML. You can output images or PDF files. You can also output any text, such as XHTML and XML.

## Why PHP?
- PHP runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.)
- PHP is compatible with almost all servers used today (Apache, IIS, etc.)
- PHP supports a wide range of databases
- PHP is free. Download it from the official PHP resource: www.php.net
- PHP is easy to learn and runs efficiently on the server side

## What's new in PHP 7
- PHP 7 is much faster than the previous popular stable release (PHP 5.6)
- PHP 7 has improved Error Handling
- PHP 7 supports stricter Type Declarations for function arguments
- PHP 7 supports new operators (like the spaceship operator: <=>)

## PHP Syntax
- A PHP script is executed on the server, and the plain HTML result is sent back to the browser.

## Basic PHP Syntax
- A PHP script can be placed anywhere in the document.
- A PHP script starts with ```<?php and ends with ?>:```
  
```php
<!DOCTYPE html>
<html>
<body>
 
  <?php
// PHP code goes here
?>
</body>
</html>
```

- The default file extension for PHP files is ".php".

- A PHP file normally contains HTML tags, and some PHP scripting code.

Below, we have an example of a simple PHP file, with a PHP script that uses a built-in PHP function "echo" to output the text "Hello World!" on a web page:

## Example
- A simple .php file with both HTML code and PHP code:

 
```php
 <!DOCTYPE html>
<html>
<body>

<h1>My first PHP page</h1>

<?php
echo "Hello World!";
?>

</body>
</html>
```
- Note: PHP statements end with a semicolon (;).

## PHP Case Sensitivity
- In PHP, keywords (e.g. if, else, while, echo, etc.), classes, functions, and user-defined functions are not case-sensitive.
- In the example below, all three echo statements below are equal and legal:

## Example
- ECHO is the same as echo:
```php
<!DOCTYPE html>
<html>
<body>

<?php
ECHO "Hello World!<br>";
echo "Hello World!<br>";
EcHo "Hello World!<br>";
?>

</body>
</html>
```
- Note: However; all variable names are case-sensitive!
  
- Look at the example below; only the first statement will display the value of the $color variable! This is because $color, $COLOR, and $coLOR are treated as three different variables:

## Example
- $COLOR is not same as $color:

```php
  <!DOCTYPE html>
<html>
<body>

<?php
$color = "red";
echo "My car is " . $color . "<br>";
echo "My house is " . $COLOR . "<br>";
echo "My boat is " . $coLOR . "<br>";
?>

</body>
</html>
```

## PHP Comments
- A comment in PHP code is a line that is not executed as a part of the program. Its only purpose is to be read by someone who is looking at the code.

- Comments can be used to:

- Let others understand your code
- Remind yourself of what you did - Most programmers have experienced coming back to their own work a year or two later and having to re-figure out what they did. Comments 
  can remind you of what you were thinking when you wrote the code
- Leave out some parts of your code
  
PHP supports several ways of commenting:

## Example
- Syntax for comments in PHP code:

```php
// This is a single-line comment

#This is also a single-line comment

/* This is a
multi-line comment */
```
## Single Line Comments
- Single line comments start with //.

- Any text between // and the end of the line will be ignored (will not be executed).

- You can also use # for single line comments, but in this tutorial we will use //.

- The following examples uses a single-line comment as an explanation:

 ## Example
-- A comment before the code:

// Outputs a welcome message:

```php
echo "Welcome Home!";
```
## Example
-- A comment at the end of a line:

```php
echo "Welcome Home!"; // Outputs a welcome message
```

## Comments to Ignore Code
-- We can use comments to prevent code lines from being executed:

## Example
-- Do not display a welcome message:

// echo "Welcome Home!";

## PHP Multiline Comments

- Multi-line Comments
- Multi-line comments start with /* and end with */.

- Any text between /* and */ will be ignored.

- The following example uses a multi-line comment as an explanation:

## Example
- The  + 15 part will be ignored in the calculation:

```php
<!DOCTYPE html>
<html>
<body>
$x = 5 /* + 15 */ + 5;
echo $x;
<html>
<body>
```
## PHP Variables

- Variables are "containers" for storing information.

- Creating (Declaring) PHP Variables
- In PHP, a variable starts with the $ sign, followed by the name of the variable:

## Example
```php
<!DOCTYPE html>
<html>
<body>
$x = 5;
$y = "John"
<html>
<body>
```

In the example above, the variable $x will hold the value 5, and the variable $y will hold the value "John".

- Note: When you assign a text value to a variable, put quotes around the value.

- Note: Unlike other programming languages, PHP has no command for declaring a variable. It is created the moment you first assign a value to it.

## PHP Variables
- A variable can have a short name (like $x and $y) or a more descriptive name ($age, $carname, $total_volume).

*Rules for PHP variables:*

- A variable starts with the $ sign, followed by the name of the variable
- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive ($age and $AGE are two different variables)

## Remember that PHP variable names are case-sensitive! ##

## Output Variables
- The PHP echo statement is often used to output data to the screen.

- The following example will show how to output text and a variable:

## Example
```php
$txt = "W3Schools.com";
echo "I love $txt!";
```
- The following example will produce the same output as the example above:

## Example
```php
$txt = "W3Schools.com";
echo "I love " . $txt . "!";
```

- The following example will output the sum of two variables:

## Example

```php
$x = 5;
$y = 4;
echo $x + $y;
```
- ***Note: You will learn more about the echo statement and how to output data to the screen in the PHP Echo/Print chapter.***

## PHP is a Loosely Typed Language
- In the example above, notice that we did not have to tell PHP which data type the variable is.

- PHP automatically associates a data type to the variable, depending on its value. Since the data types are not set in a strict sense, you can do things like adding a 
  string to an integer without causing an error.

- In PHP 7, type declarations were added. This gives an option to specify the data type expected when declaring a function, and by enabling the strict requirement, it will 
  throw a "Fatal Error" on a type mismatch.

- You will learn more about strict and non-strict requirements, and data type declarations in the PHP Functions chapter.

Variable Types
PHP has no command for declaring a variable, and the data type depends on the value of the variable.

## Example
```php
$x = 5;      // $x is an integer
$y = "John"; // $y is a string
echo $x;
echo $y;
```
## PHP supports the following data types:

- String
- Integer
- Float (floating point numbers - also called double)
- Boolean
- Array
- Object
- NULL
- Resource

## Get the Type
- To get the data type of a variable, use the var_dump() function.

## Example
- The var_dump() function returns the data type and the value:

```php
$x = 5;
var_dump($x);
```
## Example
- See what var_dump() returns for other data types:
```php
var_dump(5);
var_dump("John");
var_dump(3.14);
var_dump(true);
var_dump([2, 3, 56]);
var_dump(NULL);
```
## Assign String to a Variable
- Assigning a string to a variable is done with the variable name followed by an equal sign and the string:
## Example
```php
$x = "John";
echo $x;
```
- String variables can be declared either by using double or single quotes, but you should be aware of the differences. Learn more about the differences in the PHP Strings 
  chapter.

## Assign Multiple Values
- You can assign the same value to multiple variables in one line:
## Example
- All three variables get the value "Fruit":
```php
$x = $y = $z = "Fruit";
```
## PHP Variables Scope

- In PHP, variables can be declared anywhere in the script.

- The scope of a variable is the part of the script where the variable can be referenced/used.

- PHP has three different variable scopes:

  - local
  - global
  - static
  - Global and Local Scope
- A variable declared outside a function has a GLOBAL SCOPE and can only be accessed outside a function:

## Example
- Variable with global scope:
```php
$x = 5; // global scope

function myTest() {
  // using x inside this function will generate an error
  echo "<p>Variable x inside function is: $x</p>";
}
myTest();

echo "<p>Variable x outside function is: $x</p>";
```
***A variable declared within a function has a LOCAL SCOPE and can only be accessed within that function:***
## Example
- Variable with local scope:
```php
function myTest() {
  $x = 5; // local scope
  echo "<p>Variable x inside function is: $x</p>";
}
myTest();

// using x outside the function will generate an error
echo "<p>Variable x outside function is: $x</p>";
```
## PHP The global Keyword
- The global keyword is used to access a global variable from within a function.

- To do this, use the global keyword before the variables (inside the function):

## Example
```php
$x = 5;
$y = 10;

function myTest() {
  global $x, $y;
  $y = $x + $y;
}

myTest();
echo $y; // outputs 15
```
- PHP also stores all global variables in an array called $GLOBALS[index]. The index holds the name of the variable. This array is also accessible from within functions and 
  can be used to update global variables directly.

***The example above can be rewritten like this:***

## Example
```php
$x = 5;
$y = 10;

function myTest() {
  $GLOBALS['y'] = $GLOBALS['x'] + $GLOBALS['y'];
}

myTest();
echo $y; // outputs 15
```
## PHP The static Keyword
- Normally, when a function is completed/executed, all of its variables are deleted. However, sometimes we want a local variable NOT to be deleted. We need it for a further 
  job.

- To do this, use the static keyword when you first declare the variable:
## Example
```php
function myTest() {
  static $x = 0;
  echo $x;
  $x++;
}

myTest();
myTest();
myTest();
```
- Then, each time the function is called, that variable will still have the information it contained from the last time the function was called.

***Note: The variable is still local to the function.***

## PHP echo and print Statements

- With PHP, there are two basic ways to get output: echo and print.

- In this tutorial we use echo or print in almost every example. So, this chapter contains a little more info about those two output statements.

## PHP echo and print Statements
- echo and print are more or less the same. They are both used to output data to the screen.

-The differences are small: echo has no return value while print has a return value of 1 so it can be used in expressions. echo can take multiple parameters (although such 
 usage is rare) while print can take one argument. echo is marginally faster than print.

## The PHP echo Statement
- The echo statement can be used with or without parentheses: echo or echo().
## Example
```php
echo "Hello";
//same as:
echo("Hello");
```
## Display Text
- The following example shows how to output text with the echo command (notice that the text can contain HTML markup):
## Example
```php
echo "<h2>PHP is Fun!</h2>";
echo "Hello world!<br>";
echo "I'm about to learn PHP!<br>";
echo "This ", "string ", "was ", "made ", "with multiple parameters.";
```
## Display Variables
- The following example shows how to output text and variables with the echo statement:
## Example
```php
$txt1 = "Learn PHP";
$txt2 = "W3Schools.com";

echo "<h2>$txt1</h2>";
echo "<p>Study PHP at $txt2</p>";
```
## Using Single Quotes
- Strings are surrounded by quotes, but there is a difference between single and double quotes in PHP.

- When using double quotes, variables can be inserted to the string as in the example above.

- When using single quotes, variables have to be inserted using the . operator, like this:

## Example
```php
$txt1 = "Learn PHP";
$txt2 = "W3Schools.com";

echo '<h2>' . $txt1 . '</h2>';
echo '<p>Study PHP at ' . $txt2 . '</p>';
```
## The PHP print Statement
- The print statement can be used with or without parentheses: print or print().
## Example
```php
print "Hello";
//same as:
print("Hello");
```
## Display Text
- The following example shows how to output text with the print command (notice that the text can contain HTML markup):

## Example
```php
print "<h2>PHP is Fun!</h2>";
print "Hello world!<br>";
print "I'm about to learn PHP!";
```
## Display Variables
- The following example shows how to output text and variables with the print statement:
## Example
```php
$txt1 = "Learn PHP";
$txt2 = "W3Schools.com";

print "<h2>" . $txt1 . "</h2>";
print "<p>Study PHP at " . $txt2 . "</p>";
```
## Using Single Quotes
- Strings are surrounded by quotes, but there is a difference between single and double quotes in PHP.

- When using double quotes, variables can be inserted to the string as in the example above.

- When using single quotes, variables have to be inserted using the . operator, like this:

## Example
```php
$txt1 = "Learn PHP";
$txt2 = "W3Schools.com";

print '<h2>' . $txt1 . '</h2>';
print '<p>Study PHP at ' . $txt2 . '</p>';
```
## PHP Data Types
- Variables can store data of different types, and different data types can do different things.
- PHP supports the following data types:
  - String
  - Integer
  - Float (floating point numbers - also called double)
  - Boolean
  - Array
  - Object
  - NULL
  - Resource
   
 ## Getting the Data Type
- You can get the data type of any object by using the var_dump() function.
## Example
- The var_dump() function returns the data type and the value:
```php
$x = 5;
var_dump($x);
```
## PHP String
- A string is a sequence of characters, like "Hello world!".

- A string can be any text inside quotes. You can use single or double quotes:
## Example
```php
$x = "Hello world!";
$y = 'Hello world!';

var_dump($x);
echo "<br>";
var_dump($y);
```
## PHP Integer
- An integer data type is a non-decimal number between -2,147,483,648 and 2,147,483,647.

- Rules for integers:
  - An integer must have at least one digit
  - An integer must not have a decimal point
  - An integer can be either positive or negative
  - Integers can be specified in: decimal (base 10), hexadecimal (base 16), octal (base 8), or binary (base 2) notation
- In the following example $x is an integer. The PHP var_dump() function returns the data type and value:
## Example
```php
$x = 5985;
var_dump($x);
```
## PHP Float
- A float (floating point number) is a number with a decimal point or a number in exponential form.

- In the following example $x is a float. The PHP var_dump() function returns the data type and value:
## Example
```php
$x = 10.365;
var_dump($x);
```
## PHP Boolean
- A Boolean represents two possible states: TRUE or FALSE.
## Example
```php
$x = true;
var_dump($x);
```
- Booleans are often used in conditional testing.

- You will learn more about conditional testing in the PHP If...Else chapter.
## PHP Array
- An array stores multiple values in one single variable.

- In the following example $cars is an array. The PHP var_dump() function returns the data type and value:
## Example
```php
$cars = array("Volvo","BMW","Toyota");
var_dump($cars);
```
- You will learn a lot more about arrays in later chapters of this tutorial.
## PHP Object
- Classes and objects are the two main aspects of object-oriented programming.
- A class is a template for objects, and an object is an instance of a class.
- When the individual objects are created, they inherit all the properties and behaviors from the class, but each object will have different values for the properties.
- Let's assume we have a class named Car that can have properties like model, color, etc. We can define variables like $model, $color, and so on, to hold the values of 
  these properties.
- When the individual objects (Volvo, BMW, Toyota, etc.) are created, they inherit all the properties and behaviors from the class, but each object will have different 
  values for the properties.
- If you create a __construct() function, PHP will automatically call this function when you create an object from a class.
## Example
```php
class Car {
  public $color;
  public $model;
  public function __construct($color, $model) {
    $this->color = $color;
    $this->model = $model;
  }
  public function message() {
    return "My car is a " . $this->color . " " . $this->model . "!";
  }
}

$myCar = new Car("red", "Volvo");
var_dump($myCar);
```
- Do not worry if you do not understand the PHP Object syntax, you will learn more about that in the PHP Classes/Objects chapter.
## PHP NULL Value
- Null is a special data type which can have only one value: NULL.
- A variable of data type NULL is a variable that has no value assigned to it.
- Tip: If a variable is created without a value, it is automatically assigned a value of NULL.
- Variables can also be emptied by setting the value to NULL:
## Example
```php
$x = "Hello world!";
$x = null;
var_dump($x);
```
## Change Data Type
- If you assign an integer value to a variable, the type will automatically be an integer.
- If you assign a string to the same variable, the type will change to a string:
## Example
```php
$x = 5;
var_dump($x);

$x = "Hello";
var_dump($x);
```
- If you want to change the data type of an existing variable, but not by changing the value, you can use casting.

- Casting allows you to change data type on variables:
## Example
```php
$x = 5;
$x = (string) $x;
var_dump($x);
```
- You will learn more about casting in the PHP Casting Chapter.
## PHP Resource
- The special resource type is not an actual data type. It is the storing of a reference to functions and resources external to PHP.
- A common example of using the resource data type is a database call.
- We will not talk about the resource type here, since it is an advanced topic.
## PHP Strings
- A string is a sequence of characters, like "Hello world!".
## Strings
- Strings in PHP are surrounded by either double quotation marks, or single quotation marks.
## Example
```php
echo "Hello";
echo 'Hello';
```
## Double or Single Quotes?
- You can use double or single quotes, but you should be aware of the differences between the two.
- Double quoted strings perform action on special characters
- E.g. when there is a variable in the string, it returns the value of the variable:
## Example
- Double quoted string literals perform operations for special characters:
```php
$x = "John";
echo "Hello $x";
```
- Single quoted strings does not perform such actions, it returns the string like it was written, with the variable name:
## Example
- Single quoted string literals returns the string as it is:
```php
$x = "John";
echo 'Hello $x';
```
## String Length
- The PHP strlen() function returns the length of a string.
## Example
- Return the length of the string "Hello world!":
```php
echo strlen("Hello world!");
```
## Word Count
- The PHP str_word_count() function counts the number of words in a string.
## Example
- Count the number of word in the string "Hello world!":
```php
echo str_word_count("Hello world!");
```
## Search For Text Within a String
- The PHP strpos() function searches for a specific text within a string.
- If a match is found, the function returns the character position of the first match. If no match is found, it will return FALSE.
## Example
- Search for the text "world" in the string "Hello world!":
```php
echo strpos("Hello world!", "world");
```
- Tip: The first character position in a string is 0 (not 1).
## Complete PHP String Reference
- For a complete reference of all string functions, go to our complete PHP String Reference.
- The PHP string reference contains description and example of use, for each function!
## PHP - Modify Strings
- PHP has a set of built-in functions that you can use to modify strings.
## Upper Case
## Example
- The strtoupper() function returns the string in upper case:
```php
$x = "Hello World!";
echo strtoupper($x);
```
## Lower Case
## Example
- The strtolower() function returns the string in lower case:
```php
$x = "Hello World!";
echo strtolower($x);
```
## Replace String
- The PHP str_replace() function replaces some characters with some other characters in a string.
## Example
- Replace the text "World" with "Dolly":
```php
$x = "Hello World!";
echo str_replace("World", "Dolly", $x)
```
## Reverse a String
- The PHP strrev() function reverses a string.
## Example
- Reverse the string "Hello World!":
```php
$x = "Hello World!";
echo strrev($x);
```
## Remove Whitespace
- Whitespace is the space before and/or after the actual text, and very often you want to remove this space.
## Example
- The trim() removes any whitespace from the beginning or the end:
```php
$x = " Hello World! ";
echo trim($x);
```
## Convert String into Array
- The PHP explode() function splits a string into an array.

- The first parameter of the explode() function represents the "separator". The "separator" specifies where to split the string.
## Note: The separator is required.
## Example
- Split the string into an array. Use the space character as separator:
```php
$x = "Hello World!";
$y = explode(" ", $x);

//Use the print_r() function to display the result:
print_r($y);

/*
Result:
Array ( [0] => Hello [1] => World! )
*/
```
## Complete PHP String Reference
- For a complete reference of all string functions, go to our complete PHP String Reference.
## PHP - Slicing Strings
## Slicing
- You can return a range of characters by using the substr() function.
- Specify the start index and the number of characters you want to return.
## Example
- Start the slice at index 6 and end the slice 5 positions later:
```php
$x = "Hello World!";
echo substr($x, 6, 5);
```
## Slice to the End
- By leaving out the length parameter, the range will go to the end:
## Example
- Start the slice at index 6 and go all the way to the end:
```php
$x = "Hello World!";
echo substr($x, 6);
```
## Slice From the End
- Use negative indexes to start the slice from the end of the string:
## Example
- Get the 3 characters, starting from the "o" in world (index -5):
```php
$x = "Hello World!";
echo substr($x, -5, 3);
```
## Negative Length
- Use negative length to specify how many characters to omit, starting from the end of the string:
## Example
- From the string "Hi, how are you?", get the characters starting from index 5, and continue until you reach the 3. character from the end (index -3).

- Should end up with "ow are y":
```php
$x = "Hi, how are you?";
echo substr($x, 5, -3);
```
## Complete PHP String Reference
- For a complete reference of all string functions, go to our complete PHP String Reference.
## PHP - Escape Characters
- To insert characters that are illegal in a string, use an escape character.
- An escape character is a backslash \ followed by the character you want to insert.
- An example of an illegal character is a double quote inside a string that is surrounded by double quotes:
## Example
```php
$x = "We are the so-called "Vikings" from the north.";
```
- To fix this problem, use the escape character \":
## Example
```php
$x = "We are the so-called \"Vikings\" from the north.";
```
## Escape Characters
- Other escape characters used in PHP:

| Escape Character | Result            | Description         |
|------------------|-------------------|---------------------|
| `\'`             | Single Quote      | Escapes a single quote in a string  |
| `\"`             | Double Quote      | Escapes a double quote in a string  |
| `\$`             | PHP Variables     | Escapes the dollar sign to prevent variable interpolation  |
| `\n`             | New Line          | Inserts a new line (line break)     |
| `\r`             | Carriage Return   | Inserts a carriage return           |
| `\t`             | Tab               | Inserts a tab space                 |
| `\f`             | Form Feed         | Inserts a form feed (new page in printers) |
| `\ooo`           | Octal Value       | Represents a character in octal     |
| `\xhh`           | Hex Value         | Represents a character in hexadecimal |

## PHP Numbers
- In this chapter we will look in depth into Integers, Floats, and Number Strings.
- There are three main numeric types in PHP:

   - Integer
   - Float
   - Number Strings
- In addition, PHP has two more data types used for numbers:

  - Infinity
  - NaN
- Variables of numeric types are created when you assign a value to them:
## Example
```php
$a = 5;
$b = 5.34;
$c = "25";
```
- To verify the type of any object in PHP, use the var_dump() function:
## Example
```php
var_dump($a);
var_dump($b);
var_dump($c);
```
## PHP Integers
- 2, 256, -256, 10358, -179567 are all integers.
- An integer is a number without any decimal part.
- An integer data type is a non-decimal number between -2147483648 and 2147483647 in 32 bit systems, and between -9223372036854775808 and 9223372036854775807 in 64 bit 
  systems. A value greater (or lower) than this, will be stored as float, because it exceeds the limit of an integer.
- Note: Another important thing to know is that even if 4 * 2.5 is 10, the result is stored as float, because one of the operands is a float (2.5).
- Here are some rules for integers:
  - An integer must have at least one digit
  - An integer must NOT have a decimal point
  - An integer can be either positive or negative
  - Integers can be specified in three formats: decimal (base 10), hexadecimal (base 16 - prefixed with 0x), octal (base 8 - prefixed with 0) or binary (base 2 - prefixed with 0b)
- PHP has the following predefined constants for integers:
  - PHP_INT_MAX - The largest integer supported
  - PHP_INT_MIN - The smallest integer supported
  - PHP_INT_SIZE -  The size of an integer in bytes
- has the following functions to check if the type of a variable is integer:
  - is_int()
  - is_integer() - alias of is_int()
  - is_long() - alias of is_int()
## Example
- Check if the type of a variable is integer:
```php
$x = 5985;
var_dump(is_int($x));

$x = 59.85;
var_dump(is_int($x))
```
## PHP Floats
- A float is a number with a decimal point or a number in exponential form.
- 2.0, 256.4, 10.358, 7.64E+5, 5.56E-5 are all floats.
- The float data type can commonly store a value up to 1.7976931348623E+308 (platform dependent), and have a maximum precision of 14 digits.
- PHP has the following predefined constants for floats (from PHP 7.2):
    - PHP_FLOAT_MAX - The largest representable floating point number
    - PHP_FLOAT_MIN - The smallest representable positive floating point number
    - PHP_FLOAT_DIG - The number of decimal digits that can be rounded into a float and back without precision loss
    - PHP_FLOAT_EPSILON - The smallest representable positive number x, so that x + 1.0 != 1.0
- PHP has the following functions to check if the type of a variable is float:
    - is_float()
is_double() - alias of is_float()

## Example
- Check if the type of a variable is float:
```php
$x = 10.365;
var_dump(is_float($x));
```
## PHP Infinity
- A numeric value that is larger than PHP_FLOAT_MAX is considered infinite.
- PHP has the following functions to check if a numeric value is finite or infinite:
 ```php
is_finite()
is_infinite()
```
- However, the PHP var_dump() function returns the data type and value:
## Example
- Check if a numeric value is finite or infinite:
```php
 $x = 1.9e411;
var_dump($x);
```
## PHP NaN
- NaN stands for Not a Number.
- NaN is used for impossible mathematical operations.
- PHP has the following functions to check if a value is not a number:
   - is_nan()
- However, the PHP var_dump() function returns the data type and value:
## Example
- Invalid calculation will return a NaN value:
```php
$x = acos(8);
var_dump($x);
```
## PHP Numerical Strings
- The PHP is_numeric() function can be used to find whether a variable is numeric. The function returns true if the variable is a number or a numeric string, false otherwise.
## Example
- Check if the variable is numeric:
```php
$x = 5985;
var_dump(is_numeric($x));

$x = "5985";
var_dump(is_numeric($x));
$x = "59.85" + 100;
var_dump(is_numeric($x));

$x = "Hello";
var_dump(is_numeric($x));
```
## PHP Casting Strings and Floats to Integers
- Sometimes you need to cast a numerical value into another data type.
- The (int), (integer), and intval() functions are often used to convert a value to an integer.
## Example
- Cast float and string to integer:
```php
// Cast float to int
$x = 23465.768;
$int_cast = (int)$x;
echo $int_cast;

echo "<br>";

// Cast string to int
$x = "23465.768";
$int_cast = (int)$x;
echo $int_cast;
```
## PHP Casting
- Sometimes you need to change a variable from one data type into another, and sometimes you want a variable to have a specific data type. This can be done with casting.
## Change Data Type
- Casting in PHP is done with these statements:
    - (string) - Converts to data type String
    - (int) - Converts to data type Integer
    - (float) - Converts to data type Float
    - (bool) - Converts to data type Boolean
    - (array) - Converts to data type Array
    - (object) - Converts to data type Object
    - (unset) - Converts to data type NULL
## Cast to String
- To cast to string, use the (string) statement:
## Example
```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = "hello"; // String
$d = true;    // Boolean
$e = NULL;    // NULL

$a = (string) $a;
$b = (string) $b;
$c = (string) $c;
$d = (string) $d;
$e = (string) $e;

//To verify the type of any object in PHP, use the var_dump() function:
var_dump($a);
var_dump($b);
var_dump($c);
var_dump($d);
var_dump($e);
```
## Cast to Integer
- To cast to integer, use the (int) statement:
## Example
```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = "25 kilometers"; // String
$d = "kilometers 25"; // String
$e = "hello"; // String
$f = true;    // Boolean
$g = NULL;    // NULL

$a = (int) $a;
$b = (int) $b;
$c = (int) $c;
$d = (int) $d;
$e = (int) $e;
$f = (int) $f;
$g = (int) $g;
```
## Cast to Float
- To cast to float, use the (float) statement:
## Example
```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = "25 kilometers"; // String
$d = "kilometers 25"; // String
$e = "hello"; // String
$f = true;    // Boolean
$g = NULL;    // NULL

$a = (float) $a;
$b = (float) $b;
$c = (float) $c;
$d = (float) $d;
$e = (float) $e;
$f = (float) $f;
$g = (float) $g;
```
## Cast to Boolean
- To cast to boolean, use the (bool) statement:
## Example
```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = 0;       // Integer
$d = -1;      // Integer
$e = 0.1;     // Float
$f = "hello"; // String
$g = "";      // String
$h = true;    // Boolean
$i = NULL;    // NULL

$a = (bool) $a;
$b = (bool) $b;
$c = (bool) $c;
$d = (bool) $d;
$e = (bool) $e;
$f = (bool) $f;
$g = (bool) $g;
$h = (bool) $h;
$i = (bool) $i;
```
- If a value is 0, NULL, false, or empty, the (bool) converts it into false, otherwise true.

- Even -1 converts to true.
## Cast to Array
- To cast to array, use the (array) statement:
## Example
```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = "hello"; // String
$d = true;    // Boolean
$e = NULL;    // NULL

$a = (array) $a;
$b = (array) $b;
$c = (array) $c;
$d = (array) $d;
$e = (array) $e;
```
- When converting into arrays, most data types converts into an indexed array with one element.
- NULL values converts to an empty array object.
- Objects converts into associative arrays where the property names becomes the keys and the property values becomes the values:
## Example
- Converting Objects into Arrays:
```php
class Car {
  public $color;
  public $model;
  public function __construct($color, $model) {
    $this->color = $color;
    $this->model = $model;
  }
  public function message() {
    return "My car is a " . $this->color . " " . $this->model . "!";
  }
}

$myCar = new Car("red", "Volvo");

$myCar = (array) $myCar;
var_dump($myCar);
```
## Cast to Object
- To cast to object, use the (object) statement:
## Example

```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = "hello"; // String
$d = true;    // Boolean
$e = NULL;    // NULL

$a = (object) $a;
$b = (object) $b;
$c = (object) $c;
$d = (object) $d;
$e = (object) $e;
```
- When converting into objects, most data types converts into a object with one property, named "scalar", with the corresponding value.
- NULL values converts to an empty object.
- Indexed arrays converts into objects with the index number as property name and the value as property value.
- Associative arrays converts into objects with the keys as property names and values as property values.
## Example
- Converting Arrays into Objects:
```php
  $a = array("Volvo", "BMW", "Toyota"); // indexed array
$b = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43"); // associative array

$a = (object) $a;
$b = (object) $b;
```
## Cast to NULL
- To cast to NULL, use the (unset) statement:
## Example
```php
$a = 5;       // Integer
$b = 5.34;    // Float
$c = "hello"; // String
$d = true;    // Boolean
$e = NULL;    // NULL

$a = (unset) $a;
$b = (unset) $b;
$c = (unset) $c;
$d = (unset) $d;
$e = (unset) $e;
```
## PHP Math
- PHP has a set of math functions that allows you to perform mathematical tasks on numbers.
## PHP pi() Function
- The pi() function returns the value of PI:
## Example
```php
echo(pi());
```
## PHP min() and max() Functions
- The min() and max() functions can be used to find the lowest or highest value in a list of arguments:
## Example
```php
echo(min(0, 150, 30, 20, -8, -200));
echo(max(0, 150, 30, 20, -8, -200));
```
## PHP abs() Function
- The abs() function returns the absolute (positive) value of a number:
## Example
```php
echo(abs(-6.7));
```
## PHP sqrt() Function
The sqrt() function returns the square root of a number:
## Example
```php
echo(sqrt(64));
```
- PHP round() Function
- The round() function rounds a floating-point number to its nearest integer:
## Example
```php
echo(round(0.60));
echo(round(0.49));
```
## Random Numbers
- The rand() function generates a random number:
## Example
```php
echo(rand());
```
- To get more control over the random number, you can add the optional min and max parameters to specify the lowest integer and the highest integer to be returned.
- For example, if you want a random integer between 10 and 100 (inclusive), use rand(10, 100):
## Example
```php
echo(rand(10, 100));
```
## Complete PHP Math Reference
- For a complete reference of all math functions, go to our complete PHP Math Reference.

- The PHP math reference contains description and example of use, for each function.
## PHP Constants
- Constants are like variables, except that once they are defined they cannot be changed or undefined.
## PHP Constants
- A constant is an identifier (name) for a simple value. The value cannot be changed during the script.
- A valid constant name starts with a letter or underscore (no $ sign before the constant name).


- Note: Unlike variables, constants are automatically global across the entire script.

## Create a PHP Constant
- To create a constant, use the define() function.
## Syntax
```php
define(name, value);
```
## Parameters:
  - name: Specifies the name of the constant
  - value: Specifies the value of the constant
## Example
- Create a constant with a case-sensitive name:
```php
define("GREETING", "Welcome to W3Schools.com!");
echo GREETING;
```
## PHP const Keyword
- You can also create a constant by using the const keyword.
## Example
- Create a case-sensitive constant with the const keyword:
```php
const MYCAR = "Volvo";
echo MYCAR;
```
## PHP Constant Arrays
- From PHP7, you can create an Array constant using the define() function.
## Example
- Create an Array constant:
```php
define("cars", [
  "Alfa Romeo",
  "BMW",
  "Toyota"
]);
echo cars[0];
```
## Constants are Global
- Constants are automatically global and can be used across the entire script.
## Example
```php
define("GREETING", "Welcome to W3Schools.com!");

function myTest() {
  echo GREETING;
}

myTest();
```
## PHP Magic Constants

## PHP Predefined Constants
- PHP has nine predefined constants that change value depending on where they are used, and therefor they are called "magic constants".
- These magic constants are written with a double underscore at the start and the end, except for the ClassName::class constant.
## Magic Constants
- Here are the magic constants, with descriptions and examples:
  
| Constant            | Description                                                                 |
|---------------------|-----------------------------------------------------------------------------|
| `__CLASS__`         | If used inside a class, the class name is returned.                         |
| `__DIR__`           | The directory of the file.                                                  |
| `__FILE__`          | The file name including the full path.                                      |
| `__FUNCTION__`      | If inside a function, the function name is returned.                        |
| `__LINE__`          | The current line number.                                                    |
| `__METHOD__`        | If used inside a function that belongs to a class, both class and function name is returned. |
| `__NAMESPACE__`     | If used inside a namespace, the name of the namespace is returned.          |
| `__TRAIT__`         | If used inside a trait, the trait name is returned.                         |
| `ClassName::class`  | Returns the name of the specified class and the name of the namespace, if any. |

## Note:

- The magic constants are case-insensitive, meaning __LINE__ returns the same as __line__.
  
## PHP Operators
- Operators are used to perform operations on variables and values.
- PHP divides the operators in the following groups:
- Arithmetic operators
- Assignment operators
- Comparison operators
- Increment/Decrement operators
- Logical operators
- String operators
- Array operators
- Conditional assignment operators
## PHP Arithmetic Operators
- The PHP arithmetic operators are used with numeric values to perform common arithmetical operations, such as addition, subtraction, multiplication etc.
  
| Operator       | Name            | Example     | Result                               |
| -------------- | --------------- | ----------- | ------------------------------------ |
| `+`            | Addition        | `$x + $y`   | Sum of `$x` and `$y`                 |
| `-`            | Subtraction     | `$x - $y`   | Difference of `$x` and `$y`          |
| `*`            | Multiplication  | `$x * $y`   | Product of `$x` and `$y`             |
| `/`            | Division        | `$x / $y`   | Quotient of `$x` and `$y`            |
| `%`            | Modulus         | `$x % $y`   | Remainder of `$x` divided by `$y`    |
| `**`           | Exponentiation  | `$x ** $y`  | Result of raising `$x` to the `$y`'th power |

## PHP Assignment Operators
- The PHP assignment operators are used with numeric values to write a value to a variable.
- The basic assignment operator in PHP is "=". It means that the left operand gets set to the value of the assignment expression on the right.

| Assignment | Same as...   | Description                                         |
| ---------- | ------------ | --------------------------------------------------- |
| `x = y`    | `x = y`      | The left operand gets set to the value on the right |
| `x += y`   | `x = x + y`  | Addition                                            |
| `x -= y`   | `x = x - y`  | Subtraction                                         |
| `x *= y`   | `x = x * y`  | Multiplication                                      |
| `x /= y`   | `x = x / y`  | Division                                            |
| `x %= y`   | `x = x % y`  | Modulus                                             |

## PHP Comparison Operators
- The PHP comparison operators are used to compare two values (number or string):

| Operator | Name                         | Example      | Result                                                                 |
| -------- | ---------------------------- | ------------ | ---------------------------------------------------------------------- |
| `==`     | Equal                        | `$x == $y`   | Returns true if `$x` is equal to `$y`                                  |
| `===`    | Identical                    | `$x === $y`  | Returns true if `$x` is equal to `$y`, and they are of the same type   |
| `!=`     | Not equal                    | `$x != $y`   | Returns true if `$x` is not equal to `$y`                              |
| `<>`     | Not equal                    | `$x <> $y`   | Returns true if `$x` is not equal to `$y`                              |
| `!==`    | Not identical                | `$x !== $y`  | Returns true if `$x` is not equal to `$y`, or they are not of the same type |
| `>`      | Greater than                 | `$x > $y`    | Returns true if `$x` is greater than `$y`                              |
| `<`      | Less than                    | `$x < $y`    | Returns true if `$x` is less than `$y`                                 |
| `>=`     | Greater than or equal to     | `$x >= $y`   | Returns true if `$x` is greater than or equal to `$y`                  |
| `<=`     | Less than or equal to        | `$x <= $y`   | Returns true if `$x` is less than or equal to `$y`                     |
| `<=>`    | Spaceship                    | `$x <=> $y`  | Returns an integer: -1 if `$x` < `$y`, 0 if equal, 1 if `$x` > `$y`    |

## PHP Increment / Decrement Operators
| Operator | Same as...     | Description                                      |
|----------|----------------|--------------------------------------------------|
| ++$x    | Pre-increment   | Increments $x by one, then returns $x           |
| $x++    | Post-increment  | Returns $x, then increments $x by one           |
| --$x    | Pre-decrement   | Decrements $x by one, then returns $x           |
| $x--    | Post-decrement  | Returns $x, then decrements $x by one           |

## PHP Logical Operators
- The PHP logical operators are used to combine conditional statements.

  
| Operator | Name | Example       | Result                                      |
|----------|------|---------------|---------------------------------------------|
| and      | And  | $x and $y    | True if both $x and $y are true            |
| or       | Or   | $x or $y     | True if either $x or $y is true            |
| xor      | Xor  | $x xor $y    | True if either $x or $y is true, but not both |
| &&       | And  | $x && $y     | True if both $x and $y are true            |
| ||       | Or   | $x || $y     | True if either $x or $y is true            |
| !        | Not  | !$x          | True if $x is not true                     |

## PHP String Operators


| **Operator** | **Name**                | **Example**     | **Result**                             |
|--------------|-------------------------|-----------------|----------------------------------------|
| `.`          | Concatenation            | `$txt1 . $txt2` | Concatenation of `$txt1` and `$txt2`   |
| `.= `        | Concatenation assignment | `$txt1 .= $txt2`| Appends `$txt2` to `$txt1`             |


## PHP Array Operators
- The PHP array operators are used to compare arrays.
  

| **Operator** | **Name**     | **Example**    | **Result**                                                         |
|--------------|--------------|----------------|--------------------------------------------------------------------|
| `+`          | Union        | `$x + $y`      | Union of `$x` and `$y`                                             |
| `==`         | Equality     | `$x == $y`     | Returns true if `$x` and `$y` have the same key/value pairs       |
| `===`        | Identity     | `$x === $y`    | Returns true if `$x` and `$y` have the same key/value pairs in the same order and of the same types |
| `!=`         | Inequality   | `$x != $y`     | Returns true if `$x` is not equal to `$y`                          |
| `<>`         | Inequality   | `$x <> $y`     | Returns true if `$x` is not equal to `$y`                          |
| `!==`        | Non-identity | `$x !== $y`    | Returns true if `$x` is not identical to `$y`                      |


## PHP Conditional Assignment Operators
- The PHP conditional assignment operators are used to set a value depending on conditions:


| **Operator** | **Name**           | **Example**                          | **Result**                                                                                                                                              |
|--------------|--------------------|--------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------|
| `?:`         | Ternary            | `$x = expr1 ? expr2 : expr3`         | Returns the value of `$x`. The value is `expr2` if `expr1 = TRUE`, otherwise `expr3` if `expr1 = FALSE`.                                               |
| `??`         | Null coalescing     | `$x = expr1 ?? expr2`                | Returns the value of `$x`. The value is `expr1` if it exists and is not `NULL`; otherwise, the value is `expr2`. Introduced in PHP 7.                   |



## PHP if Statements
- Conditional statements are used to perform different actions based on different conditions.
## PHP Conditional Statements
- Very often when you write code, you want to perform different actions for different conditions. You can use conditional statements in your code to do this.
- In PHP we have the following conditional statements:
     - if statement - executes some code if one condition is true
     - if...else statement - executes some code if a condition is true and another code if that condition is false
     - if...elseif...else statement - executes different codes for more than two conditions
       switch statement - selects one of many blocks of code to be executed
## PHP - The if Statement
- Syntax
```php
if (condition) {
  // code to be executed if condition is true;
}
```
## Example
- Output "Have a good day!" if 5 is larger than 3:
```php
if (5 > 3) {
  echo "Have a good day!";
}
```
- We can also use variables in the if statement:

## Example
- Output "Have a good day!" if $t is less than 20:

```php
$t = 14;
if ($t < 20) {
  echo "Have a good day!";
}
```
## PHP if Operators

## Comparison Operators
- If statements usually contain conditions that compare two values.

## Example
- Check if $t is equal to 14:
```php
$t = 14;

if ($t == 14) {
  echo "Have a good day!";
}
```
- To compare two values, we need to use a comparison operator.
- Here are the PHP comparison operators to use in if statements:

| Operator | Name                     | Result                                                         |
|----------|--------------------------|----------------------------------------------------------------|
| ==       | Equal                    | Returns true if the values are equal                            |
| ===      | Identical                | Returns true if the values and data types are identical         |
| !=       | Not equal                | Returns true if the values are not equal                        |
| <>       | Not equal                | Returns true if the values are not equal                        |
| !==      | Not identical            | Returns true if the values or data types are not identical       |
| >        | Greater than             | Returns true if the first value is greater than the second value |
| <        | Less than                | Returns true if the first value is less than the second value    |
| >=       | Greater than or equal to | Returns true if the first value is greater than, or equal to, the second value |
| <=       | Less than or equal to    | Returns true if the first value is less than, or equal to, the second value    |


## Logical Operators
- To check more than one condition, we can use logical operators, like the && operator:

## Example
- Check if $a is greater than $b, AND if $a is less than $c:
 ```php
$a = 200;
$b = 33;
$c = 500;

if ($a > $b && $a < $c ) {
  echo "Both conditions are true";
}
```
- Here are the PHP logical operators to use in if statements:

| Operator | Name | Description                                      |
|----------|------|--------------------------------------------------|
| and      | And  | True if both conditions are true                 |
| &&       | And  | True if both conditions are true                 |
| or       | Or   | True if either condition is true                 |
| ||       | Or   | True if either condition is true                 |
| xor      | Xor  | True if either condition is true, but not both   |
| !        | Not  | True if the condition is not true                |

- We can compare as many conditions as we like in one if statement:
## Example
- Check if $a is either 2, 3, 4, 5, 6, or 7:
```php
$a = 5;

if ($a == 2 || $a == 3 || $a == 4 || $a == 5 || $a == 6 || $a == 7) {
  echo "$a is a number between 2 and 7";
}
```
## PHP if...else Statements
- The if...else statement executes some code if a condition is true and another code if that condition is false.
## Syntax
```php
if (condition) {
  // code to be executed if condition is true;
} else {
  // code to be executed if condition is false;
}
```
## Example
- Output "Have a good day!" if the current time is less than 20, and "Have a good night!" otherwise:

```php
$t = date("H");

if ($t < "20") {
  echo "Have a good day!";
} else {
  echo "Have a good night!";
}
```
## PHP - The if...elseif...else Statement
- The if...elseif...else statement executes different codes for more than two conditions.

## Syntax
```php
if (condition) {
  code to be executed if this condition is true;
} elseif (condition) {
  // code to be executed if first condition is false and this condition is true;
} else {
  // code to be executed if all conditions are false;
}
```
## Example
- Output "Have a good morning!" if the current time is less than 10, and "Have a good day!" if the current time is less than 20. Otherwise it will output "Have a good night!":

 ```php
<?php
$t = date("H");

if ($t < "10") {
  echo "Have a good morning!";
} elseif ($t < "20") {
  echo "Have a good day!";
} else {
  echo "Have a good night!";
}
?>
```

## PHP Shorthand if Statements

## Short Hand If
## Example
- One-line if statement:

```php
$a = 5;

if ($a < 10) $b = "Hello";

echo $b
```
## Short Hand If...Else
- if...else statements can also be written in one line, but the syntax is a bit different.
## Example
One-line if...else statement:
```php
$a = 13;

$b = $a < 10 ? "Hello" : "Good Bye";

echo $b;
```
## PHP Nested if Statement
## Nested If
- You can have if statements inside if statements, this is called nested if statements.
## Example
- An if inside an if:
```php
$a = 13;

if ($a > 10) {
  echo "Above 10";
  if ($a > 20) {
    echo " and also above 20";
  } else {
    echo " but not above 20";
  }
}
```

## PHP switch Statement
- The switch statement is used to perform different actions based on different conditions.

## The PHP switch Statement
- Use the switch statement to select one of many blocks of code to be executed.

## Syntax
```php
switch (expression) {
  case label1:
    //code block
    break;
  case label2:
    //code block;
    break;
  case label3:
    //code block
    break;
  default:
    //code block
}
```
## This is how it works:

- The expression is evaluated once
- The value of the expression is compared with the values of each case
- If there is a match, the associated block of code is executed
- The break keyword breaks out of the switch block
- The default code block is executed if there is no match

## Example
```php
$favcolor = "red";

switch ($favcolor) {
  case "red":
    echo "Your favorite color is red!";
    break;
  case "blue":
    echo "Your favorite color is blue!";
    break;
  case "green":
    echo "Your favorite color is green!";
    break;
  default:
    echo "Your favorite color is neither red, blue, nor green!";
}
```
## The break Keyword
- When PHP reaches a break keyword, it breaks out of the switch block.

- This will stop the execution of more code, and no more cases are tested.

- The last block does not need a break, the block breaks (ends) there anyway.
  
  ## Warning: If you omit the break statement in a case that is not the last, and that case gets a match, the next case will also be executed even if the evaluation does not match the case!

## Example
- What happens if we remove the break statement from case "red"?

- $favcolor is red, so the code block from case "red" is executed, but since it has no break statement, the code block from case "blue" will also be executed:

```php
$favcolor = "red";

switch ($favcolor) {
  case "red":
    echo "Your favorite color is red!";
  case "blue":
    "Your favorite color is blue!";
    break;
  case "green":
    echo "Your favorite color is green!";
    break;
  default:
    echo "Your favorite color is neither red, blue, nor green!";
}
```
## The default Keyword
- The default keyword specifies the code to run if there is no case match:

## Example
- If no cases get a match, the default block is executed:
```php
  $d = 4;

switch ($d) {
  case 6:
    echo "Today is Saturday";
    break;
  case 0:
    echo "Today is Sunday";
    break;
  default:
    echo "Looking forward to the Weekend";
}
```
- The default case does not have to be the last case in a switch block:
## Example
- Putting  the default block elsewhere than at the end of the switch block is allowed, but not recommended.
```php
  $d = 4;

switch ($d) {
  default:
    echo "Looking forward to the Weekend";
    break;
  case 6:
    echo "Today is Saturday";
    break;
  case 0:
    echo "Today is Sunday";
}
```
## Common Code Blocks
- If you want multiple cases to use the same code block, you can specify the cases like this:
## Example
- More than one case for each code block:

```php
$d = 3;

switch ($d) {
  case 1:
  case 2:
  case 3:
  case 4:
  case 5:  
    echo "The weeks feels so long!";
    break;
  case 6:
  case 0:
    echo "Weekends are the best!";
    break;
  default:
    echo "Something went wrong";
}
```
## PHP Loops
- In the following chapters you will learn how to repeat code by using loops in PHP.

## PHP Loops
- Often when you write code, you want the same block of code to run over and over again a certain number of times. So, instead of adding several almost equal code-lines in a script, we can use loops.

- Loops are used to execute the same block of code again and again, as long as a certain condition is true.

In PHP, we have the following loop types:

- while - loops through a block of code as long as the specified condition is true
- do...while - loops through a block of code once, and then repeats the loop as long as the specified condition is true
- for - loops through a block of code a specified number of times
- foreach - loops through a block of code for each element in an array
- The following chapters will explain and give examples of each loop type.

## PHP while Loop
