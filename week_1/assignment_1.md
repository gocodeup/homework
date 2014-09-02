# Week 1 - Assignment #1

### Exercise #1 - Command Line
With the command line, you can access your computer without having to go through your Finder. Here you have the ability to see what your computer contains and also manipulate it according to what you want to accomplish. This is a very powerful tool.
This entire exercise must be completed through the terminal.

Reference: cli.learncodethehardway.org/book/

1. On your __Mac terminal__, check what directory you are currently in. What do you see? In your own words explain this output.
2.  List out your directory to see it's contents. In this directory:
	a. Make a new directory and name it navigator.
	b. Change directories into __navigator__ within this directory, make another directory and call it __fligh_of_the__.
	c. Inside __flight_of_the__, create an empty file called: __Trimaxion.txt__. Change directories into __Trimaxion.txt__, what happens? What does the computer tell you and why?
	d. Next, open __Trimaxion.txt__ with sublime through the command line.
		Add the following text:
		
		"Flight of the Navigator is a 1986 comic science fiction film directed by Randal Kleiser and written by Mark H. Baker and Michael Burton, about a 12-year-old boy named David who is abducted by an alien spacecraft and finds himself caught in a world that has changed around him." 
		
	e. Using the keyboard, save and close sublime. Switch back to your terminal and create another empty file within __flight_of_the__ directory called __Max.txt__.
	f. Copy the __Trimaxion.txt__ file to the __Max.txt__ file. Now open __Max.txt__ through the command line with sublime. What do you see?
	g. Switch back to the command line and let's remove the __Max.txt__ file. Use find to see what is inside of the directory. Don't forget to use your reference source for the correct syntax for the command line.
	h. Now open a new tab in your terminal and change directories into your vagrant-lamp.
	
		1. Check to see if your vagrant is running.
		2. If it's not running, start your vagrant.
		3. Get inside your securtiy shell. Why do we get inside our security shell?
			a. List out your directories and change directories into your exercises.
			
			b. You've made a coupld text files already. Use the find command to learn which text files they are.
			
		4. Now get out of your security shell and get inside your interactive shell. What is the purpose of using your interactive shell?
		5. Now lets stop our vagrant from running. Look up the difference between halt and suspend for vagrant. Which one does what and why do we use it? Write this down.
		
	i. Exit completely out of your terminal. Name the two ways to exit your terminal.
	
	Bonus: If your terminal just keeps running and running on an infinite loop, what command can you use to make it stop? 

### Exercise #3 - Variable Assignment

1. In the REPL (read–eval–print loop) create a variable $age and set it equal to an integer of your age.
2. Set another variable $original_age equal $age.
3. So we have gone forward in time with the Delorean 5 years. Using an incrementer (either post or pre) add 5 years to your age and echo the results. Now echo $original_age so you see what year you were before you traveled in time.
4. Now you have gone back in time 7 years. Decrement your $age by 7 years.
5. Explain the purpose of the REPL.

### Exercise #4 - Variable Assignment by Reference

1. In your REPL create a variable $score and set it equal to 75.
2. Now assign a new variable $reference_score equal to $score.
3. The team just scored 3 points so using a combined operator ( += ) add 3 points to $score. Now echo $score and echo $reference_score.
4. What is the advantage of using combined operators and give a scenario, other than the one you just did, that would be appropriate to use this technique.

### Exercise #5 - Constants

1. Define a constant BIRTH_CITY and set it equal to your birth city.
2. Try to redefine that constant. Did you get the expected result?
3. Why did you get this result? Explain.

### Exercise #6 - Arrays

1. Here is a list of 10 prime numbers 2, 3, 5, 7, 11, 13, 17, 19, 23, 29. 
2. Save them to an array variable called $prime_numbers.
3. Echo out the prime number 7.
4. Create an associative array called $car. Set the keys for this array as: year, make, model, color, mileage. 
5. Set the values for the keys.
(Make up the mileage part & add other keys with there values, if you want.)
6. Create a multidimensional array called $cars.

	- Includes at least 3 inner arrays.
	
	- The keys should be the owner's name and you should describ the car that they own. (This is building off the previous task.)
7. On the command line, how would you access the 3rd array's information for the 'make' of the owner's car?
8. What's the purpose of using the multidimensional array? 

### Exercise #7 - Git

1. Create empty reposity on github.
2. Create directory locally and change directory (cd) into it .
3. Initialize git locally in this folder.
4. Add your remote reposity to this local folder.
5. Create empty file called TEST.md.
6. Add, commit and push this file up.
7. Verify that the file is online on github
8. Scrap it and do it again.
9. Research the all in compassing purpose of github. On the command line, create an empty file and in your own words, send a research_github.txt to Isaac's email, isaac@codeup.com.

### Exercise #8 - Control Structures

__Title file: hw_wk1_p1.php__

1. In this file create a variable called $hungry and set it to TRUE if you are hungry or FALSE if you are not.
2. Create another variable and call it $food_available and set it equal to TRUE or FALSE.
3. Create an if statement that will echo 'We are fed and good to go.' if both you have $food_available and are $hungry are true.
4. Now create another variable $have_money and set it to either TRUE or FALSE. Adjust your if statement so it reads. If you are $hungry and there is $food_available or $have_money then you will eat. If none of those are true then echo "Not hungy but thank you!"

### Exercise #9 - Ternary Operator

1. Convert the following into the ternary operator form:

```
$logged_in = TRUE;

if($logged_in)
{
	$logged_in_status = 'You are logged in';
} else {
	$logged_in_status = 'You are not logged in';
}

echo $logged_in_status
```