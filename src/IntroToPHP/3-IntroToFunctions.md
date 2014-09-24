% Intro To Functions
% Dr. Andrew Besmer

# Functions

## Function

* Functions help make reusable code
* A function can be written once and used over and over
* Functions have a specific purpose like add two numbers
* Functions can take 0, 1, or more arguments
* Functions may, but does not have to, return a value
* You call (or invoke) a function by providing it arguments

## Function

* `isset()` is a function that takes one argument
* The argument passed to it will be checked
	* Returns `true` if set
	* Returns `false` if not

```php
isset($_POST["applyTax"]);
```

## Function

* `is_numeric()` takes an argument and checks it to see if it is numeric
	* `true` if it is some sort of number
	* `false` if it is not
* It does not change the variables type if it is
* Example [^PHP]

[^PHP]: [PHP](http://php.net)

```php
<?php
$tests = array(
	"42",
	1337,
	0x539,
	02471,
	0b10100111001,
	1337e0,
	"not numeric",
	array(),
	9.1
);
``` 

## Function

* `is_int()` takes an argument and checks it to see if it is an integer
* Again, it does not change the data type
* Example[^PHP]

```php
$tests = array(
	23,
	"23",
	23.5,
	"23.5",
	null,
	true,
	false
);
```

## Function

* Others
	* `is_bool()`
	* `is_float()`
	* `is_numeric()`
	* `is_string()`
	* `is_array()`
	* `is_object()`
* These are all useful to check the actual data type
* All `$_GET` and `$_POST` are provided as a string

# Misc 

## var_dump
* `var_dump()` takes an argument and outputs it to the screen

```php
<?php
var_dump($_SERVER); //Server is another super global
```

## Ternery

* `?` is called a ternary operator
* `:` indicates the separation of true/false values in the ternary

```php
conditional_expression ? true_value : false_value
```

## Ternary Application

* Useful for short handing certain conditional logic

```php
if (isset($_POST["taxRate"]) == true)
{
	$tax = $_POST["taxRate"];
}
else
{
	$tax = 0.00;
}

//Equivalent to

$tax = isset($_POST["taxRate"]) ? $_POST["taxRate"] : 0.00;
```


