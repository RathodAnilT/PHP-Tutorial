
# 🚀🚀PHP-Tutorial🚀🚀
- For more information on PHP, check out the [W3Schools PHP Tutorial](https://www.w3schools.com/php/)...
- PHP is a server scripting language, and a powerful tool for making dynamic and interactive Web pages.

- PHP is a widely-used, free, and efficient alternative to competitors such as Microsoft's ASP..

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
## PHP Introduction..............Let's Gooooooooo.........🚀🚀

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
- The while loop - Loops through a block of code as long as the specified condition is true.
## The PHP while Loop
- The while loop executes a block of code as long as the specified condition is true.
## Example
- Print $i as long as $i is less than 6:
```php
$i = 1;
while ($i < 6) {
  echo $i;
  $i++;
}
```
- Note: remember to increment $i, or else the loop will continue forever.

- The while loop does not run a specific number of times, but checks after each iteration if the condition is still true.

- The condition does not have to be a counter, it could be the status of an operation or any condition that evaluates to either true or false.

## The break Statement
- With the break statement we can stop the loop even if the condition is still true:

## Example
- Stop the loop when $i is 3:
```php
$i = 1;

do {
  if ($i == 3) break;
  echo $i;
  $i++;
} while ($i < 6);
```
## The continue Statement
- With the continue statement we can stop the current iteration, and continue with the next:
## Example
- Stop, and jump to the next iteration if $i is 3:
```php
$i = 0;
while ($i < 6) {
  $i++;
  if ($i == 3) continue;
  echo $i;
}
```
## Alternative Syntax
- The while loop syntax can also be written with the endwhile statement like this
## Example
- Print $i as long as $i is less than 6:

```php
$i = 1;
while ($i < 6):
  echo $i;
  $i++;
endwhile;
```
## Step 10
- If you want the while loop count to 100, but only by each 10, you can increase the counter by 10 instead 1 in each iteration:

## Example
- Count to 100 by tens:
```php
$i = 0;
while ($i < 100) {
  $i+=10;
  echo $i "<br>";
}
```

## PHP do while Loop
- The do...while loop - Loops through a block of code once, and then repeats the loop as long as the specified condition is true.
## Example
- Print $i as long as $i is less than 6:
```php
$i = 1;

do {
  echo $i;
  $i++;
} while ($i < 6);
```

## Note: 
- In a do...while loop the condition is tested AFTER executing the statements within the loop. This means that the do...while loop will execute its statements at least once, even if the condition is false. See example below.

- Let us see what happens if we set the $i variable to 8 instead of 1, before execute the same do...while loop again:

## Example
- Set $i = 8, then print $i as long as $i is less than 6:
```php
$i = 8;

do {
  echo $i;
  $i++;
} while ($i < 6);
```
## The break Statement
- With the break statement we can stop the loop even if the condition is still true:

## Example
- Stop the loop when $i is 3:
```php
$i = 1;

do {
  if ($i == 3) break;
  echo $i;
  $i++;
}
``` 
## The continue Statement
- With the continue statement we can stop the current iteration, and continue with the next:

## Example
- Stop, and jump to the next iteration if $x is 3:
```php
for ($x = 0; $x <= 10; $x++) {
  if ($x == 3) continue;
  echo "The number is: $x <br>";
}
```
## PHP for Loop
- The for loop - Loops through a block of code a specified number of times.

## The PHP for Loop
- The for loop is used when you know how many times the script should run.

## Syntax
```php
for (expression1, expression2, expression3) {
  // code block
}
```

## This is how it works:

- expression1 is evaluated once
- expression2 is evaluated before each iteration
- expression3 is evaluated after each iteration

## Example
- Print the numbers from 0 to 10:
```php
for ($x = 0; $x <= 10; $x++) {
  echo "The number is: $x <br>";
}
```
## Example Explained
- The first expression, $x = 0;, is evaluated once and sets a counter to 0.
- The second expression, $x <= 10;, is evaluated before each iteration, and the code block is only executed if this expression evaluates to true. In this example the expression is true as long as $x is less than, or equal to, 10.
- The third expression, $x++;, is evaluated after each iteration, and in this example, the expression increases the value of $x by one at each iteration.

## The break Statement
- With the break statement we can stop the loop even if the condition is still true:

## Example
- Stop the loop when $x is 3:
```php
for ($x = 0; $x <= 10; $x++) {
  if ($x == 3) break;
  echo "The number is: $x <br>";
}
```
## The continue Statement
- With the continue statement we can stop the current iteration, and continue with the next:

## Example
- Stop, and jump to the next iteration if $x is 3:
```php
for ($x = 0; $x <= 10; $x++) {
  if ($x == 3) continue;
  echo "The number is: $x <br>";
}
```

## Step 10
- This example counts to 100 by tens:

## Example
```php
for ($x = 0; $x <= 100; $x+=10) {
  echo "The number is: $x <br>";
}
```
## PHP foreach Loop
- The foreach loop - Loops through a block of code for each element in an array or each property in an object.

## The foreach Loop on Arrays
- The most common use of the foreach loop, is to loop through the items of an array.

## Example
- Loop through the items of an indexed array:
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) {
  echo "$x <br>";
}
```

- For every loop iteration, the value of the current array element is assigned to the variabe $x. The iteration continues until it reaches the last array element.

## Keys and Values
- The array above is an indexed array, where the first item has the key 0, the second has the key 1, and so on.

- Associative arrays are different, associative arrays use named keys that you assign to them, and when looping through associative arrays, you might want to keep the key as well as the value.

- This can be done by specifying both the key and value in the foreach defintition, like this:

## Example
- Print both the key and the value from the $members array:
```php
$members = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");

foreach ($members as $x => $y) {
  echo "$x : $y <br>";
}
```

## The foreach Loop on Objects
- The foreach loop can also be used to loop through properties of an object:

## Example
- Print the property names and values of the $myCar object:
```php
class Car {
  public $color;
  public $model;
  public function __construct($color, $model) {
    $this->color = $color;
    $this->model = $model;
  }
}

$myCar = new Car("red", "Volvo");

foreach ($myCar as $x => $y) {
  echo "$x: $y <br>";
}
```

## The break Statement
- With the break statement we can stop the loop even if it has not reached the end:

## Example
- Stop the loop if $x is "blue":
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) {
  if ($x == "blue") break;
  echo "$x <br>";
}
```
## The continue Statement
- With the continue statement we can stop the current iteration, and continue with the next:

## Example
- Stop, and jump to the next iteration if $x is "blue":
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) {
  if ($x == "blue") continue;
  echo "$x <br>";
}
```

## Foreach Byref
- When looping through the array items, any changes done to the array item will, by default, NOT affect the original array:

## Example
- By default, changing an array item will not affect the original array:
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) {
  if ($x == "blue") $x = "pink";
}

var_dump($colors);
```
- BUT, by using the & character in the foreach declaration, the array item is assigned by reference, which results in any changes done to the array item will also be done to the original array:

