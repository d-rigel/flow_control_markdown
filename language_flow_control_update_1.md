![functions image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT4m8CbZYpzU62RvizTh8EweUH0N4APU7t-WOTgt6uYzdJjyhcflF94pUgNKcHyhXV5qYE&usqp=CAU)

#### Objectives:

* Learn Conditional Statements in various programming languages .
* Learn Loops in various programming languages.
* Learn Switch Statement (or Case Statement) in various programming languages.
* Learn Break Statement in various programming languages
* Learn Continue Statement in various programming languages
* Learn Return Statement in various programming languages


#### Resources:

* [YouTube Video](https://www.youtube.com/@junior-it-ai/videos)
* [Interactive Practice](https://juniorit.ai/resource/course/coding-syntax-and-comments-in-different-languages-practice)

#### Contents

1. <a name="b1" href="#a1">Conditional statements in different programming languages</a>
2. <a name="b2" href="#a2">Loop statements in different programming languages</a>
3. <a name="b3" href="#a3">Switch statements in different programming languages</a>
4. <a name="b4" href="#a4">Break Statement in different programming languages</a>
5. <a name="b5" href="#a5">Continue Statement in different programming languages</a>
6. <a name="b6" href="#a6">Return Statement in different programming languages</a>


Flow control is an essential concept in programming that allows developers to dictate the execution path of a program. 
By using control structures, such as conditionals and loops, programmers can make their code more intelligent, efficient, and adaptable.

In this Lecture, we will explore the fundamentals of flow control, discuss different control structures, and provide practical examples in different programming languages to help you understand and implement effective flow control in your programs.

## <a name="a1" href="#b1">1.</a> Conditional statements in different programming languages

Conditional statements in programming allow you to make decisions based on certain conditions.
They control the flow of execution by evaluating conditions and executing different blocks of code based on the results. 
Some common types of conditional statements are:



**If / if-else statements:**

If/else statements are control structures used in programming to make decisions based on certain conditions. 
They allow the program to execute different blocks of code depending on whether a condition is true or false.


**If / if-else statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Objective-C share some similarities in their "if/if-else" statements.


```tabs

\```dart {}
var  num=5; 
if (num>0) { 
 print("number is positive"); 
}  
// The above example will print “number is positive” as the condition specified by the if block is true.

int age = 18;

if (age >= 18) {
    print("You are eligible to vote!");
} else {
    print("You are not eligible to vote yet.");
}

//Depending on the value of age, it will print out the corresponding text's

  int number = 10;

  if (number > 0) {
    print("The number is positive.");
  } else if (number < 0) {
    print("The number is negative.");
  } else {
    print("The number is zero.");
  }

//Depending on the value of age, it will print out the corresponding text's

\```

\```javascript {title: 'JavaScript/TypeScript'}
//Make a "Good day" greeting if the hour is less than 18:00:

let hour = 13
if (hour < 18) {
  greeting = "Good day";
}

//The result of greeting will be "Good day"

let age = 18;

if (age >= 18) {
  console.log("You are eligible to vote!");
} else {
  console.log("You are not eligible to vote yet.");
}

//Depending on the value of age, it will print out the corresponding text's

 let number = 10;

if (number > 0) {
  console.log("The number is positive.");
} else if (number < 0) {
  console.log("The number is negative.");
} else {
  console.log("The number is zero.");
}

//Depending on the value of age, it will print out the corresponding text's

\```

\```php {}
// Output "Hello, JuniorIT.AI!" if the current time (HOUR) is less than 20:

$t = date("H");

if ($t < "20") {
  echo "Hello, JuniorIT.AI!";
}

//As long as the time is less than 20, it will print "Hello, JuniorIT.AI


$age = 25;

if ($age >= 18) {
    echo "You are eligible to vote.";
} else {
    echo "You are not eligible to vote.";
}

//Depending on the value of age, it will print out the corresponding text's

$number = 10;

if ($number > 0) {
    echo "The number is positive.";
} else if ($number < 0) {
    echo "The number is negative.";
} else {
    echo "The number is zero.";
}

//In this example above our result will depend on the value assigned to variable "number"
\```


\```java {}

int x = 20;
int y = 18;
if (x > y) {
    System.out.println("x is greater than y");
}

// If x is greater than y is going to print "x is greater than y"

int age = 25;

if (age >= 18) {
    System.out.println("You are eligible to vote.");
} else {
    System.out.println("You are not eligible to vote.");
}

//Depending on the value of age, it will print out the corresponding text's

int number = 10;

if (number > 0) {
     System.out.println("The number is positive.");
} else if (number < 0) {
     System.out.println("The number is negative.");
} else {
     System.out.println("The number is zero.");
}
//Depending on the value of age, it will print out the corresponding text's

\```


\```c++ {title: 'C/C++'}

 int num1 = 20;

 if (num1 > 18) {
    std::cout << "20 is greater than 18." << std::endl;
}  

//In the example above, we test two values to find out if 20 is greater than 18. If the condition is true, print some text:

int age = 25;

if (age >= 18) {
    std::cout << "You are eligible to vote." << std::endl;
} else {
    std::cout << "You are not eligible to vote." << std::endl;
}

//In the example above, we test two values to find out if 25 is greater than 18. If the condition is true, print some text:


int num2 = 10;

if (num2 > 0) {
    std::cout << "The num2 is positive." << std::endl;
} else if (num2 < 0) {
    std::cout << "The num2 is negative." << std::endl;
} else {
    std::cout << "The num2 is zero." << std::endl;
}

//In the example above we prints the text based on the value of the variable "number"


\```

\```objective-c {}

 /* local variable definition */
int a = 10;
 
/* check the boolean condition using if statement */
if( a < 20 ) {
/* if condition is true then print the following */
    NSLog(@"a is less than 20\n" );
}
   
   NSLog(@"value of a is : %d\n", a);

/*
   When the above code is compiled and executed, it produces the following result

   2013-09-07 22:07:00.845 demo[13573] a is less than 20
   2013-09-07 22:07:00.845 demo[13573] value of a is : 10
*/

int b = 10;

if (b > 0) {
    NSLog(@"The b is positive.");
} else if (b < 0) {
    NSLog(@"The b is negative.");
} else {
    NSLog(@"The b is zero.");
}

//In the example above we prints the text based on the value of the variable "number"

int c = 10;

if (c > 0) {
 NSLog(@"The c is positive.");
} else if (c < 0) {
 NSLog(@"The c is negative.");
} else {
 NSLog(@"The c is zero.");
}
\```

\```go {}

number := 10

if number > 0 {
    fmt.Println("The number is positive.")
} else if number < 0 {
    fmt.Println("The number is negative.")
} else {
    fmt.Println("The number is zero.")
}

//In the example above we prints the text based on the value of the variable "number"

number2 := 10
if number2 > 0 {
 fmt.Println("The number2 is positive.")
} else if number2 < 0 {
fmt.Println("The number2 is negative.")
} else {
fmt.Println("The number2 is zero.")
}
//In the example above we prints the text based on the value of the variable "number2"
number3 := 10
if number3 > 0 {
        fmt.Println("The number3 is positive.")
    } else if number3 < 0 {
        fmt.Println("The number3 is negative.")
    } else {
        fmt.Println("The number3 is zero.")
}

//In the example above we prints the text based on the value of the variable "number3"
\```

```

Many programming languages have "if" and "if-else" statements as fundamental constructs. However, some languages have additional features or syntax that make their "if" statements more expressive or powerful. Here are a few examples:


```tabs

\```python {}
age = 25

if age >= 18:
    print("You are eligible to vote.")

"""
When you run this code it will output: You are eligible to vote.
"""

x = 5

if x > 10:
    print("x is greater than 10")
else:
    print("x is not greater than 10")

"""
when you This code it output will be: x is not greater than 10

"""

x = 5

if x > 10:
    print("x is greater than 10")
elif x > 5:
    print("x is greater than 5 but not greater than 10")
else:
    print("x is not greater than 5")

"""
In the example above the print out text will depend on the value assigned to x
"""
\```

\```swift {}
let number = 10

if number > 0 {
    print("The number is positive.")
} else if number < 0 {
    print("The number is negative.")
} else {
    print("The number is zero.")
}
//In the example above we prints the text based on the value of the variable "number"

let number1 = 10

if number1 > 0 {
 print("The number1 is positive.")
} else if number1 < 0 {
 print("The number1 is negative.")
   } else {
     print("The number1 is zero.")
}

//In the example above we prints the text based on the value of the variable "number"

  let number2 = 10
  if number2 > 0 {
      print("The number2 is positive.")
  } else if number2 < 0 {
      print("The number2 is negative.")
  } else {
      print("The number2 is zero.")
  }

//In the example above we prints the text based on the value of the variable "number"

\```

\```kotlin {}

val age = 25

if (age >= 18) {
    println("You are eligible to vote.")
} else {
    println("You are not eligible to vote.")
}

//In the example above we prints the text based on the value of the variable "age"

val age1 = 25

if (age1 >= 18) {
  println("You are eligible to vote.")
} else {
    println("You are not eligible to vote.")
}

//In the example above we prints the text based on the value of the variable "age1"

val number = 10

if (number > 0) {
    println("The number is positive.")
} else if (number < 0) {
    println("The number is negative.")
} else {
    println("The number is zero.")
}

//In the example above we prints the text based on the value of the variable "number"

\```

```


**Terbary operators**

A ternary operator, also known as the conditional operator, is a compact syntax for expressing conditional statements in many programming languages. It allows you to conditionally assign a value to a variable or express a condition in a concise manner.


**Ternary operatos  in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have ternary operators for conditional operations.
Lets check ternary operators in the above languages.

```tabs

\```dart {}
int number = 10;

String result = number > 0 ? "Positive" : "Non-positive";
print(result);

//In this example above our result will depend on the value assigned to variable "number"

\```

\```javascript {title: 'JavaScript/TypeScript'}

let number = 10;

let result = number > 0 ? "Positive" : "Non-positive";
console.log(result);

//In this example above our result will depend on the value assigned to variable "number"
\```

\```php {}
$number = 10;

$result = ($number > 0) ? "Positive" : "Non-positive";
echo $result;

//In this example above our result will depend on the value assigned to variable "number"

\```


\```java {}
int number = 10;
        
String result = (number > 0) ? "Positive" : "Non-positive";
System.out.println(result);
        
//In this example above our result will depend on the value assigned to variable "number"


\```

\```kotlin {}

val number = 10

val result = if (number > 0) "Positive" else "Non-positive"
println(result)

//In this example above our result will depend on the value assigned to variable "number"
\```

\```c++ {title: 'C/C++'}


int number = 10;

std::string result = (number > 0) ? "Positive" : "Non-positive";
std::cout << result << std::endl;

//In this example above our result will depend on the value assigned to variable "number"



\```

\```objective-c {}
int number = 10;
NSString *result = (number > 5) ? @"Greater than 5" : @"Less than or equal to 5";
NSLog(@"%@", result);

//In this example above our result will depend on the value assigned to variable "number"

\```

\```swift {}
let number = 10

let result = number > 0 ? "Positive" : "Non-positive"
print(result)

//In this example above our result will depend on the value assigned to variable "number"

\```

\```go {}

number := 10

result := ""
if number > 0 {
    result = "Positive"
} else {
    result = "Non-positive"
}
fmt.Println(result)

//In this example above our result will depend on the value assigned to variable "number"

\```

```


## <a name="a2" href="#b2">2.</a> Loop statements in different programming languages

In programming, loops are control structures that allow you to repeat a block of code multiple times.
They are useful when you need to perform the same task repeatedly or iterate over a collection of data.
There are generally three types of loops: for loops, while loops, and do-while loops.


**For loops:**

For loops are used when you know the number of iterations in advance or when you want to iterate over a collection of data, such as an array or a list. The syntax of a for loop typically includes an initialization, a condition, an update statement, and the code block to be executed.

Let's break down each part of the for loop:

1. Initialization: This step is executed only once at the beginning of the loop and is used to initialize a control variable. 
   It sets the initial value for the variable that controls the loop.
2. Condition: The condition is evaluated before each iteration of the loop. If the condition is true, the loop's code block is executed. 
   If the condition is false, the loop terminates, and the program continues to the next line of code after the loop.
3. Update: The update statement is executed at the end of each iteration. 
   It typically increments or decrements the control variable to move towards the loop termination condition.


**For loops in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have for loops  for iteraction operations.
Lets check for loops in the above languages.

```tabs

\```dart {}
for (int i = 0; i < 5; i++) {
    print(i);
  }

/*In this Dart example, the for loop will iterate five times, printing the values of i from 0 to 4. */

\```

\```javascript {title: 'JavaScript/TypeScript'}

 for (let i = 0; i < 5; i++) {
    console.log(i);
}

//In this example above, the loop will execute five times because the condition i < 5 is satisfied.

\```

\```php {}
for ($i = 0; $i < 5; $i++) {
    echo $i . "<br>";
}

//In this example, the loop will iterate 5 times. The loop starts with the initialization statement $i = 0, sets the condition $i < 5, and 
//increments the value of $i by 1 after each iteration with $i++.

\```


\```java {}
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

/*In this example above, the for loop will iterate 5 times. The loop will print the values of i from 0 to 4.*/

\```

\```kotlin {}

for (i in 0 until 5) {
    println(i)
}

//In this example, the loop will iterate from 0 to 4 (inclusive).

for (i in 0..10 step 2) {
    println(i)
}
//In this example above, the .. operator is used to specify a range from 0 to 10 (inclusive), and the step 2 part indicates that the loop 
//should increment i by 2 in each iteration. This loop will print the even numbers 0, 2, 4, 6, 8, and 10.
\```

\```c++ {title: 'C/C++'}

     for (int i = 1; i <= 5; i++) {
        std::cout << "Value of i: " << i << std::endl;
    }


//In this example the loop continues as long as the condition i <= 5 is true. After each iteration, the loop variable i is incremented by i++.
\```

\```objective-c {}

 for (int i = 0; i < 5; i++) {
    NSLog(@"The value of i is %d", i);
}

/*In this example the loop will continue executing as long as i is less than 5.*/

\```

\```swift {}
for i in 0..<5 {
    print(i)
}


//The loop uses a range expression 0..<5 to specify the range of values that i will take. the loop iterates for i values 0, 1, 2, 3, and 4.

for i in 0...4 {
    print(i)
}
\```

\```go {}
for i := 0; i < 5; i++ {
    fmt.Println(i)
}


//When you run this program, it will output: 0 1 2 3 4
\```

```


**While loops:**

A while loop is a control flow statement that allows you to repeatedly execute a block of code as long as a certain condition is true. The loop continues iterating until the condition becomes false. The syntax of a while loop typically includes the condition and the code block to be executed.

Let's break down each part of the while loop:

1. Condition: The condition is evaluated before each iteration of the loop. 
   If the condition is true, the loop's code block is executed. If the condition is false, the loop terminates, and the program continues to the next line of code after the loop
2. Code block: The code block contains the statements that will be executed as long as the condition is true. 
   It can be a single statement or  a group of statements enclosed in curly braces.




**While loops in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have while loops  for iteraction operations.
Lets check while loops in the above languages


```tabs

\```dart {}
int i = 0;
  
while (i < 5) {
    print(i);
    i++;
}
//In this example above, the while loop is used to print the numbers from 0 to 4.


\```

\```javascript {title: 'JavaScript/TypeScript'}

let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}

/*In this example above, the while loop continues as long as the condition i < 5 is true. Output: 0 1 2 3 4*/


\```

\```php {}

$i = 0;
while ($i < 5) {
    echo $i . "\n";
    $i++;
}

/*In this example, the while loop initializes $i to 0 and continues to execute the loop as long as $i is less than 5.
Output will be 0 1 2 3 4*/

\```


\```java {}
int i = 0;
while (i < 5) {
    System.out.println(i);
      i++;
}

/*In this example, the while loop continues as long as the condition i < 5 is true. The loop iterates from 0 to 4. output: 0 1 2 3 4*/


\```

\```kotlin {}

var i = 0
 while (i < 5) {
  println(i)
        i++
}

/*In this example above, the while loop continues executing the code block as long as the condition i < 5 is true. Output: 0 1 2 3 4*/

\```

\```c++ {title: 'C/C++'}

int i = 0;
 while (i < 5) {
    std::cout << i << std::endl;
        i++;
}

/*In this example, the while loop continues executing as long as i is less than 5. Output: 0 1 2 3 4*/

\```

\```objective-c {}
int i = 0;
while (i < 5) {
    NSLog(@"%d", i);
    i++;
}

/*In this example above, the while loop continues as long as the condition i < 5 is true. Output: 0 1 2 3 4*/
\```

\```swift {}
var i = 0
while i < 5 {
    print(i)
    i += 1
}

/*In this example, the while loop continues executing as long as the condition i < 5 is true. Output: 0 1 2 3 4*/

\```

\```go {}
i := 0
for i < 5 {
 fmt.Println(i)
    i++
}

/*In this example the loop continues as long as i is less than 5. Output 0 1 2 3 4*/

\```

```

**Do-While loops:**

In programming, a do-while loop is a control flow structure that executes a block of code at least once, and then repeats the execution as long as a specified condition is true. The key difference between a do-while loop and a regular while loop is that the condition in a do-while loop is evaluated after executing the code block, ensuring that the block is executed at least once.

Let's break down each part of the do-while loop:

1. Code block: The code block contains the statements that will be executed at least once and potentially multiple times,
   depending on the condition.
2. Condition: The condition is evaluated after each iteration of the loop. 
   If the condition is true, the loop continues, and the code block is  executed again.
   If the condition is false, the loop terminates, and the program continues to the next line of code after the loop.





**Do-While loops in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have for do-while loops  for iteraction operations.
Lets check do-while loops in the above languages


```tabs

\```dart {}
 int i = 0;
  
  do {
    print(i);
    i++;
  } while (i < 5);

/*In this example the loop continues to iterate as long as the condition i < 5 is true. Output: 0 1 2 3 4*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

let i = 0;

do {
    console.log(i);
    i++;
} while (i < 5);

/*In this example above, the loop will execute the code block at least once and continue executing as long as the condition i < 5 is true.
Output: 0 1 2 3 4*/

\```

\```php {}
$i = 0;
do {
    echo $i . "<br>";
    $i++;
} while ($i < 5);

/*In this example above, the do-while loop will print the numbers from 0 to 4. Output: 0 1 2 3 4*/

\```


\```java {}
        
int i = 0;
 do {
  System.out.println(i);
    i++;
} while (i < 5);

/*In this example, the loop will print the numbers from 0 to 4. Output: 0 1 2 3 4*/

\```

\```kotlin {}

var i = 0
 do {
  println(i)
    i++
} while (i < 5)

/*In this example above, the loop will print the numbers from 0 to 4.*/

\```

\```c++ {title: 'C/C++'}

int i = 0;
do {
 std::cout << i << std::endl;
  i++;
} while (i < 5);
    
/*The loop continues executing as long as i is less than 5. Output 0 1 2 3 4*/
\```

\```objective-c {}
int i = 0;
do {
    NSLog(@"%d", i);
    i++;
} while (i < 5);

/*If the condition is true, the loop continues executing: Output: 0 1 2 3 4*/
\```

\```swift {}
var i = 0
repeat {
    print(i)
    i += 1
} while i < 5

/*the loop will print the numbers from 0 to 4. Output: 0 1 2 3 4*/


\```

\```go {}
 i := 0
for {
fmt.Println(i)
 i++
  if i >= 5 {
    break
    }
}

/*
In this example, the for loop runs indefinitely until the break statement is encountered. Inside the loop, fmt.Println(i) statement prints the value of i, which starts from 0. Then, i is incremented by 1 (i++). The if i >= 5 condition checks if i has reached 5 or more. If the condition is true, the break statement is executed, and the loop terminates.
*/
\```

```


**foreach loops:**

The foreach statement, or foreach loop, is a construct found in many programming languages that allows for easy iteration over elements in a collection, such as an array, list, set, or dictionary. It provides a way to perform a specific action on each element of the collection without the need for explicit indexing or maintaining a loop counter. Here we have few languages that use's foreach loops.


**foreach loops in few popualar languages**

JavaScript/TypeScript, Dart, PHP, and kotlin, uses foreach  loops  for iteraction operations.
Lets check foreach loops in the above languages

```tabs

\```dart {}
 
  List<String> fruits = ['Apple', 'Banana', 'Orange'];

  // Iterating over a List
  fruits.forEach((fruit) {
    print('I like $fruit');
  });

  Set<int> numbers = {1, 2, 3, 4, 5};

  // Iterating over a Set
  numbers.forEach((number) {
    print('The number is $number');
  });

  Map<String, int> scores = {'John': 85, 'Alice': 92, 'Bob': 78};

  // Iterating over a Map
  scores.forEach((name, score) {
    print('$name scored $score');
  });

/*
In this example above, we have three different collections: a List called fruits, a Set called numbers, and a Map called scores
When you run this code, it will output:
I like Apple
I like Banana
I like Orange
The number is 1
The number is 2
The number is 3
The number is 4
The number is 5
John scored 85
Alice scored 92
Bob scored 78
*/


\```

\```javascript {title: 'JavaScript/TypeScript'}

const fruits = ['Apple', 'Banana', 'Orange'];

fruits.forEach(fruit => {
  console.log('I like ' + fruit);
});

/*
In this example, we have an array called fruits containing three elements.
When you run this code, it will output:
I like Apple
I like Banana
I like Orange

*/

\```

\```php {}
$fruits = ["Apple", "Banana", "Orange"];

foreach ($fruits as $fruit) {
    echo $fruit . "\n";
}

/*
In this example, we have an array $fruits containing three elements: "Apple", "Banana", and "Orange". The foreach loop iterates over each element in the array.
When you run this code, it will output:
Apple
Banana
Orange

*/

\```


\```kotlin {}
val fruits = arrayOf("Apple", "Banana", "Orange")

for (fruit in fruits) {
    println("I like $fruit")
}

/*
In this example, we have an array called fruits containing strings representing different fruits.
When you run this code, it will output:
I like Apple
I like Banana
I like Orange


*/

\```

```

Several programming languages have dedicated foreach or similar statements designed specifically for iterating over collections or sequences. Here  are some few languages that provide special foreach statements:

```tabs

\```java {}
 
int[] numbers = { 1, 2, 3, 4, 5 };

for (int number : numbers) {
    System.out.println(number);
  }

String[] fruits = { "Apple", "Banana", "Orange" };

for (String fruit : fruits) {
    System.out.println(fruit);
}
/*
In Java, the foreach loop is known as the enhanced for loop or the for-each loop.
In this example, we have an array of integers numbers and an array of strings fruits.
Click run to see output
*/



\```

\```c++ {title: 'C/C++'}
#include <iostream>
#include <vector>

int main() {
    std::vector<int> numbers = {1, 2, 3, 4, 5};

    // Iterating over a vector
    for (int number : numbers) {
        std::cout << number << std::endl;
    }

    return 0;
}



/*
In this example, we have a std::vector<int> called numbers that stores a collection of integers.
Click run to see output

*/

\```

\```objective-c {}
NSArray *fruits = @[@"Apple", @"Banana", @"Orange"];

// Using NSEnumerator
NSEnumerator *enumerator = [fruits objectEnumerator];
id fruit;
while (fruit = [enumerator nextObject]) {
    NSLog(@"I like %@", fruit);
}

// Using block-based enumeration
[fruits enumerateObjectsUsingBlock:^(id fruit, NSUInteger idx, BOOL *stop) {
    NSLog(@"I like %@", fruit);
}];



/*
In Objective-C, there isn't a direct equivalent of a foreach loop like in some other programming languages. However, you can achieve similar functionality using fast enumeration with an NSEnumerator or block-based enumeration

*/

\```


\```swift {}
let fruits = ["Apple", "Banana", "Orange"]

for fruit in fruits {
    print(fruit)
}


/*
In this example, we have an array called fruits containing three elements: "Apple", "Banana", and "Orange".
Click run to see output
*/

\```

\```go {}
numbers := []int{1, 2, 3, 4, 5}

// Iterating over a slice
for _, number := range numbers {
	fmt.Println(number)
}

fruits := map[string]string{
		"apple":  "red",
		"banana": "yellow",
		"orange": "orange",
}

// Iterating over a map
for fruit, color := range fruits {
	fmt.Printf("%s is %s\n", fruit, color)
}


/*
In this example, we have a slice called numbers and a map called fruits.
Click run to see output
*/

\```

\```python {}
fruits = ['Apple', 'Banana', 'Orange']

# Iterating over a list
for fruit in fruits:
    print(fruit)



"""
In this example, we have a list called fruits containing three elements: 'Apple', 'Banana', and 'Orange'.
Click run to output
"""

\```

```




## <a name="a3" href="#b3">3.</a> Switch statements in different programming languages

A switch statement is a control flow statement found in many programming languages, including Go. It allows you to select and execute different blocks of code based on the value of an expression or variable. The syntax of a switch statement typically includes multiple case statements and an optional default statement.

Let's break down each part of the switch statement:
1. Expression: The expression is evaluated, and its value is compared against the values in each case statement. It can be of any type that can be compared for equality, such as integers, strings, or even custom types.

2. Case Statements: Each case statement represents a specific value that the expression is compared against. If the expression matches a case value, the corresponding code block is executed.

3. Code Block: The code block associated with each case statement contains the statements to be executed when the expression matches the case value.

4. Default: The default statement is optional and is executed when none of the case values match the expression. It is typically used as a fallback option.





**Switch statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have switch statements to execute blocks of codes.
Lets check switch statements in the above languages


```tabs

\```dart {}
  String grade = 'B';

  switch (grade) {
    case 'A':
      print('Excellent');
      break;
    case 'B':
      print('Good');
      break;
    case 'C':
      print('Fair');
      break;
    case 'D':
      print('Poor');
      break;
    default:
      print('Invalid grade');
  }


/*
In this example, the switch statement takes a variable grade as the expression and compares it against different cases. Based on the value of grade, the corresponding code block is executed.

When you run this program, it will output: Good

Since the value of grade is 'B', the code block associated with case 'B' is executed, which prints "Good" to the console.

Note that each case is followed by a break statement to exit the switch statement after executing the corresponding code block. This prevents fall-through behavior where execution continues to the next case even if a match is found.

If none of the case values match the expression, the code block associated with the default statement is executed. In this example, if the value of grade is not 'A', 'B', 'C', or 'D', it will print "Invalid grade".

Note: You can customize the switch statement by adding or removing cases and adjusting the code blocks to fit your specific requirements. The switch statement in Dart provides a concise way to handle multiple conditions based on the value of an expression.
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 let day = 3;

switch (day) {
  case 1:
    console.log("Monday");
    break;
  case 2:
    console.log("Tuesday");
    break;
  case 3:
    console.log("Wednesday");
    break;
  case 4:
    console.log("Thursday");
    break;
  case 5:
    console.log("Friday");
    break;
  default:
    console.log("Weekend");
}


/*
In this example, the switch statement compares the value of the variable day against different cases. Since day is 3, the code block associated with case 3 is executed, and it logs "Wednesday" to the console.

When you run this code, it will output: Wednesday
*/

\```

\```php {}
$day = 3;

switch ($day) {
    case 1:
        echo "Monday";
        break;
    case 2:
        echo "Tuesday";
        break;
    case 3:
        echo "Wednesday";
        break;
    case 4:
        echo "Thursday";
        break;
    case 5:
        echo "Friday";
        break;
    default:
        echo "Weekend";
        break;
}



/*
In this example, the switch statement compares the value of the variable $day against different cases. Since $day is 3, the code block associated with the case 3 is executed, and it echoes "Wednesday" to the output.

When you run this PHP code, it will output: Wednesday
*/

\```


\```java {}
        int day = 3;

        switch (day) {
            case 1:
                System.out.println("Monday");
                break;
            case 2:
                System.out.println("Tuesday");
                break;
            case 3:
                System.out.println("Wednesday");
                break;
            case 4:
                System.out.println("Thursday");
                break;
            case 5:
                System.out.println("Friday");
                break;
            default:
                System.out.println("Weekend");
                break;
        }


/*
In this example, the switch statement compares the value of the variable day against different cases. Since day is 3, the code block associated with the case 3 is executed, and it prints "Wednesday" to the console.

When you run this program, it will output: Wednesday
*/

\```

\```kotlin {}

val dayOfWeek = 3

    when (dayOfWeek) {
        1 -> println("Monday")
        2 -> println("Tuesday")
        3 -> println("Wednesday")
        4 -> println("Thursday")
        5 -> println("Friday")
        else -> println("Weekend")
}


/*
In this example, the when keyword is used to initiate the switch statement. It compares the value of dayOfWeek against different cases. Since dayOfWeek is 3, the code block associated with 3 -> println("Wednesday") is executed, and it prints "Wednesday" to the console.

When you run this program, it will output: Wednesday
*/


\```

\```c++ {title: 'C/C++'}
    int day = 3;

    switch (day) {
        case 1:
            std::cout << "Monday" << std::endl;
            break;
        case 2:
            std::cout << "Tuesday" << std::endl;
            break;
        case 3:
            std::cout << "Wednesday" << std::endl;
            break;
        case 4:
            std::cout << "Thursday" << std::endl;
            break;
        case 5:
            std::cout << "Friday" << std::endl;
            break;
        default:
            std::cout << "Weekend" << std::endl;
            break;
    }

/*
In this example, the switch statement compares the value of the variable day against different cases. Since day is 3, the code block associated with case 3 is executed, and it prints "Wednesday" to the console.

When you run this program, it will output: Wednesday
*/
\```

\```objective-c {}


int day = 3;

switch (day) {
    case 1:
        NSLog(@"Monday");
        break;
    case 2:
        NSLog(@"Tuesday");
        break;
    case 3:
        NSLog(@"Wednesday");
        break;
    case 4:
        NSLog(@"Thursday");
        break;
    case 5:
        NSLog(@"Friday");
        break;
    default:
        NSLog(@"Weekend");
        break;
}



/*
In this example, the switch statement compares the value of the variable day against different cases. Based on the value of day, the code block associated with the matching case is executed.

When you run this code, it will output: Wednesday
 */
\```

\```swift {}
let fruit = "apple"

switch fruit {
case "apple":
    print("It's an apple.")
case "banana":
    print("It's a banana.")
case "orange":
    print("It's an orange.")
default:
    print("It's an unknown fruit.")
}



/*
In this example, the switch statement compares the value of the fruit variable against different cases. Based on the value of fruit, the corresponding code block is executed.

When you run this code, it will output: It's an apple.
*/

\```

\```go {}
    fruit := "apple"

    switch fruit {
    case "apple":
        fmt.Println("Selected fruit: Apple")
    case "banana":
        fmt.Println("Selected fruit: Banana")
    case "orange":
        fmt.Println("Selected fruit: Orange")
    default:
        fmt.Println("Unknown fruit")
    }


/*
In this example, the switch statement is used to compare the value of the variable fruit against different cases. Depending on the value of fruit, the corresponding code block is executed.

When you run this program, it will output: 
Selected fruit: Apple
*/
\```

```


## <a name="a4" href="#b4">4.</a> Break statements in different programming languages

The break statement is a control flow statement that is commonly used within loops or switch statements. It allows you to prematurely exit from a loop or terminate the execution of a switch statement. When the break statement is encountered, the program immediately exits the loop or switch statement, and execution continues with the next line of code after the loop or switch.

Here are two common scenarios where the break statement is used:

Loop Termination: Within a loop, when a certain condition is met, you can use the break statement to exit the loop before it has completed all iterations. This is often used when you want to prematurely end the loop based on a specific condition.



Switch Statement Termination: In a switch statement, the break statement is used to terminate the execution of the switch and exit the block of code associated with it. This prevents the program from executing subsequent case statements.

**Break statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have break statements to execute blocks of codes.
Lets check break statements in the above languages

```tabs

\```dart {}
for (int i = 0; i < 10; i++) {
    if (i == 5) {
      break;
    }
    print(i);
}


/*
In the Dart programming language, the break statement is used to exit from loops or switch statements. 

In this example, a for loop is used to iterate from 0 to 9. Inside the loop, an if statement checks if the current value of i is equal to 5. When i is equal to 5, the break statement is executed, which terminates the loop immediately. As a result, only the numbers 0 to 4 are printed.

When you run this Dart code, it will output: 0 1 2 3 4
*/
 String fruit = 'apple';

  switch (fruit) {
    case 'apple':
      print('Selected fruit: Apple');
      break;
    case 'banana':
      print('Selecte fruit: Banana');
      break;
    default:
      print('Unknown fruit');
  }

/*
In this example, the switch statement checks the value of the fruit variable. When fruit is equal to 'apple', the corresponding code block is executed, and the break statement exits the switch statement.

When you run this Dart code, it will output:
Selected fruit: Apple

The break statement plays a crucial role in controlling the flow of your Dart program, allowing you to exit loops or terminate switch statements as needed.
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 for (let i = 0; i < 5; i++) {
    if (i === 3) {
        break;
    }
    console.log(i);
}



/*
In this example, we have a for loop that iterates from 0 to 4. However, when the value of i is 3, the break statement is encountered, and the loop is immediately terminated. The program will continue executing the code after the loop.

When you run this code, it will output: 0 1 2 3

As soon as i becomes 3, the break statement is executed, and the loop is exited. The number 3 is not printed because the loop terminates before reaching that iteration.
*/

/*
The break statement can also be used in a switch statement to exit the switch block prematurely. Here's an example:
*/
let fruit = "apple";

switch (fruit) {
    case "apple":
        console.log("Selected fruit: Apple");
        break;
    case "banana":
        console.log("Selected fruit: Banana");
        break;
    default:
        console.log("Unknown fruit");
        break;
}

/*
In this case, when fruit is "apple", the code block associated with the case "apple" is executed. The break statement terminates the switch block, preventing the execution of subsequent cases.

*/

\```

\```php {}
for ($i = 0; $i < 10; $i++) {
    if ($i == 5) {
        break;
    }
    echo $i . "\n";
}


/*
In this example, a for loop is used to iterate from 0 to 9. Inside the loop, an if condition checks if the value of $i is equal to 5. If the condition is true, the break statement is executed, and the loop is terminated prematurely.

When you run this PHP code, it will output: 0 1 2 3 4

The loop runs until $i is equal to 5, and then the break statement is encountered, causing the loop to exit immediately. As a result, only the numbers 0 to 4 are printed.

*/

\```


\```java {}
for (int i = 0; i < 10; i++) {
    if (i == 5) {
      break;
    }
     System.out.println(i);
}


/*
In this example, a for loop is used to iterate from 0 to 9. Within the loop, there's an if statement that checks if i is equal to 5. If the condition is true, the break statement is encountered, and the loop is terminated immediately.

When you run this program, it will output: 0 1 2 3 4 

As soon as i becomes 5, the break statement is executed, and the loop is terminated. Thus, only the numbers 0 to 4 are printed to the console.
*/

\```

\```kotlin {}

val fruits = listOf("apple", "banana", "orange", "pear", "grape")

for (fruit in fruits) {
    if (fruit == "orange") {
      println("Found orange!")
        break
    }
    println("Current fruit: $fruit")
}


/*
In this example, we have a list of fruits, and we iterate over each fruit using a for loop. 
Inside the loop, we check if the current fruit is equal to "orange". 
If it is, we print "Found orange!" and then use the break statement to exit the loop immediately. 
If the condition is not met, we print the current fruit.

When you run this program, it will output:
Current fruit: apple
Current fruit: banana
Found orange!

As soon as the break statement is encountered when the fruit is "orange", the loop is terminated, and the program continues with the next line of code after the loop.

*/


\```

\```c++ {title: 'C/C++'}
for (int i = 0; i < 10; i++) {
    if (i == 5) {
        break;
    }
  std::cout << i << std::endl;
}



/*
In this example, the break statement is used within a for loop. The loop iterates from 0 to 9, but when i equals 5, the break statement is encountered. As a result, the loop is terminated, and the program moves on to the next line of code after the loop.

When you run this program, it will output: 0 1 2 3 4

The loop stops when i becomes 5 due to the break statement, so the numbers 0 to 4 are printed. After that, the program exits the loop and continues with the next line of code.

The break statement can also be used in other control structures such as switch statements. Its purpose remains the same—to exit the innermost loop or terminate the execution of a switch statement.

Feel free to modify the example and experiment with the break statement to suit your specific needs.
*/
\```

\```objective-c {}
for (int i = 0; i < 10; i++) {
    if (i == 5) {
        break;
    }
NSLog(@"%d", i);
}


/*
In this example, the break statement is used within a for loop. The loop iterates from 0 to 9, but when i equals 5, the break statement is encountered, and the loop is immediately terminated. The program then continues with the next line of code after the loop.

When you run this Objective-C program, it will output: 0 1 2 3 4
 */
\```

\```swift {}
for number in 1...10 {
    if number == 5 {
        break
    }
    print(number)
}



/*
In this example, we have a for loop that iterates from 1 to 10. Inside the loop, there is an if statement that checks if the current number is equal to 5. If the condition is true, the break statement is executed, and the loop is terminated.

When you run this code, it will output: 1 2 3 4
*/

/*
The break statement can also be used with switch statements in Swift to exit the switch block

*/

let fruit = "apple"

switch fruit {
case "apple":
    print("Selected fruit: Apple")
    break
case "banana":
    print("Selected fruit: Banana")
    break
default:
    print("Unknown fruit")
}

/*
In this example, when fruit is "apple", the code block associated with the case "apple" is executed. The break statement immediately exits the switch statement, preventing the execution of subsequent cases.

*/

\```

\```go {}
for i := 0; i < 5; i++ {
 if i == 3 {
	break
}
fmt.Println(i)
}

/*
In this example, the for loop runs from i=0 to i=4. However, when i equals 3, the break statement is encountered, causing an immediate exit from the loop. As a result, the loop terminates, and the program continues with the next line of code after the loop.

When you run this program, it will output: 0 1 2
0
1
2

As you can see, the loop is terminated when i becomes 3 because of the break statement. The numbers 0, 1, and 2 are printed to the console, and the loop ends without further iterations.

*/
\```

```


## <a name="a5" href="#b5">5.</a> Continue Statement in various programming languages

The continue statement is a control flow statement that is commonly used within loops. It allows you to skip the remaining code within the current iteration of a loop and move on to the next iteration. When the continue statement is encountered, the program immediately jumps to the next iteration without executing any further statements in the loop for that particular iteration.


**Continue statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have continue statements to execute blocks of codes.
Lets check continue statements in the above languages

```tabs

\```dart {}
for (var i = 0; i < 5; i++) {
    if (i == 2) {
      continue;
    }
    print(i);
}


/*
In this example, the for loop runs from i=0 to i=4. When i equals 2, the continue statement is encountered.
As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 0 1 3 4

*/


\```

\```javascript {title: 'JavaScript/TypeScript'}

 for (let i = 0; i < 5; i++) {
  if (i === 2) {
    continue;
  }
  console.log(i);
}


/*
In this example, the for loop runs from i = 0 to i < 5. However, when i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this code, it will output: 0 1 3 4
*/


\```

\```php {}

for ($i = 0; $i < 5; $i++) {
    if ($i == 2) {
        continue;
    }
    echo $i . "\n";
}

/*
In this PHP example, the for loop runs from $i=0 to $i=4. When $i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this code, it will output: 0 1 3 4
*/


\```


\```java {}
 for (int i = 0; i < 5; i++) {
    if (i == 2) {
        continue;
            }
    System.out.println(i);
 }


/*
In this example, the for loop runs from i=0 to i=4. However, when i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 0 1 3 4
*/

\```

\```kotlin {}

 for (i in 0 until 5) {
    if (i == 2) {
        continue
    }
    println(i)
}


/*
In this Kotlin example, the for loop runs from i=0 to i=4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 0 1 3 4
*/


\```

\```c++ {title: 'C/C++'}

 for (int i = 0; i < 5; i++) {
    if (i == 2) {
     continue;
}
  std::cout << i << std::endl;
}

/*
In this example, the for loop runs from i=0 to i=4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 0 1 3 4
*/
\```

\```objective-c {}

for (int i = 0; i < 5; i++) {
    if (i == 2) {
      continue;
}
        NSLog(@"%d", i);
}
/*
In this Objective-C example, we have a for loop that iterates from i=0 to i=4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 0 1 3 4
 */
\```

\```swift {}
for i in 0..<5 {
    if i == 2 {
        continue
    }
    print(i)
}

/*
In this example, the for loop iterates over the range from 0 to 4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 0 1 3 4
*/



\```

\```go {}
for i := 0; i < 5; i++ {
		if i%2 == 0 {
			continue
		}
		fmt.Println(i)
}

/*
In this example, the for loop runs from i=0 to i=4. However, when i is an even number (divisible by 2), the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output: 1 3
*/
\```

```

## <a name="a6" href="#b6">6.</a> Return Statement in verious programming languages

In programming, a return statement is used to exit a function and optionally provide a value back to the caller of that function.
When a return statement is executed, the control flow of the program returns to the point where the function was called, and the value specified in the return statement (if any) is passed back.


**Return statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, use return statements in some operations.

```tabs

\```dart {}
int addNumbers(int a, int b) {
  int sum = a + b;
  return sum;
}

int result = addNumbers(5, 3);
print('The sum is: $result');



/*
In this example, we have a function called addNumbers that takes two integer parameters, a and b. Inside the function, we calculate the sum of a and b and store it in the variable sum. Then, we use the return statement return sum to exit the function and return the value of sum back to the caller.

In the main function, we call addNumbers(5, 3) and assign the returned value to the variable result. Finally, we print the value of result using the print statement.

When you run this Dart code, it will output:
The sum is: 8
*/


\```

\```javascript {title: 'JavaScript/TypeScript'}

 function addNumbers(a, b) {
  var sum = a + b;
  return sum;
}

var result = addNumbers(3, 5);
console.log(result); // Output: 8


/*
In this example, we have a function called addNumbers that takes two parameters, a and b. Inside the function, we calculate the sum of a and b and store it in a variable called sum. Then, we use the return statement to pass the value of sum back to the caller.

Outside the function, we call addNumbers(3, 5), passing in the arguments 3 and 5. The function calculates the sum and returns it. We store the returned value in the variable result. Finally, we log the value of result to the console, which displays 8.
*/


\```

\```php {}
function addNumbers($num1, $num2) {
    $sum = $num1 + $num2;
    return $sum;
}

$result = addNumbers(5, 7);
echo $result; // Output: 12


/*
In the above example, we have a function called addNumbers that takes two parameters $num1 and $num2. Inside the function, the sum of these two numbers is calculated and stored in the variable $sum. The return statement is used to exit the function and return the value of $sum back to the caller.

The function is then called with arguments 5 and 7, and the returned value is assigned to the variable $result. Finally, the value of $result is echoed, which outputs 12 in this case.
*/


\```


\```java {}
public static int addNumbers(int a, int b) {
 int sum = a + b;
 return sum;
}

int result = addNumbers(5, 10);
System.out.println("The sum is: " + result);



/*
In this example, we have a method called addNumbers that takes two integer parameters a and b. Inside the method, we calculate the sum of a and b and store it in the variable sum. Then, the return statement is used to exit the method and pass the value of sum back to the caller.

Finally, we print the result to the console, which would output:
The sum is: 15
*/

\```

\```kotlin {}

fun multiply(a: Int, b: Int): Int {
    val result = a * b
    return result
}


/*
In the code snippet above, we have a function named multiply that takes two parameters a and b, both of type Int. Inside the function, we calculate the multiplication of a and b and store the result in a variable called result. Finally, we use the return statement to exit the function and return the value of result back to the caller.

You can call this function and use the returned value like this:

val product = multiply(5, 6)
println("Product: $product") // Output: Product: 30

*/


\```

\```c++ {title: 'C/C++'}

int multiply(int a, int b) {
int result = a * b;
    return result;  // Returning the calculated result
}


int x = 5;
int y = 3;
int product = multiply(x, y);  // Calling the multiply function

std::cout << "The product of " << x << " and " << y << " is: " << product << std::endl;


/*
In the above example, we have a function named multiply that takes two integers a and b as parameters. It calculates their product and assigns it to a variable named result. The return statement is then used to exit the function and return the value of result back to the caller.

When you run the program, it will output:
The product of 5 and 3 is: 15
*/
\```

\```objective-c {}
int multiply(int a, int b) {
    int product = a * b;
    return product;
}

int result = multiply(5, 10);
NSLog(@"The result is %d", result);




/*
In this example, we have a function named multiply that takes two integer parameters a and b. Inside the function, we declare a variable product and assign the product of a and b to it.

The return statement is used to return a value from the function.
 */
\```

\```swift {}
func addNumbers(a: Int, b: Int) -> Int {
    let sum = a + b
    return sum
}

let result = addNumbers(a: 3, b: 5)
print(result) // Output: 8


/*
In this example, we have a function called addNumbers that takes two integer parameters a and b. Inside the function, we calculate the sum of a and b and store it in the sum variable. The return statement is then used to exit the function and pass the value of sum back to the caller.

We call the addNumbers function with the arguments a: 3 and b: 5 and assign the returned value to the result constant. Finally, we print the value of result, which is 8 in this case.

Note that the return type of the addNumbers function is specified as Int after the arrow (->) in the function signature. This indicates that the function will return an integer value.
*/



\```

\```go {}

func addNumbers(a, b int) int {
	sum := a + b
	return sum
}

result := addNumbers(3, 5)
	fmt.Println(result)


/*
In this example, we define a function addNumbers that takes two integer parameters a and b. Inside the function, we calculate the sum of a and b and assign it to the variable sum. Finally, we use the return statement to return the value of sum.
*/
\```

```


We also provided some AI prompts for other popular coding languages that were not mentioned in this unit:

```yml-list {default: true}
- "Using code examples to explain Ruby language's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain Rust language's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain C# language's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain Lua script's syntax: white spaces, line breaks, comments and code block etc."
- "Using code examples to explain Bash script's syntax: white spaces, line breaks, comments and code block etc."
```