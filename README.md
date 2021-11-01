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

---
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

---
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

---
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

---
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

---
# Homework № 6
## LEARNING OF OOP PRINCIPLES: INHERITANCE AND POLYMORPHISM

## Task № 1:
Write a Java program in which:
- describe the **Shape** class(field *color*, constructor, overridden *toString()* method (a string like "class=...: color=..."), a method for calculating the area of a shape *calcArea()*, which returns a value of 0.0).
- describe the **Circle** class as a subclass of **Shape**. The **Circle** class contains: field *radius*, constructor, overridden *toString()* and *calcArea()* methods.
- describe the **Rectangle** class as a subclass of **Shape**. The **Rectangle** class contains: *width* and *height* fields, constructor, overridden *toString()* and *calcArea()* methods.
- describe the **Triangle** class as a subclass of **Shape**. The **Triangle** class contains: fields ***a, b, c***; constructor, overridden *toString()* and  *calcArea()* methods.
- describe the class **Main** with the *main()* method, in which create an array of shapes (four rectangles, three circles, two triangles) and display it to the console along with the area information of the shapes. Provide some method of the **Main** class to output the array of shapes.
- add a method to the **Main** class for calculating the total area of all shapes of the created array.
- add a method to the **Main** class for calculating the total area of a specific shape type in the created array.
- add the call of the described methods to the *main()* method.

## Requirements:
1) During the coding should be used Java coding conventions.
2) Use the **instanceof** operator to determine the type of shape.
---
# Homework № 7
## LEARNING OF INTERFACES AND EXCEPTIONS HANDLING

## Task № 1:
Open the program created on Homework № 5 and make the following changes:
- replace the *view()* method with the *toString()* method in the description of the **Book** class and change the code that used the *view()* method to appropriate applying of *toString()* method.
- provide for handling incorrect data input by user through the exception handling mechanism (to do this, describe your exceptions). *For example*, you describe the **Validator** class, which contains methods for checking of something for something,  and use its methods to validate the entered values. If all is well, the program continues to work, but if the data is not correct, you throw an exception, and the code using validation should handle the exception.
- supplement the **Books** class with methods of sorting the set of books by author alphabetically, by publisher in alphabetical order, by cost in descending order. Consider when sorting that the original set should not change, this only changes its presentation to the user, i.e. you need to apply copying an array of books before sorting.

## Requirements:
1) During the coding should be used Java coding conventions.
2) Use the **Comparator** interface to describe the rule for comparing books by the specified criterion.
---
# Task № 1
## Calculator
Implement calculator program. Calculator must perform operations:
- addition, subtraction, multiplication, division, exponentiation.
<div>When performing division, enter a check for 0.</div>
<div>If the second argument is 0, it is necessary to throw java.lang.IllegalStateException.</div>

---
# Task № 2
## Point
<div>Implement a Point class that describes a point in the x, y coordinate system - Point (x, y).</div>
<div>The point object must have methods double Point#distanceTo(Point point) - the method must calculate the distance between two points.</div>

---
# Task № 3
## Triangle
<div>Implement a Triangle class. The triangle must be described through points in the coordinate system.</div>
<div>The triangle object must have methods:</div>

- boolean exists() - checks if the triangle exists or not;
- double area() - calculates the area of the triangle.
<div>If triangle doesn't exist, it is necessary to throw java.lang.IllegalStateException.</div>

---
# Task № 4
## Isosceles Triangle
<div>Implement an Isosceles Triangle class by inheriting the Triangle class from task № 3.</div>
<div>Complement the behavior of the method boolean exists() - true if the triangle is isosceles.</div>
<div>Leave the rest of the behavior the same.</div>

---
# Task № 5
## Right Triangle
<div>Implement a Right Triangle class by inheriting the Triangle class from task № 3.</div>
<div>Complement the behavior of the method boolean exists() - true if the triangle is rectangular.</div>
<div>Leave the rest of the behavior the same.</div>

---
# Task № 6
## Square
<div>Implement a Square class based on the four points Point (x, y).</div>

- boolean exists() - checks if the square exists or not.

---
# Task № 7
## Expression
<div>Implement an Expression class. The class must receive a string from a simple mathematical expression and implement methods:</div>

- double calc().
- must support operations: +. -. /. *. exp.
<div>For example, "2+2" - 4, "2-2" – 0.</div>
If the expression is not correct, it is necessary to throw java.lang.IllegalStateException.

---
# Task № 8
## Primes
Implement a class that computes prime numbers up to N.

---
# Task № 9
## Unique Chars
Implement a method for counting unique characters in a string.

---
# Task № 10
## Brackets
<div>Implement methods for checking the correctness of open and closed parentheses.</div>
For example, ()(()((()))) - true, ()) – false.

---
# Task № 11
## Array Contains One
<div>An array of numbers with values 0 and 1 is given. It is necessary to check that all values in the array are equal to 1.</div>
<div>For example, [0, 1] - false, [1, 1] - true.</div>

---
# Task № 12
## Sequence Array
<div>An array of numbers with values 0 and 1 is given. It is necessary to check that the array contains sequences of three or more ones.</div>
For example, [0, 1, 1] - false, [1, 1, 1] - true.

---
# Task № 13
## Mono Array
<div>Numeric array is given. It is necessary to check that all the values in the array are the same.</div>
For example, [0, 0, 0] - true, [1, 1, 1] - true, [0, 1, 1] - false.

---
# Task № 14
## Reverse Phrase
<div>Sentence is given. It is necessary to rearrange the words in the reverse order.</div>
For example, "program and earn" -> "earn and program".

---
# Task № 15
## Cycle Shift
<div>Numeric array is given. It is necessary to implement the method of ring shift by N: int[] shift().</div>
<div>Don't use an additional array.</div>
For example, [1, 2, 3, 4, 5] -> shift(2) -> [4, 5, 1, 2, 3].

---
# Task № 16
## Tic-Tac-Toe
A square array is given. It is necessary to check that it has winning options for tic-tac-toe.

---
# Task № 17
## Cash Machine
<div>ATM cash machine of money change is implemented. The machine receives a paper bill and exchanges it for coins.</div>
The method should return a list of all possible options for changing the bill.

---
# Task № 18
## Pool
<div>A two-dimensional array filled with zeros and ones is given. It is necessary to define the largest set of ones.</div>
<div>A set is a union of ones that are next to each other.</div>
Ignore diagonal neighborhood.

---
# Task № 19
## Maze
<div>A two-dimensional array of ones and zeros is given. It is necessary to find the minimum path from point A to point B.</div>
You can move only on ones and only vertically or horizontally.

---
# Task № 20
## Combine
A one-dimensional array is given. It is necessary to find all possible variants of permutations of this array.

---
<div align="center">
<a href="https://github.com/webmanager2009/webmanager2009/blob/main/Presentation_slide_1.jpg" title="Presentation slide № 1"><img src="https://github.com/webmanager2009/webmanager2009/blob/main/Presentation_slide_1.jpg"
alt="Presentation slide № 1"></a>
</div>
---
<div align="center">
<a href="https://github.com/webmanager2009/webmanager2009/blob/main/Presentation_slide_2.jpg" title="Presentation slide № 2"><img src="https://github.com/webmanager2009/webmanager2009/blob/main/Presentation_slide_2.jpg"
alt="Presentation slide № 2"></a>
</div>
---
