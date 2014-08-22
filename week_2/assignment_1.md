# Week 2 - Assignment #1

##Functions

### Exercise #1

__Title File: hw_wk2_p1.php__

_Please look up the date function to help_

1. Create a function called daysOfMonth.
2. Make sure you are able to pass a month e.g. 'January' to the function. Note: Leap year does not exist. (Lookup date function in php).
3. Use other months to test your function.

Expected output:

```
January has 31 days in it.
February has 28 days in it. (Unless it is leap year, then return 29)
	and so on...
```

### Exercise #2

__Title File: hw_wk2_p2.php__

1. Create a function the returns the area of a circle.
2. Now create a function that returns the area of a donut; use your previous function to figure this out.
3. The radius of the donut is 15 and the radius of its hole is 5.

### Exercise #3

__Title file: h2_wk2_p3.php__

You will need to create a function called __listCars()__ that excepts an array parameter. The function should return each car in the array like the example in the output section.

You have the following array:

```
$cars = array(
	'Toyota Solara' => array(
		'year' => 2001,
		'doors' => 2,
		'color' => 'gray',
		'mileage' => 100000,
		'sunroof' => true,
		'convertable' = false,
		'license' => 'JSRULZ',
	),

	'Honda Odyssey' => array(
		'year' => 2004, 
		'doors' => 4,
		'color' => 'marron',
		'mileage' => 60000,
		'sunroof' => false,
		'convertable' = false,
		'license' => 'ILUVPHP',
	),

	'Cadillac Escalade' => array(
		'year' => 2014,
		'doors' => 4,
		'color' => 'white',
		'mileage' => 5000,
		'sunroof' => false,
		'convertable' = false,
		'license' => 'HTML5',
	),

);
```
Create a function that outputs the following:

```
I own a 2014 Cadillac Escalade. Details below:
------------------------------------------------
4 Door 2014 Cadillac Escalade
Color: white
Milelage: 5000
Sunroof: N/A
Convertable: N/A
Lincense NO: HTML5
```
Now create a function called __add_car()__ that allows you to add cars to the array and now call __listCars()__ so you are able to output with the new added car.

### Exercise 4

Take the functions from the previous Exercise #3 and add two new functions to the script called __save_to_file()__. Each of these functions will need a parameter passed that allows the user to input a text filename.

Save to file should save the car list as outputed to the file.