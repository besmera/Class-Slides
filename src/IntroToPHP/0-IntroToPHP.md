% Intro to PHP
% Dr. Andrew Besmer

# About PHP

## The Language
PHP
:   PHP Hypertext Preprocessor
<br />

* Recursive acronym
* Open source
* Available on most OS

## Similarities
* Code similar to
	* C
	* Java
	* Perl
* Take some concepts with you or reuse existing
* Used to write dynamic server side web apps
	* Can be used to make cli scripts
* Loosely typed

# PHP mode

## PHP mode
* Can go into "PHP mode" by using the start tag `<?php` 
* You can exit by using the end tag `?>`
```php
<?php
	//PHP mode
?>
```
* Everything inside these tags is code to be run on the server

## PHP mode
* PHP is most frequently combined with HTML/CSS/JS for making web apps
```php
<!DOCTYPE html>
<html>
	<head>
		<title>First App</title>
	</head>
	<body>
		<?php echo "Hi CSCI241!"; ?>
	</body>
</html>
```
* Can be used to do many other things
	* Generate PNG/JPG 
	* Generate JSON/XML
	* Generate PDF

# Variables

## Variables
Variable
:   Reference to a storage location in main memory (RAM) who's value can change.

* Which would you rather? 
```cpp
0x00BAB10C
```
```php
$uberBlock
```
* Variables hold one value at a time


<div class="notes">

</div>


