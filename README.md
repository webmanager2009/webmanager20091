# New Document

[![Watch the video](https://github.com/webmanager2009/webmanager2009/blob/main/Capture2.PNG)](https://youtu.be/Ee9cELSGwzo)

# Homework № 1
## LEARNING OF DATA TYPES AND OPERATIONS WITH THEM

## Task № 1:
Write a Java program that:
- describes a three-digit integer *number* number (*for example*, 123);
- finds and displays to the console the difference between *number* number and number composed of the digits of the *number*, but taken in reverse order (for the specified example, the reverse number is 321).

## Task № 2:
Write a Java program that converts the weight given in pounds to kilograms, but outputs the number of received kilograms and grams separately (in 1 lb 453.6 grams).

## Task № 3:
Write a Java program that calculates and displays to the console the amount of profit for a given deposit (*for example*, 10000) for a given number of months (*for example*, 6) at a specified percentage per annum (*for example*, 12%).

## Requirements:
1) Use variables to store program data.
2) Use arithmetic operations for calculations and, if necessary, data types casting.
3) Use the *System.out.println(...)* operator to output the result of calculations.
4) Read books:
	- Head First Java, O'Reilly.
	- Java Code Convention.
	- Clean Code, Robert C. Martin.
5) Watch the video <https://itvdn.com/ru/specialities/java-developer>.

# Homework № 2
## LEARNING OF OPERATORS

## Task № 1:
Write a Java program that fills in with asterisks (*) and displays to the console the triangles  shown in the figure:

<p align="center">
<a href="https://github.com/webmanager2009/webmanager2009/blob/main/res/Untitled.jpg" title="Animated GIF cat"><img src="https://github.com/webmanager2009/webmanager2009/blob/main/res/Untitled.jpg"
alt="Cat1"></a>
</p>

## Requirements:
1) During the coding should be used Java coding conventions.
2) Keep reading books:
	- Head First Java, O'Reilly.
	- Java Code Convention.
	- Clean Code, Robert C. Martin.
3) Keep watching the video <https://itvdn.com/ru/specialities/java-developer>.

# Homework № 3
## LEARNING OF METHODS AND PROCESSING LINE

## Task № 1:
Write a Java program that inputs some string and prints to the console all the unique characters of this string. String processing is done in a separate method.

## Task № 2:
Write a Java program that inputs an integer, converts it to binary representation, storing it as a string, and prints the result to the console. The conversion is done in a separate method.

## Requirements:
1) During the coding should be used Java coding conventions.
2) Methods of data processing should not carry out the output of the result, it should be returned from methods.

## Additional tasks for those who wish:

## Task № 1:
Write a Java program that:
- inputs an integer variable and outputs the result of its processing;
- processing is a method that gets an integer, determines the last two digits and returns them as a string of characters in reverse order. *For example*, the number is 2546, the result is "64".

## Task № 2:
Write a Java program that:
- inputs the height of the pyramid and passes it to the method for outputing the pyramid;
- the method outputs to the console the pyramid of the obtained height (value in the range from 1 to 9). For example, for *height* = 3:

<div align="center">1</div>
<div align="center">121</div>
<div align="center">12321</div>
<div align="center">1234321</div>

## Task № 3:
Write a Java program that:
- describes a method that finds and returns the first character of the word under the given number in the given string. Restriction: words in a line are separated only by spaces.
- inputs some text and a word number, and then uses a method to process and outputs the result.

# Homework № 4
## LEARNING OF ARRAYS

## Task № 1 - Processing without branchings:
Write a Java program that creates an array of any type and then prints it to the console in forward and backward order.

## Task № 2 - Creating a third array of known length:
Write a Java program that creates two arrays of the same dimension, and then creates a third one of the same dimension and fills it with the pairwise sum of elements from the first two ones.

## Task № 3 - Creating a third array of unknown length:
Write a Java program that creates an array of any type, and then separates it into two ones: from positive and negative elements.

## Requirements:
1) During the coding should be used Java coding conventions.
2) If possible, processing arrays to do in a separate method.
3) The dimension of the array can be set explicitly or entered by typing from the keyboard.
4) Fill the original arrays with random values (*for example*, use the  Math.random() method).
5) For clarity of the completing the task, it is necessary to output the arrays before and after processing in cases where the original array changes.

## Additional tasks for those who wish:

## Task № 1
Write a Java program that creates an array of any type, and then calculates the arithmetic mean of the array elements and the number of array elements that are greater than this arithmetic mean.

## Task № 2
Write a Java program that creates two arrays of different dimensions and then creates a third array as a concatenation of the two original ones.

## Task № 3
Write a Java program that creates an array of any type and then determines the maximum and minimum values of the array elements and removes their duplicates.

# Homework № 5
## LEARNING OF CLASSES

## Task № 1:
Write a Java program in which:
- describe a well encapsulated **Book** class (ID, Title, Author, Publisher, Year of publication, Number of pages, Cost), i.e. private fields with accessor methods. Add a constructor to the class with all parameters. Add a *view()* method to the class  to display (output) the object.
- describe the **Books** class, which will contain an array of objects (field) of the **Book** type; constructor that takes the size of an array and allocates memory for it; method of adding one book; method to display all books in an array; method of changing the cost of books by a specified number of percent; search method for all books of the specified author; search method for all books published after the specified year.
- describe a class with a *main()* method, in which you enter the dimension of an array of books and create an object of type **Books**; create and add objects of type **Book** to an object of type **Books**; display a set of books to the console; use all other methods of class **Books**.

## Requirements:
1) During the coding should be used Java coding conventions.
2) Use the **Scanner** class to enter a percentage value from the keyboard to change the cost of books, author and year of publication for the selection of books.
3) Search methods should return a new object of type **Books**, which encapsulates an array of found books (if the array is empty, then provide the output of the corresponding message).
