# PHP-Tutorial

- PHP is a server scripting language, and a powerful tool for making dynamic and interactive Web pages.

- PHP is a widely-used, free, and efficient alternative to competitors such as Microsoft's ASP.

## Example PHP Script

```html
<!DOCTYPE html>
<html>
<body>
 
<?php
echo "My first PHP script!";
?>

</body>
</html>

```
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
  
```html
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

 
```html
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
```html
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

```html
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

```
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

```html
echo "Welcome Home!";
```
## Example
-- A comment at the end of a line:

```html
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

```html
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
```html
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
```
$txt = "W3Schools.com";
echo "I love $txt!";
```

