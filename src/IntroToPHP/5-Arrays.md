% Arrays
% Dr. Andrew Besmer

# Arrays

## About Arrays

* What if you needed to average all of the grades for a student in a class?  One posibility is:

```php
<?php

$grade1 = 88;
$grade2 = 92;
$grade3 = 75;
...
...
$gradeN = 97;
```

* What sort of issues would this have?

## About Arrays

* Arrays can hold multiple values
	* Lend themselves well to looping structures we have learned
	* It's not required to know how many you need to store at the time of development
* PHP arrays allow values of different types to be stored
	* Not limited to only `integer` or only `float`
* Arrays in PHP are allowed to be either sequential or associative, lets look at sequential

## Sequential Arrays

* Lets look at storing the students grades in an array
* Observe 
	* Structure
	* Indexing
	* Retrieval
	* Properties

## Creating Arrays

* Use `array()` to create arrays
	* Pass your values each separated by a comma
	* Optionally specify a 'key'
* Optionally use `[]` for assigning one at a time

```php
<?php

$grades = array(88, 92, 75, 97);
```

or

```php
<?php

$grades[] = 88;
$grades[] = 92;
$grades[] = 75;
$grades[] = 97;
```