## Example
- By assigning the array items by reference, changes will affect the original array:
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as &$x) {
  if ($x == "blue") $x = "pink";
}

var_dump($colors);
```

## Alternative Syntax
- The foreach loop syntax can also be written with the endforeach statement like this

## Example
- Loop through the items of an indexed array:
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) :
  echo "$x <br>";
endforeach;
```
## PHP Break
- The break statement can be used to jump out of different kind of loops.

## Break in For loop
- The break statement can be used to jump out of a for loop.
## Example
- Jump out of the loop when $x is 4:
```php
for ($x = 0; $x < 10; $x++) {
  if ($x == 4) {
    break;
  }
  echo "The number is: $x <br>";
}
```
## Break in While Loop
- The break statement can be used to jump out of a while loop.

## Break Example
```php
$x = 0;

while($x < 10) {
  if ($x == 4) {
    break;
  }
  echo "The number is: $x <br>";
  $x++;
}
```

## Break in Do While Loop
- The break statement can be used to jump out of a do...while loop.

## Example
- Stop the loop when $i is 3:
```php
$i = 1;

do {
  if ($i == 3) break;
  echo $i;
  $i++;
} while ($i < 6);
```

## Break in For Each Loop
- The break statement can be used to jump out of a foreach loop.

## Example
- Stop the loop if $x is "blue":

```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) {
  if ($x == "blue") break;
  echo "$x <br>";
}
```

## PHP Continue
- The continue statement can be used to jump out of the current iteration of a loop, and continue with the next.

## Continue in For Loops
- The continue statement stops the current iteration in the for loop and continue with the next.
  
## Example
- Move to next iteration if $x = 4:
```php
  for ($x = 0; $x < 10; $x++) {
  if ($x == 4) {
    continue;
  }
  echo "The number is: $x <br>";
 }
 ```
## Continue in While Loop
- The continue statement stops the current iteration in the while loop and continue with the next.

## Continue Example
- Move to next iteration if $x = 4:
```php
$x = 0;

while($x < 10) {
  if ($x == 4) {
    continue;
  }
  echo "The number is: $x <br>";
  $x++;
}
```

## Continue in Do While Loop
- The continue statement stops the current iteration in the do...while loop and continue with the next.

## Example
- Stop, and jump to the next iteration if $i is 3:
```php
$i = 0;

do {
  $i++;
  if ($i == 3) continue;
  echo $i;
} while ($i < 6);
```
## Continue in For Each Loop
- The continue statement stops the current iteration in the foreach loop and continue with the next.

## Example
- Stop, and jump to the next iteration if $x is "blue":
```php
$colors = array("red", "green", "blue", "yellow");

foreach ($colors as $x) {
  if ($x == "blue") continue;
  echo "$x <br>";
}
```

## PHP Functions
- The real power of PHP comes from its functions.

- PHP has more than 1000 built-in functions, and in addition you can create your own custom functions.

## PHP Built-in Functions
- PHP has over 1000 built-in functions that can be called directly, from within a script, to perform a specific task.

- Please check out our PHP reference for a complete overview of the PHP built-in functions.

## PHP User Defined Functions
- Besides the built-in PHP functions, it is possible to create your own functions.

- A function is a block of statements that can be used repeatedly in a program.
- A function will not execute automatically when a page loads.
- A function will be executed by a call to the function.
## Create a Function
- A user-defined function declaration starts with the keyword function, followed by the name of the function:
## Example
```php
function myMessage() {
  echo "Hello world!";
}
```

- Note: A function name must start with a letter or an underscore. Function names are NOT case-sensitive.

- Tip: Give the function a name that reflects what the function does!

## Call a Function
- To call the function, just write its name followed by parentheses ():

## Example
```php
function myMessage() {
  echo "Hello world!";
}

myMessage();
```

- In our example, we create a function named myMessage().

- The opening curly brace { indicates the beginning of the function code, and the closing curly brace } indicates the end of the function.

- The function outputs "Hello world!".

## PHP Function Arguments
- Information can be passed to functions through arguments. An argument is just like a variable.

- Arguments are specified after the function name, inside the parentheses. You can add as many arguments as you want, just separate them with a comma.

- The following example has a function with one argument ($fname). When the familyName() function is called, we also pass along a name, e.g. ("Jani"), and the name is used 
  inside the function, which outputs several different first names, but an equal last name:

## Example
```php
function familyName($fname) {
  echo "$fname Refsnes.<br>";
}

familyName("Jani");
familyName("Hege");
familyName("Stale");
familyName("Kai Jim")
```
- The following example has a function with two arguments ($fname, $year):

## Example
```php
function familyName($fname, $year) {
  echo "$fname Refsnes. Born in $year <br>";
}

familyName("Hege", "1975");
familyName("Stale", "1978");
familyName("Kai Jim", "1983");
```
## PHP Default Argument Value
- The following example shows how to use a default parameter. If we call the function setHeight() without arguments it takes the default value as argument:

## Example
```php
function setHeight($minheight = 50) {
  echo "The height is : $minheight <br>";
}

setHeight(350);
setHeight(); // will use the default value of 50
setHeight(135);
setHeight(80);
```

## PHP Functions - Returning values
- To let a function return a value, use the return statement:

## Example
```php
function sum($x, $y) {
  $z = $x + $y;
  return $z;
}

echo "5 + 10 = " . sum(5, 10) . "<br>";
echo "7 + 13 = " . sum(7, 13) . "<br>";
echo "2 + 4 = " . sum(2, 4);
```

## Passing Arguments by Reference
- In PHP, arguments are usually passed by value, which means that a copy of the value is used in the function and the variable that was passed into the function cannot 
 changed.

- When a function argument is passed by reference, changes to the argument also change the variable that was passed in. To turn a function argument into a reference, the & operator is used:

## Example
- Use a pass-by-reference argument to update a variable:
```php
function add_five(&$value) {
  $value += 5;
}

$num = 2;
add_five($num);
echo $num;
```

## Variable Number of Arguments
- By using the ... operator in front of the function parameter, the function accepts an unknown number of arguments. This is also called a variadic function.

- The variadic function argument becomes an array.

## Example
- A function that do not know how many arguments it will get:
```php
function sumMyNumbers(...$x) {
  $n = 0;
  $len = count($x);
  for($i = 0; $i < $len; $i++) {
    $n += $x[$i];
  }
  return $n;
}

$a = sumMyNumbers(5, 2, 6, 2, 7, 7);
echo $a;
```

- You can only have one argument with variable length, and it has to be the last argument.

## Example
- The variadic argument must be the last argument:
```php
function myFamily($lastname, ...$firstname) {
  txt = "";
  $len = count($firstname);
  for($i = 0; $i < $len; $i++) {
    $txt = $txt."Hi, $firstname[$i] $lastname.<br>";
  }
  return $txt;
}

$a = myFamily("Doe", "Jane", "John", "Joey");
echo $a;
```
## Example
- Having the ... operator on the first of two arguments, will raise an error:
```php
function myFamily(...$firstname, $lastname) {
  $txt = "";
  $len = count($firstname);
  for($i = 0; $i < $len; $i++) {
    $txt = $txt."Hi, $firstname[$i] $lastname.<br>";
  }
  return $txt;
}

$a = myFamily("Doe", "Jane", "John", "Joey");
echo $a;
```

## PHP is a Loosely Typed Language
- In the examples above, notice that we did not have to tell PHP which data type the variable is.

- PHP automatically associates a data type to the variable, depending on its value. Since the data types are not set in a strict sense, you can do things like adding a string to an integer without causing an error.

- In PHP 7, type declarations were added. This gives us an option to specify the expected data type when declaring a function, and by adding the strict declaration, it will throw a "Fatal Error" if the data type mismatches.

- In the following example we try to send both a number and a string to the function without using strict:

## Example
```php
function addNumbers(int $a, int $b) {
  return $a + $b;
}
echo addNumbers(5, "5 days");
// since strict is NOT enabled "5 days" is changed to int(5), and it will return 10
```

- To specify strict we need to set declare(strict_types=1);. This must be on the very first line of the PHP file.

- In the following example we try to send both a number and a string to the function, but here we have added the strict declaration:

## Example
```php
<?php declare(strict_types=1); // strict requirement

function addNumbers(int $a, int $b) {
  return $a + $b;
}
echo addNumbers(5, "5 days");
// since strict is enabled and "5 days" is not an integer, an error will be thrown
?>
```

- The strict declaration forces things to be used in the intended way.

## PHP Return Type Declarations
- PHP 7 also supports Type Declarations for the return statement. Like with the type declaration for function arguments, by enabling the strict requirement, it will throw a "Fatal Error" on a type mismatch.

- To declare a type for the function return, add a colon ( : ) and the type right before the opening curly ( { )bracket when declaring the function.

- In the following example we specify the return type for the function:

## Example
```php
<?php declare(strict_types=1); // strict requirement
function addNumbers(float $a, float $b) : float {
  return $a + $b;
}
echo addNumbers(1.2, 5.2);
?>
```
- You can specify a different return type, than the argument types, but make sure the return is the correct type:

## Example
```php
<?php declare(strict_types=1); // strict requirement
function addNumbers(float $a, float $b) : int {
  return (int)($a + $b);
}
echo addNumbers(1.2, 5.2);
```
## PHP Arrays
- An array stores multiple values in one single variable:
## Example
```php
$cars = array("Volvo", "BMW", "Toyota");
```
What is an Array?
An array is a special variable that can hold many values under a single name, and you can access the values by referring to an index number or name.

## PHP Array Types
- In PHP, there are three types of arrays:

- Indexed arrays - Arrays with a numeric index
- Associative arrays - Arrays with named keys
- Multidimensional arrays - Arrays containing one or more arrays

## Working With Arrays
- In this tutorial you will learn how to work with arrays, including:

- Create Arrays
- Access Arrays
- Update Arrays
- Add Array Items
- Remove Array Items

## Array Items
- items can be of any data type.

- The most common are strings and numbers (int, float), but array items can also be objects, functions or even arrays.

- You can have different data types in the same array.

## Example
- Array items of four different data types:
```php
$myArr = array("Volvo", 15, ["apples", "bananas"], myFunction);
```
## Array Functions
- The real strength of PHP arrays are the built-in array functions, like the count() function for counting array items:

## Example
- How many items are in the $cars array:
```php
$cars = array("Volvo", "BMW", "Toyota");
echo count($cars);
```

## PHP Indexed Arrays
- In indexed arrays each item has an index number.

- By default, the first item has index 0, the second item has item 1, etc

## Example
- Create and display an indexed array:
```php
$cars = array("Volvo", "BMW", "Toyota");
var_dump($cars);
```
## Access Indexed Arrays
- To access an array item you can refer to the index number.

## Example
- Display the first array item:
```php
$cars = array("Volvo", "BMW", "Toyota");
echo $cars[0];
```

## Change Value
- To change the value of an array item, use the index number:

## Example
- Change the value of the second item:
```php
$cars = array("Volvo", "BMW", "Toyota");
$cars[1] = "Ford";
var_dump($cars);
```

## Loop Through an Indexed Array
- To loop through and print all the values of an indexed array, you could use a foreach loop, like this:

## Example
- Display all array items:
```php
$cars = array("Volvo", "BMW", "Toyota");
foreach ($cars as $x) {
  echo "$x <br>";
}
```
## PHP Associative Arrays
- Associative arrays are arrays that use named keys that you assign to them
## Example
```php
$car = array("brand"=>"Ford", "model"=>"Mustang", "year"=>1964);
var_dump($car);
```

## Access Associative Arrays
- To access an array item you can refer to the key name.

## Example
- Display the model of the car:
```php
$car = array("brand"=>"Ford", "model"=>"Mustang", "year"=>1964);
echo $car["model"];
```

## Change Value
- To change the value of an array item, use the key name:

## Example
- Change the year item:
```php
$car = array("brand"=>"Ford", "model"=>"Mustang", "year"=>1964);
$car["year"] = 2024;
var_dump($car);
```

## Loop Through an Associative Array
- To loop through and print all the values of an associative array, you could use a foreach loop, like this:

## Example
- Display all array items, keys and values:
```php
$car = array("brand"=>"Ford", "model"=>"Mustang", "year"=>1964);

foreach ($car as $x => $y) {
  echo "$x: $y <br>";
}
```
## PHP Create Arrays


## Create Array
- You can create arrays by using the array() function:
## Example
```php
$cars = array("Volvo", "BMW", "Toyota");
```
- You can also use a shorter syntax by using the [] brackets:

## Example
```php
$cars = ["Volvo", "BMW", "Toyota"];
```

## Multiple Lines
- Line breaks are not important, so an array declaration can span multiple lines:

## Example
```php
$cars = [
  "Volvo",
  "BMW",
  "Toyota"
];
```
## Trailing Comma
- A comma after the last item is allowed:

## Example
```php
$cars = [
  "Volvo",
  "BMW",
  "Toyota",
];
```
## Array Keys
- When creating indexed arrays the keys are given automatically, starting at 0 and increased by 1 for each item, so the array above could also be created with keys:

## Example
```php
$cars = [
  0 => "Volvo",
  1 => "BMW",
  2 =>"Toyota"
];
```
- As you can see, indexed arrays are the same as associative arrays, but associative arrays have names instead of numbers:

## Example
```php
$myCar = [
  "brand" => "Ford",
  "model" => "Mustang",
  "year" => 1964
];
```
## Declare Empty Array
- You can declare an empty array first, and add items to it later:

## Example
```php
$cars = [];
$cars[0] = "Volvo";
$cars[1] = "BMW";
$cars[2] = "Toyota";
```
- The same goes for associative arrays, you can declare the array first, and then add items to it:

## Example
```php
$myCar = [];
$myCar["brand"] = "Ford";
$myCar["model"] = "Mustang";
$myCar["year"] = 1964;
```
## Mixing Array Keys
- You can have arrays with both indexed and named keys:

## Example
```php
$myArr = [];
$myArr[0] = "apples";
$myArr[1] = "bananas";
$myArr["fruit"] = "cherries";
```

## PHP Access Arrays

## Access Array Item
- To access an array item, you can refer to the index number for indexed arrays, and the key name for associative arrays.
## Example
- Access an item by referring to its index number:
  ```php
  $cars = array("Volvo", "BMW", "Toyota");
  echo $cars[2];
  ```
## Note: The first item has index 0.

- To access items from an associative array, use the key name:

## Example
- Access an item by referring to its key name:
```php
$cars = array("brand" => "Ford", "model" => "Mustang", "year" => 1964);
echo $cars["year"];
```
## Double or Single Quotes
- You can use both double and single quotes when accessing an array:

## Example
```php
echo $cars["model"];
echo $cars['model'];
```

## Excecute a Function Item
- Array items can be of any data type, including function.

- To execute such a function, use the index number followed by parentheses ():

## Example
- Execute a function item:
```php
function myFunction() {
  echo "I come from a function!";
}

$myArr = array("Volvo", 15, myFunction);

$myArr[2]();
```
- Use the key name when the function is an item in a associative array:

## Example
- Execute function by referring to the key name:
```php
function myFunction() {
  echo "I come from a function!";
}

$myArr = array("car" => "Volvo", "age" => 15, "message" => myFunction);

$myArr["message"]();
```
## Loop Through an Associative Array
- To loop through and print all the values of an associative array, you can use a foreach loop, like this:

## Example
- Display all array items, keys and values:
```php
$car = array("brand"=>"Ford", "model"=>"Mustang", "year"=>1964);

foreach ($car as $x => $y) {
  echo "$x: $y <br>";
}
```
## Loop Through an Indexed Array
- To loop through and print all the values of an indexed array, you can use a foreach loop, like this:

## Example
- Display all array items:
```php
$cars = array("Volvo", "BMW", "Toyota");
foreach ($cars as $x) {
  echo "$x <br>";
}
```

## PHP Update Array Items

## Update Array Item
- To update an existing array item, you can refer to the index number for indexed arrays, and the key name for associative arrays.

## Example
- Change the second array item from "BMW" to "Ford":
```php
$cars = array("Volvo", "BMW", "Toyota");
$cars[1] = "Ford";
```
## Note: The first item has index 0.

- To update items from an associative array, use the key name:

## Example
- Update the year to 2024:
```php
$cars = array("brand" => "Ford", "model" => "Mustang", "year" => 1964);
$cars["year"] = 2024;
```
## Update Array Items in a Foreach Loop
- There are different techniques to use when changing item values in a foreach loop.

- One way is to insert the & character in the assignment to assign the item value by reference, and thereby making sure that any changes done with the array item inside the loop will be done to the original array:

## Example
- Change ALL item values to "Ford":
```php
$cars = array("Volvo", "BMW", "Toyota");
foreach ($cars as &$x) {
  $x = "Ford";
}
unset($x);
var_dump($cars);
```
## Note: Remember to add the unset() function after the loop.

- Without the unset($x) function, the $x variable will remain as a reference to the last array item.

- To demonstrate this, see what happens when we change the value of $x after the foreach loop:

## Example
- Demonstrate the consequence of forgetting the unset() function:
```php
$cars = array("Volvo", "BMW", "Toyota");
foreach ($cars as &$x) {
  $x = "Ford";
}

$x = "ice cream";

var_dump($cars);
```

## PHP Add Array Items
## Add Array Item
- To add items to an existing array, you can use the bracket [] syntax.

## Example
- Add one more item to the fruits array:
```php
$fruits = array("Apple", "Banana", "Cherry");
$fruits[] = "Orange";
```
## Associative Arrays
- To add items to an associative array, or key/value array, use brackets [] for the key, and assign value with the = operator.

## Example
- Add one item to the car array:
```php
$cars = array("brand" => "Ford", "model" => "Mustang");
$cars["color"] = "Red";
```
## Add Multiple Array Items
- To add multiple items to an existing array, use the array_push() function.

## Example
- Add three item to the fruits array:
```php
$fruits = array("Apple", "Banana", "Cherry");
array_push($fruits, "Orange", "Kiwi", "Lemon");
```
## Add Multiple Items to Associative Arrays
- To add multiple items to an existing array, you can use the += operator.

## Example
- Add two items to the cars array:
```php
$cars = array("brand" => "Ford", "model" => "Mustang");
$cars += ["color" => "red", "year" => 1964];
```

## PHP Delete Array Items
## Remove Array Item
- To remove an existing item from an array, you can use the array_splice() function.

- With the array_splice() function you specify the index (where to start) and how many items you want to delete.

##Example
- Remove the second item:
```php
$cars = array("Volvo", "BMW", "Toyota");
array_splice($cars, 1, 1);
```
- After the deletion, the array gets reindexed automatically, starting at index 0.

## Using the unset Function
- You can also use the unset() function to delete existing array items.

- Note: The unset() function does not re-arrange the indexes, meaning that after deletion the array will no longer contain the missing indexes.

## Example
-Remove the second item:
```php
$cars = array("Volvo", "BMW", "Toyota");
unset($cars[1]);
```

## Remove Multiple Array Items
- To remove multiple items, the array_splice() function takes a length parameter that allows you to specify the number of items to delete.

## Example
Remove 2 items, starting a the second item (index 1):
```php
$cars = array("Volvo", "BMW", "Toyota");
array_splice($cars, 1, 2);
```
- The unset() function takes a unlimited number of arguments, and can therefore be used to delete multiple array items:

## Example
- Remove the first and the second item:
```php
$cars = array("Volvo", "BMW", "Toyota");
unset($cars[0], $cars[1]);
```
- Remove Item From an Associative Array
- To remove items from an associative array, you can use the unset() function.

- Specify the key of the item you want to delete.

## Example
- Remove the "model":
```php
$cars = array("brand" => "Ford", "model" => "Mustang", "year" => 1964);
unset($cars["model"]);
```
- Using the array_diff Function
- You can also use the array_diff() function to remove items from an associative array.

- This function returns a new array, without the specified items.

## Example
- Create a new array, without "Mustang" and "1964":
```php
$cars = array("brand" => "Ford", "model" => "Mustang", "year" => 1964);
$newarray = array_diff($cars, ["Mustang", 1964]);
```
- Note: The array_diff() function takes values as parameters, and not keys.

## Remove the Last Item
- The array_pop() function removes the last item of an array.

- Example
- Remove the last item:
```php
$cars = array("Volvo", "BMW", "Toyota");
array_pop($cars);
```
- Remove the First Item
- The array_shift() function removes the first item of an array.

## Example
- Remove the first item:
```php
$cars = array("Volvo", "BMW", "Toyota");
array_shift($cars);
```

## PHP Sorting Arrays
- The elements in an array can be sorted in alphabetical or numerical order, descending or ascending.

## PHP - Sort Functions For Arrays
- In this chapter, we will go through the following PHP array sort functions:

- sort() - sort arrays in ascending order
- rsort() - sort arrays in descending order
- asort() - sort associative arrays in ascending order, according to the value
- ksort() - sort associative arrays in ascending order, according to the key
- arsort() - sort associative arrays in descending order, according to the value
- krsort() - sort associative arrays in descending order, according to the key
## Sort Array in Ascending Order - sort()
  
- The following example sorts the elements of the $cars array in ascending alphabetical order:

## Example
```php
$cars = array("Volvo", "BMW", "Toyota");
sort($cars);
```
- The following example sorts the elements of the $numbers array in ascending numerical order:

## Example
```PHP
$numbers = array(4, 6, 2, 22, 11);
sort($numbers);
```

## Sort Array in Descending Order - rsort()
- The following example sorts the elements of the $cars array in descending alphabetical order:

## Example
```
$cars = array("Volvo", "BMW", "Toyota");
rsort($cars);
```
- The following example sorts the elements of the $numbers array in descending numerical order:

## Example
```PHP
$numbers = array(4, 6, 2, 22, 11);
rsort($numbers);
```
## Sort Array (Ascending Order), According to Value - asort()
- The following example sorts an associative array in ascending order, according to the value:

## Example
```PHP
$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
asort($age);
```
## Sort Array (Ascending Order), According to Key - ksort()
- The following example sorts an associative array in ascending order, according to the key:

## Example
```PHP
$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
ksort($age);
```
## Sort Array (Descending Order), According to Value - arsort()
- The following example sorts an associative array in descending order, according to the value:

## Example
```PHP
$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
arsort($age);
```
## Sort Array (Descending Order), According to Key - krsort()
- The following example sorts an associative array in descending order, according to the key:

## Example
```PHP
$age = array("Peter"=>"35", "Ben"=>"37", "Joe"=>"43");
krsort($age);
```
## PHP Multidimensional Arrays
- In the previous pages, we have described arrays that are a single list of key/value pairs.

- However, sometimes you want to store values with more than one key. For this, we have multidimensional arrays.

## PHP - Multidimensional Arrays
- A multidimensional array is an array containing one or more arrays.

- PHP supports multidimensional arrays that are two, three, four, five, or more levels deep. However, arrays more than three levels deep are hard to manage for most people.

- The dimension of an array indicates the number of indices you need to select an element.

- For a two-dimensional array you need two indices to select an element
- For a three-dimensional array you need three indices to select an element
## PHP - Two-dimensional Arrays
## PHP - Two-dimensional Arrays
- A two-dimensional array is an array of arrays (a three-dimensional array is an array of arrays of arrays).

- First, take a look at the following table:

| Name        | Stock | Sold |
|-------------|-------|------|
| Volvo       | 22    | 18   |
| BMW         | 15    | 13   |
| Saab        | 5     | 2    |
| Land Rover  | 17    | 15   |

- We can store the data from the table above in a two-dimensional array, like this:
```php
$cars = array (
  array("Volvo",22,18),
  array("BMW",15,13),
  array("Saab",5,2),
  array("Land Rover",17,15)
);
```

- Now the two-dimensional $cars array contains four arrays, and it has two indices: row and column.

- To get access to the elements of the $cars array we must point to the two indices (row and column):

## Example
```php
echo $cars[0][0].": In stock: ".$cars[0][1].", sold: ".$cars[0][2].".<br>";
echo $cars[1][0].": In stock: ".$cars[1][1].", sold: ".$cars[1][2].".<br>";
echo $cars[2][0].": In stock: ".$cars[2][1].", sold: ".$cars[2][2].".<br>";
echo $cars[3][0].": In stock: ".$cars[3][1].", sold: ".$cars[3][2].".<br>";
```
- We can also put a for loop inside another for loop to get the elements of the $cars array (we still have to point to the two indices):

## Example
```php
for ($row = 0; $row < 4; $row++) {
  echo "<p><b>Row number $row</b></p>";
  echo "<ul>";
    for ($col = 0; $col < 3; $col++) {
      echo "<li>".$cars[$row][$col]."</li>";
    }
  echo "</ul>";
}
```

## PHP Array Functions
## PHP Array Functions
- PHP has a set of built-in functions that you can use on arrays.

| **Function**               | **Description**                                                                                              |
|----------------------------|----------------------------------------------------------------------------------------------------------|
| `array()`                  | Creates an array                                                                                         |
| `array_change_key_case()`  | Changes all keys in an array to lowercase or uppercase                                                   |
| `array_chunk()`            | Splits an array into chunks of arrays                                                                    |
| `array_column()`           | Returns the values from a single column in the input array                                               |
| `array_combine()`          | Creates an array by using the elements from one "keys" array and one "values" array                      |
| `array_count_values()`     | Counts all the values of an array                                                                        |
| `array_diff()`             | Compare arrays, and returns the differences (compare values only)                                        |
| `array_diff_assoc()`       | Compare arrays, and returns the differences (compare keys and values)                                    |
| `array_diff_key()`         | Compare arrays, and returns the differences (compare keys only)                                          |
| `array_diff_uassoc()`      | Compare arrays, and returns the differences (compare keys and values, using a user-defined key comparison function) |
| `array_diff_ukey()`        | Compare arrays, and returns the differences (compare keys only, using a user-defined key comparison function) |
| `array_fill()`             | Fills an array with values                                                                               |
| `array_fill_keys()`        | Fills an array with values, specifying keys                                                              |
| `array_filter()`           | Filters the values of an array using a callback function                                                 |
| `array_flip()`             | Flips/Exchanges all keys with their associated values in an array                                        |
| `array_intersect()`        | Compare arrays, and returns the matches (compare values only)                                           |
| `array_intersect_assoc()`  | Compare arrays and returns the matches (compare keys and values)                                         |
| `array_intersect_key()`    | Compare arrays, and returns the matches (compare keys only)                                             |
| `array_intersect_uassoc()` | Compare arrays, and returns the matches (compare keys and values, using a user-defined key comparison function) |
| `array_intersect_ukey()`   | Compare arrays, and returns the matches (compare keys only, using a user-defined key comparison function) |
| `array_key_exists()`       | Checks if the specified key exists in the array                                                         |
| `array_keys()`             | Returns all the keys of an array                                                                        |
| `array_map()`              | Sends each value of an array to a user-made function, which returns new values                          |
| `array_merge()`            | Merges one or more arrays into one array                                                                |
| `array_merge_recursive()`  | Merges one or more arrays into one array recursively                                                    |
| `array_multisort()`        | Sorts multiple or multi-dimensional arrays                                                              |
| `array_pad()`              | Inserts a specified number of items, with a specified value, to an array                                |
| `array_pop()`              | Deletes the last element of an array                                                                    |
| `array_product()`          | Calculates the product of the values in an array                                                       |
| `array_push()`             | Inserts one or more elements to the end of an array                                                    |
| `array_rand()`             | Returns one or more random keys from an array                                                          |
| `array_reduce()`           | Returns an array as a string, using a user-defined function                                            |
| `array_replace()`          | Replaces the values of the first array with the values from following arrays                            |
| `array_replace_recursive()`| Replaces the values of the first array with the values from following arrays recursively                |
| `array_reverse()`          | Returns an array in the reverse order                                                                  |
| `array_search()`           | Searches an array for a given value and returns the key                                                |
| `array_shift()`            | Removes the first element from an array, and returns the value of the removed element                  |
| `array_slice()`            | Returns selected parts of an array                                                                     |
| `array_splice()`           | Removes and replaces specified elements of an array                                                    |
| `array_sum()`              | Returns the sum of the values in an array                                                              |
| `array_udiff()`            | Compare arrays, and returns the differences (compare values only, using a user-defined key comparison function) |
| `array_udiff_assoc()`      | Compare arrays, and returns the differences (compare keys and values, using a built-in function to compare the keys and a user-defined function to compare the values) |
| `array_udiff_uassoc()`     | Compare arrays, and returns the differences (compare keys and values, using two user-defined key comparison functions) |
| `array_uintersect()`       | Compare arrays, and returns the matches (compare values only, using a user-defined key comparison function) |
| `array_uintersect_assoc()` | Compare arrays, and returns the matches (compare keys and values, using a built-in function to compare the keys and a user-defined function to compare the values) |
| `array_uintersect_uassoc()`| Compare arrays, and returns the matches (compare keys and values, using two user-defined key comparison functions) |
| `array_unique()`           | Removes duplicate values from an array                                                                |
| `array_unshift()`          | Adds one or more elements to the beginning of an array                                                |
| `array_values()`           | Returns all the values of an array                                                                    |
| `array_walk()`             | Applies a user function to every member of an array                                                   |
| `array_walk_recursive()`   | Applies a user function recursively to every member of an array                                       |
| `arsort()`                 | Sorts an associative array in descending order, according to the value                                |
| `asort()`                  | Sorts an associative array in ascending order, according to the value                                 |
| `compact()`                | Create array containing variables and their values                                                   |
| `count()`                  | Returns the number of elements in an array                                                           |
| `current()`                | Returns the current element in an array                                                              |
| `each()`                   | Deprecated from PHP 7.2. Returns the current key and value pair from an array                         |
| `end()`                    | Sets the internal pointer of an array to its last element                                            |
| `extract()`                | Imports variables into the current symbol table from an array                                        |
| `in_array()`               | Checks if a specified value exists in an array                                                      |
| `key()`                    | Fetches a key from an array                                                                          |
| `krsort()`                 | Sorts an associative array in descending order, according to the key                                 |
| `ksort()`                  | Sorts an associative array in ascending order, according to the key                                  |
| `list()`                   | Assigns variables as if they were an array                                                          |
| `natcasesort()`            | Sorts an array using a case insensitive "natural order" algorithm                                    |
| `natsort()`                | Sorts an array using a "natural order" algorithm                                                    |
| `next()`                   | Advance the internal array pointer of an array                                                      |
| `pos()`                    | Alias of current()                                                                                  |
| `prev()`                   | Rewinds the internal array pointer                                                                  |
| `range()`                  | Creates an array containing a range of elements                                                    |
| `reset()`                  | Sets the internal pointer of an array to its first element                                          |
| `rsort()`                  | Sorts an indexed array in descending order                                                         |
| `shuffle()`                | Shuffles an array                                                                                   |
| `sizeof()`                 | Alias of count()                                                                                    |
| `sort()`                   | Sorts an indexed array in ascending order                                                          |
| `uasort()`                 | Sorts an array by values using a user-defined comparison function and maintains the index association |
| `uksort()`                 | Sorts an array by keys using a user-defined comparison function                                     |
| `usort()`                  | Sorts an array by values using a user-defined comparison function                                   |


## PHP Global Variables - Superglobals
- Superglobals were introduced in PHP 4.1.0, and are built-in variables that are always available in all scopes.

## PHP Global Variables - Superglobals
- Some predefined variables in PHP are "superglobals", which means that they are always accessible, regardless of scope - and you can access them from any function, class or file without having to do anything special.

## The PHP superglobal variables are:

- $GLOBALS
- $_SERVER
- $_REQUEST
- $_POST
- $_GET
- $_FILES
- $_ENV
- $_COOKIE
- $_SESSION
  
- The next chapters will explain some of the superglobals, and the rest will be explained in later chapters

## PHP $GLOBALS
- $GLOBALS is an array that contains all global variables.

## Global Variables
- Global variables are variables that can be accessed from any scope.

- Variables of the outer most scope are automatically global variables, and can be used by any scope, e.g. inside a function.

- To use a global variable inside a function you have to either define them as global with the global keyword, or refer to them by using the $GLOBALS syntax.

## Example
- Refer to the global variable $x inside a function:
```php
$x = 75;
  
function myfunction() {
  echo $GLOBALS['x'];
}

myfunction()
```
- This is different from other programming languages where global variables are available without specifically referring to them as global.

## Example
- In PHP you get nothing (or an error) when referring to a global variable without the $GLOBALS syntax:
```php
$x = 75;
  
function myfunction() {
  echo $x;
}

myfunction()
```
- You can also refer to global variables inside functions by defining them as global with the global keyword.

## Example
- Define $x as global inside a function:
```php
$x = 75;
  
function myfunction() {
  global $x;
  echo $x;
}

myfunction()
```
## Create Global Variables
- Variables created in the outer most scope are global variables either if they are created using the $GLOBALS syntax or not:

## Example
```php
$x = 100;

echo $GLOBALS["x"];
echo $x;
```
- Variables created inside a function belongs only to that function, but you can create global variables inside a function by using the $GLOBALS syntax:

## Example

- Create a global variable from inside a function, and use it outside of the function:
```php
function myfunction() {
  $GLOBALS["x"] = 100;
}

myfunction();

echo $GLOBALS["x"];
echo $x;
```
## PHP - $_SERVER
- $_SERVER
- $_SERVER is a PHP super global variable which holds information about headers, paths, and script locations.

- The example below shows how to use some of the elements in $_SERVER:

## Example
```php
echo $_SERVER['PHP_SELF'];
echo $_SERVER['SERVER_NAME'];
echo $_SERVER['HTTP_HOST'];
echo $_SERVER['HTTP_REFERER'];
echo $_SERVER['HTTP_USER_AGENT'];
echo $_SERVER['SCRIPT_NAME'];
```

## $_SERVER Elements

The following table lists the most important elements that can go inside `$_SERVER`:

| Element/Code                    | Description                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| `$_SERVER['PHP_SELF']`           | Returns the filename of the currently executing script                      |
| `$_SERVER['GATEWAY_INTERFACE']` | Returns the version of the Common Gateway Interface (CGI) the server is using |
| `$_SERVER['SERVER_ADDR']`        | Returns the IP address of the host server                                    |
| `$_SERVER['SERVER_NAME']`        | Returns the name of the host server (such as www.w3schools.com)             |
| `$_SERVER['SERVER_SOFTWARE']`    | Returns the server identification string (such as Apache/2.2.24)            |
| `$_SERVER['SERVER_PROTOCOL']`    | Returns the name and revision of the information protocol (such as HTTP/1.1) |
| `$_SERVER['REQUEST_METHOD']`     | Returns the request method used to access the page (such as POST)           |
| `$_SERVER['REQUEST_TIME']`       | Returns the timestamp of the start of the request (such as 1377687496)      |
| `$_SERVER['QUERY_STRING']`       | Returns the query string if the page is accessed via a query string         |
| `$_SERVER['HTTP_ACCEPT']`        | Returns the Accept header from the current request                          |
| `$_SERVER['HTTP_ACCEPT_CHARSET']`| Returns the Accept_Charset header from the current request (such as utf-8,ISO-8859-1) |
| `$_SERVER['HTTP_HOST']`          | Returns the Host header from the current request                            |
| `$_SERVER['HTTP_REFERER']`       | Returns the complete URL of the current page (not reliable because not all user-agents support it) |
| `$_SERVER['HTTPS']`              | Is the script queried through a secure HTTP protocol                        |
| `$_SERVER['REMOTE_ADDR']`        | Returns the IP address from where the user is viewing the current page      |
| `$_SERVER['REMOTE_HOST']`        | Returns the Host name from where the user is viewing the current page      |
| `$_SERVER['REMOTE_PORT']`        | Returns the port being used on the user's machine to communicate with the web server |
| `$_SERVER['SCRIPT_FILENAME']`    | Returns the absolute pathname of the currently executing script            |
| `$_SERVER['SERVER_ADMIN']`       | Returns the value given to the SERVER_ADMIN directive in the web server configuration file (such as someone@w3schools.com) |
| `$_SERVER['SERVER_PORT']`        | Returns the port on the server machine being used by the web server for communication (such as 80) |
| `$_SERVER['SERVER_SIGNATURE']`   | Returns the server version and virtual host name which are added to server-generated pages |
| `$_SERVER['PATH_TRANSLATED']`    | Returns the file system-based path to the current script                    |
| `$_SERVER['SCRIPT_NAME']`        | Returns the path of the current script                                      |
| `$_SERVER['SCRIPT_URI']`         | Returns the URI of the current page                                         |



## PHP - $_REQUEST
- $_REQUEST
- $_REQUEST is a PHP super global variable which contains submitted form data, and all cookie data.

- In other words, $_REQUEST is an array containing data from $_GET, $_POST, and $_COOKIE.

- You can access this data with the $_REQUEST keyword followed by the name of the form field, or cookie, like this:
```php
$_REQUEST['firstname']
```
- Using $_REQUEST on $_POST Requests
- POST request are usually data submitted from an HTML form.

- Here is an example of how a HTML form could look like:

- HTML form
```php
<html>
<body>

<form method="post" action="demo_request.php">
  Name: <input type="text" name="fname">
  <input type="submit">
</form>

</body>
</html>
```
- When a user clicks the submit button, the form data is sent to a PHP file specified in the action attribute of the <form> tag.

- In the action file we can use the $_REQUEST variable to collect the value of the input field.

## PHP file

```php
$name = $_REQUEST['fname'];
echo $name;
```
- In the example below we have put the HTML form and PHP code in the same PHP file.

- We have also added some extra lines for security.

## Example
```php
<html>
<body>

<form method="post" action="<?php echo $_SERVER['PHP_SELF'];?>">
  Name: <input type="text" name="fname">
  <input type="submit">
</form>

<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
  $name = htmlspecialchars($_REQUEST['fname']);
  if (empty($name)) {
    echo "Name is empty";
  } else {
    echo $name;
  }
}
?>

</body>
</html>
```
## Using $_REQUEST on $_GET Requests
- GET request can be form submissions as in the example above, with the method attribute of the HTML <form> element set to GET.

- GET requests can also be data from a query string (information added after a URL address).

- Here is an example of how an HTML hyperlink, with a query string could look like:

## HTML link
```php
<html>
<body>

<a href="demo_phpfile.php?subject=PHP&web=W3schools.com">Test $GET</a>

</body>
</html>
```
- When a user clicks the link, the query string data is sent to demo_phpfile.php.

- In the PHP file we can use the $_REQUEST variable to collect the value of the query string.

## Example
- The PHP file demo_phpfile.php:
```php
<html>
<body>

<?php
echo "Study " . $_REQUEST['subject'] . " at " . $_REQUEST['web'];
?>

</body>
</html>
```

## PHP - $_POST
- PHP $_POST
- $_POST contains an array of variables received via the HTTP POST method.

- There are two main ways to send variables via the HTTP Post method:

## HTML forms
- JavaScript HTTP requests
- $_POST in HTML Forms
- A HTML form submits information via the HTTP POST method if the form's method attribute is set to "POST".

- To demonstrate this, we start by creating a simple HTML form:

## HTML Form
```php
<html>
<body>

<form method="POST" action="demo_request.php">
  Name: <input type="text" name="fname">
  <input type="submit">
</form>

</body>
</html>
```
- When a user clicks the submit button, the form data is sent to a PHP file specified in the action attribute of the <form> tag.

- In the action file we can use the $_POST variable to collect the value of the input field.

## PHP file
```php
$name = $_POST['fname'];
echo $name;
```
- In the example below we have put the HTML form and PHP code in the same PHP file.

- We have also added some extra lines for security.

## Example
```php
<html>
<body>

<form method="POST" action="<?php echo $_SERVER['PHP_SELF'];?>">
  Name: <input type="text" name="fname">
  <input type="submit">
</form>

<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
  $name = htmlspecialchars($_POST['fname']);
  if (empty($name)) {
    echo "Name is empty";
  } else {
    echo $name;
  }
}
?>

</body>
</html>
```
- $_POST in JavaScript HTTP Requests
- When sending a HTTP request in JavaScript, you can specify that the HTTP method is POST.

- To demonstrate this we start by creating a JavaScript function containing a HTTP request:

## JavaScript function
```php
function myfunction() {
  const xhttp = new XMLHttpRequest();
  xhttp.open("POST", "demo_phpfile.php");
  xhttp.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
  xhttp.onload = function() {
    document.getElementById("demo").innerHTML = this.responseText;
  }
  xhttp.send("fname=Mary");
  }
}
```
- The code above will:

- Intiate a HTTP request
- Set the HTTP method to POST
- Set a valid request header
- Create a function to execute when the request is done
- Send the HTTP request with a variable fname set to Mary
- Look at the function that will be executed when the request is done:
```php
xhttp.onload = function() {
    document.getElementById("demo").innerHTML = this.responseText;
  }
```
- It will try to write a response from the operation in a HTML element with id="demo".

- Let us make a HTML page with such element, and also a button that executes the function.

- If we also add the the JavaScript, the page looks like this:

## Example
- How to post and receive data from a HTTP request:
```php
<html>
<script>
function myfunction() {
  const xhttp = new XMLHttpRequest();
  xhttp.open("POST", "demo_ajax.php");
  xhttp.setRequestHeader("Content-type", "application/x-www-form-urlencoded");
  xhttp.onload = function() {
    document.getElementById("demo").innerHTML = this.responseText;
  }
  xhttp.send("fname=Mary");
  }
}
</script>
<body>

<button onclick="myfunction()">Click me!</button>

<h1 id="demo"></h1>

</body>
</html>
```
- In the PHP file that receive this HTTP request (demo_ajax.php), we simply use the $_POST variable to retrieve the fname variable, and writes it as a response.

## PHP file
```php
$name = $_POST['fname'];
echo $name;
```
## PHP Superglobal - $_GET

## PHP $_GET
- $_GET contains an array of variables received via the HTTP GET method.

- There are two main ways to send variables via the HTTP GET method:

- Query strings in the URL
- HTML Forms

## Query string in the URL
- A query string is data added at the end of a URL. In the link below, everything after the ? sign is part of the query string:
```php
<a href="demo_phpfile.php?subject=PHP&web=W3schools.com">Test $GET</a>
```
- The query string above contains two key/value pairs:
```php
subject=PHP
web=W3schools.com
```
- In the PHP file we can use the $_GET variable to collect the value of the query string.

## Example
- The PHP file demo_phpfile.php:
```php
<html>
<body>

<?php
echo "Study " . $_GET['subject'] . " at " . $_GET['web'];
?>

</body>
</html>
```

## $_GET in HTML Forms
- A HTML form submits information via the HTTP GET method if the form's method attribute is set to "GET".

- To demonstrate this, we start by creating a simple HTML form:

```php
HTML Form

<html>
<body>

<form action="welcome_get.php" method="GET">
  Name: <input type="text" name="name">
  E-mail: <input type="text" name="email">
  <input type="submit">
</form>

</body>
</html>
```
- When a user clicks the submit button, the form data is sent to a PHP file specified in the action attribute of the <form> tag.

- The form fields are sent to the PHP file, with your input, as query strings:

```php
welcome_get.php?name=John&email=john@example.com
```
- In the action file we can use the $_GET variable to collect the value of the input fields.

## Example
- PHP code inside the welcome_get.php page:
```PHP
<html>
<body>

Welcome <?php echo $_GET["name"]; ?><br>
Your email address is: <?php echo $_GET["email"]; ?>

</body>
</html>
```
## PHP Regular Expressions
## What is a Regular Expression?
- A regular expression is a sequence of characters that forms a search pattern. When you search for data in a text, you can use this search pattern to describe what you are searching for.

- A regular expression can be a single character, or a more complicated pattern.

- Regular expressions can be used to perform all types of text search and text replace operations.

## Syntax
- In PHP, regular expressions are strings composed of delimiters, a pattern and optional modifiers.
```php
$exp = "/w3schools/i";
```
- In the example above, / is the delimiter, w3schools is the pattern that is being searched for, and i is a modifier that makes the search case-insensitive.

- The delimiter can be any character that is not a letter, number, backslash or space. The most common delimiter is the forward slash (/), but when your pattern contains forward slashes it is convenient to choose other delimiters such as # or ~.

## Regular Expression Functions
- PHP provides a variety of functions that allow you to use regular expressions.

- The most common functions are:
  
| Function | Description |
|---------------|------------------------------------------------------------|
| `preg_match()` | Returns 1 if the pattern was found in the string, and 0 if not |
| `preg_match_all()` | Returns the number of times the pattern was found in the string, which may also be 0 |
| `preg_replace()` | Returns a new string where matched patterns have been replaced with another string |



## Using preg_match()
- The preg_match() function will tell you whether a string contains matches of a pattern.

## Example
- Use a regular expression to do a case-insensitive search for "w3schools" in a string:
```php
$str = "Visit W3Schools";
$pattern = "/w3schools/i";
echo preg_match($pattern, $str);
```
## Using preg_match_all()
- The preg_match_all() function will tell you how many matches were found for a pattern in a string.

## Example
- Use a regular expression to do a case-insensitive count of the number of occurrences of "ain" in a string:
```php
$str = "The rain in SPAIN falls mainly on the plains.";
$pattern = "/ain/i";
echo preg_match_all($pattern, $str);
```
## Using preg_replace()
- The preg_replace() function will replace all of the matches of the pattern in a string with another string.

## Example
- Use a case-insensitive regular expression to replace Microsoft with W3Schools in a string:
```php
$str = "Visit Microsoft!";
$pattern = "/microsoft/i";
echo preg_replace($pattern, "W3Schools", $str);
```

## Regular Expression Modifiers
| Modifier | Description |
|----------|-------------|
| `i` | Performs a case-insensitive search |
| `m` | Performs a multiline search (matches beginning or end of each line) |
| `u` | Enables correct matching of UTF-8 encoded patterns |

## Regular Expression Patterns
| Expression | Description |
|------------|-------------|
| `[abc]` | Find one or many of the characters inside the brackets |
| `[^abc]` | Find any character NOT between the brackets |
| `[a-z]` | Find any character alphabetically between two letters |
| `[A-z]` | Find any character alphabetically between a specified upper-case and lower-case letter |
| `[A-Z]` | Find any character alphabetically between two upper-case letters |
| `[123]` | Find one or many of the digits inside the brackets |
| `[0-5]` | Find any digits between the two numbers |
| `[0-9]` | Find any digits |

## Metacharacters
| Metacharacter | Description |
|--------------|-------------|
| `|` | Find a match for any one of the patterns separated by `|`, e.g., `cat|dog|fish` |
| `.` | Find any character |
| `^` | Finds a match at the beginning of a string, e.g., `^Hello` |
| `$` | Finds a match at the end of the string, e.g., `World$` |
| `\d` | Find any digits |
| `\D` | Find any non-digits |
| `\s` | Find any whitespace character |
| `\S` | Find any non-whitespace character |
| `\w` | Find any alphabetical letter (a to Z) and digit (0 to 9) |
| `\W` | Find any non-alphabetical and non-digit character |
| `\b` | Find a match at the beginning or end of a word, e.g., `\bWORD` or `WORD\b` |
| `\uxxxx` | Find the Unicode character specified by the hexadecimal number `xxxx` |

## Quantifiers
| Quantifier | Description |
|------------|-------------|
| `n+` | Matches any string that contains at least one `n` |
| `n*` | Matches any string that contains zero or more occurrences of `n` |
| `n?` | Matches any string that contains zero or one occurrences of `n` |
| `n{3}` | Matches any string that contains a sequence of exactly 3 `n`'s |
| `n{2,5}` | Matches any string that contains a sequence of at least 2, but not more than 5 `n`'s |
| `n{3,}` | Matches any string that contains a sequence of at least 3 `n`'s |


## Grouping
- You can use parentheses ( ) to apply quantifiers to entire patterns. They also can be used to select parts of the pattern to be used as a match.

## Example..
- Use grouping to search for the word "banana" by looking for ba followed by two instances of na:
```php
$str = "Apples and bananas.";
$pattern = "/ba(na){2}/i";
echo preg_match($pattern, $str);
```
