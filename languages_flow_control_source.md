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



**if statements:**

An if statement allows you to execute a block of code only if a certain condition is true. It has the following syntax:
``` python
if condition:
    # Code to execute if condition is true

```

**If statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, share some similarities in their "if" statements.
Lets check if statements in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() { 
   var  num=5; 
   if (num>0) { 
      print("number is positive"); 
   }    
}
// The above example will print “number is positive” as the condition specified by the if block is true.

\```

\```javascript {title: 'JavaScript/TypeScript'}
//Make a "Good day" greeting if the hour is less than 18:00:

function checkHour() {
let hour = 13
if (hour < 18) {
  greeting = "Good day";
}
}

//The result of greeting will be "Good day"

\```

\```php {}
// Output "Hello, JuniorIT.AI!" if the current time (HOUR) is less than 20:
<?php
$t = date("H");

if ($t < "20") {
  echo "Hello, JuniorIT.AI!";
}
?>
//As long as the time is less than 20, it will print "Hello, JuniorIT.AI
\```


\```java {}
// If x is greater than y is going to print "x is greater than y"
int x = 20;
int y = 18;
if (x > y) {
  System.out.println("x is greater than y");
}


\```

\```kotlin {}

val x = 20
val y = 18
if (x > y) {
  println("x is greater than y")
}

//In the example above we use two variables, x and y, to test whether x is greater than y (using the > operator). 
//As x is 20, and y is 18, and we know that 20 is greater than 18, we print to the screen that "x is greater than y".
\```

\```c++ {title: 'C/C++'}
// # symbol is preprocessor directive
#include <iostream>

int main() {
    if (20 > 18) {
        std::cout << "20 is greater than 18." << std::endl;
    }
    

    return 0;
}
//In the example above, we test two values to find out if 20 is greater than 18. If the condition is true, print some text:

\```

\```objective-c {}
// # symbol is preprocessor directive, not comment
#import <Foundation/Foundation.h>

int main(int argc, const char * argv[]) {
    NSAutoreleasePool * pool = [[NSAutoreleasePool alloc] init];

    /* local variable definition */
   int a = 10;
 
   /* check the boolean condition using if statement */
   if( a < 20 ) {
      /* if condition is true then print the following */
      NSLog(@"a is less than 20\n" );
   }
   
   NSLog(@"value of a is : %d\n", a);
   return 0;

   //When the above code is compiled and executed, it produces the following result

   //2013-09-07 22:07:00.845 demo[13573] a is less than 20
   //2013-09-07 22:07:00.845 demo[13573] value of a is : 10
}
\```

\```swift {}
var num1: Int = 40

if num1 > 20 {

print("Number Greater than 20")
/*
If you observe above example we are checking the condition whether the value of “num1” greater 20 or not.
When we execute the above code, we will get "Number Greater than 20"
*/

}

\```

\```go {}
// Single line comment 
package main
import ("fmt")

func main() {
  if 20 > 18 {
    fmt.Println("20 is greater than 18")
  }
}

//In the example above, we test two values to find out if 20 is greater than 18. If the condition is true, print some text:
\```

```


**If-else statement:**

The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed.
``` python
if condition:
    # code to be executed if the condition is true
else:
    # code to be executed if the condition is false


```

**If-else statement in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, share some similarities in their "if else" statements.
Lets check if else  statements in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  int age = 18;

  if (age >= 18) {
    print("You are eligible to vote!");
  } else {
    print("You are not eligible to vote yet.");
  }
}
/*In this example, we declare an age variable with a value of 18. The if statement checks whether the age is greater than or equal to 18. 
If the condition is true, it executes the code inside the if block and prints the message "You are eligible to vote!". 
Otherwise, if the condition is false, it executes the code inside the else block and prints the message "You are not eligible to vote yet."*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 function ageCheck() {
 let age = 18;

if (age >= 18) {
  console.log("You are eligible to vote!");
} else {
  console.log("You are not eligible to vote yet.");
}

 }

/*In this example, we have a variable age with a value of 18. The if statement checks if the age is greater than or equal to 18.
 If the  condition is true, it executes the code inside the if block and logs the message "You are eligible to vote!" to the console. 
 therwise, if the condition is false, it executes the code inside the else block and logs the message "You are not eligible to vote yet." 
 to the console.*/

\```

\```php {}
<?php
$age = 25;

if ($age >= 18) {
    echo "You are eligible to vote.";
} else {
    echo "You are not eligible to vote.";
}
?>


/*
In this example, we have a variable $age that stores the value 25. The if-else statement checks whether the value of $age is greater than or 
equal to 18. If it is, it will execute the code block inside the if statement and display the message "You are eligible to vote." 
Otherwise, it will execute the code block inside the else statement and display the message "You are not eligible to vote."
 */

\```


\```java {}
public class Example {
    public static void main(String[] args) {
        int age = 25;

        if (age >= 18) {
            System.out.println("You are eligible to vote.");
        } else {
            System.out.println("You are not eligible to vote.");
        }
    }
}

/*In this example, we have a variable age that stores the value 25. The if-else statement checks whether the value of age is greater than or 
equal to 18. If it is, it will execute the code block inside the if statement and print the message "You are eligible to vote." Otherwise, 
it will execute the code block inside the else statement and print the message "You are not eligible to vote."

So, in this case, since the value of age is 25 (which is greater than 18), the output will be: "You are eligible to vote" */

\```

\```kotlin {}

fun main() {
    val age = 25

    if (age >= 18) {
        println("You are eligible to vote.")
    } else {
        println("You are not eligible to vote.")
    }
}
/*In this example, we have a variable age that stores the value 25. The if-else statement checks whether the value of age is greater than or 
equal to 18. If it is, it will execute the code block inside the if statement and print the message "You are eligible to vote." Otherwise, 
it will execute the code block inside the else statement and print the message "You are not eligible to vote."

So, in this case, since the value of age is 25 (which is greater than 18), the output will be: "You are eligible to vote."*/
\```

\```c++ {title: 'C/C++'}
// # symbol is preprocessor directive
#include <iostream>

int main() {
    int age = 25;

    if (age >= 18) {
        std::cout << "You are eligible to vote." << std::endl;
    } else {
        std::cout << "You are not eligible to vote." << std::endl;
    }

    return 0;
}
/*In this example, we have a variable age that stores the value 25. The if-else statement checks whether the value of age is greater than or 
equal to 18. If it is, it will execute the code block inside the if statement and print the message "You are eligible to vote." Otherwise, 
it will execute the code block inside the else statement and print the message "You are not eligible to vote."

So, in this case, since the value of age is 25 (which is greater than 18), the output will be: "You are eligible to vote."
*/
\```

\```objective-c {}
int number = 10;

if (number > 0) {
    NSLog(@"The number is positive.");
} else if (number < 0) {
    NSLog(@"The number is negative.");
} else {
    NSLog(@"The number is zero.");
}

/*In this example, we have an integer variable number assigned a value of 10. The if statement checks the value of number using the condition 
number > 0. If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive." to the 
console using NSLog(). If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number 
is negative." is printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/
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
/*In this example, we have a constant number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. 
If the condition evaluates to true, the code inside the if block is executed, 
which prints "The number is positive." to the console using print(). 
If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number is negative." is 
printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/

\```

\```go {}
package main

import "fmt"

func main() {
    number := 10

    if number > 0 {
        fmt.Println("The number is positive.")
    } else if number < 0 {
        fmt.Println("The number is negative.")
    } else {
        fmt.Println("The number is zero.")
    }
}
/*
In this example, we have a variable number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. 
If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive." to the console using 
fmt.Println(). If the condition is false, the code inside the else if block is checked, 
and if that condition is true, "The number is negative.
" is printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/
\```

```


**if-else if-else statement:**

An if-else if-else statement is a control structure used in programming languages to execute different blocks of code based on multiple conditions. It provides a way to check multiple conditions in sequence and perform different actions depending on the outcome of those conditions.

The basic structure of an if-else if-else statement is as follows:
``` python
if condition1 {
    // Code to execute if condition1 is true
} else if condition2 {
    // Code to execute if condition1 is false and condition2 is true
} else {
    // Code to execute if both condition1 and condition2 are false
}



```

**If-else if-else statement in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, share some similarities in their "if-else if-else" statements.
Lets check if-else if-else  statements in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  int number = 10;

  if (number > 0) {
    print("The number is positive.");
  } else if (number < 0) {
    print("The number is negative.");
  } else {
    print("The number is zero.");
  }
}

/*
In this example, we have a variable number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. 
If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive." to the console using 
print(). If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number is negative." 
is printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 function checkNumber() {
 let number = 10;

if (number > 0) {
  console.log("The number is positive.");
} else if (number < 0) {
  console.log("The number is negative.");
} else {
  console.log("The number is zero.");
}


 }

/*
In this example, we have a variable number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. 
If the condition evaluates to true, the code inside the if block is executed, which logs "The number is positive." to the console using 
console.log(). If the condition is false, the else if block is checked, and if that condition is true (number < 0), "The number is negative.
" is logged. If both conditions are false, the code inside the else block is executed, which logs "The number is zero."
*/

\```

\```php {}
$number = 10;

if ($number > 0) {
    echo "The number is positive.";
} else if ($number < 0) {
    echo "The number is negative.";
} else {
    echo "The number is zero.";
}

/*
In this example, we have a variable $number assigned a value of 10. 
The if statement checks the value of $number using the condition $number > 0. 
If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive." to the output using 
echo. 
If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number is negative." is 
printed. I
if both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/

\```


\```java {}
public class Main {
    public static void main(String[] args) {
        int number = 10;

        if (number > 0) {
            System.out.println("The number is positive.");
        } else if (number < 0) {
            System.out.println("The number is negative.");
        } else {
            System.out.println("The number is zero.");
        }
    }
}


/*
In this example, we have a variable number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. 
If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive."
 to the console using System.out.println(). 
If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number is negative." is 
printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/

\```

\```kotlin {}

fun main() {
    val number = 10

    if (number > 0) {
        println("The number is positive.")
    } else if (number < 0) {
        println("The number is negative.")
    } else {
        println("The number is zero.")
    }
}

/*
In this example, we have a variable number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. If the condition evaluates to true, 
the code inside the if block is executed, which prints "The number is positive." to the console using println().
 If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number is negative." is 
printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/
\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    int number = 10;

    if (number > 0) {
        std::cout << "The number is positive." << std::endl;
    } else if (number < 0) {
        std::cout << "The number is negative." << std::endl;
    } else {
        std::cout << "The number is zero." << std::endl;
    }

    return 0;
}
/*
In this example, we have a variable number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0.
 If the condition evaluates to true, the code inside the if block is executed, which outputs "The number is positive."
to the console using std::cout. If the condition is false, the code inside the else if block is checked, 
and if that condition is true, "The number is negative." is outputted. 
If both conditions are false, the code inside the else block is executed, which outputs "The number is zero."
*/
\```

\```objective-c {}
int number = 10;

if (number > 0) {
    NSLog(@"The number is positive.");
} else if (number < 0) {
    NSLog(@"The number is negative.");
} else {
    NSLog(@"The number is zero.");
}

//In this example, we have an integer variable number assigned a value of 10. 
//The if statement checks the value of number using the condition number > 0. 
//If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive."
 //to the console using NSLog(). If the condition is false, the next condition number < 0 is evaluated. 
 //If it is true, the code inside the else if block is executed, which prints "The number is negative." 
 //If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
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
/*In this example, we have a constant number assigned a value of 10. 
The if statement checks the value of number using the condition number > 0. 
If the condition evaluates to true, the code inside the if block is executed, 
which prints "The number is positive." to the console using print(). 
If the condition is false, the code inside the else if block is checked. 
If that condition is true, "The number is negative." is printed. 
If both conditions are false, the code inside the else block is executed, which prints "The number is zero."

This if-else if-else statement allows you to handle multiple cases and 
execute different blocks of code based on the specific condition that evaluates to true.
*/

\```

\```go {}
package main

import "fmt"

func main() {
    number := 10

    if number > 0 {
        fmt.Println("The number is positive.")
    } else if number < 0 {
        fmt.Println("The number is negative.")
    } else {
        fmt.Println("The number is zero.")
    }
}

/*
In this example, we have a variable number assigned a value of 10. The if statement checks the value of number using the condition number > 0. If the condition evaluates to true, the code inside the if block is executed, which prints "The number is positive." to the console using fmt.Println(). If the condition is false, the code inside the else if block is checked, and if that condition is true, "The number is negative." is printed. If both conditions are false, the code inside the else block is executed, which prints "The number is zero."
*/
\```

```


**Terbary operators**

A ternary operator, also known as the conditional operator, is a compact syntax for expressing conditional statements in many programming languages. It allows you to conditionally assign a value to a variable or express a condition in a concise manner.

The syntax of the ternary operator typically takes the following form:

``` python
condition ? value1 : value2

```

**Ternary operatos  in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have ternary operators for conditional operations.
Lets check ternary operators in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  int number = 10;

  String result = number > 0 ? "Positive" : "Non-positive";
  print(result);
}


/*
In this example, the condition number > 0 is evaluated. If the condition is true, the value "Positive" is assigned to the result variable; otherwise, the value "Non-positive" is assigned. The value of result is then printed to the console.

The ternary operator in Dart follows the same syntax as many other programming languages, with the condition ? value1 : value2 structure.
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 let number = 10;

let result = number > 0 ? "Positive" : "Non-positive";
console.log(result);


/*
In this example, the condition number > 0 is evaluated. If the condition is true, the value "Positive" is assigned to result; otherwise, the value "Non-positive" is assigned. The value of result is then logged to the console using console.log().

The ternary operator in JavaScript is commonly used for simple conditional assignments or expressions where you want to choose between two values based on a condition.
*/

\```

\```php {}
$number = 10;

$result = ($number > 0) ? "Positive" : "Non-positive";
echo $result;


/*
In this example, the condition $number > 0 is evaluated. If the condition is true, the value "Positive" is assigned to the variable $result; otherwise, the value "Non-positive" is assigned. The value of $result is then echoed to the output.

The ternary operator in PHP follows the syntax (condition) ? value1 : value2, where value1 is returned if the condition is true, and value2 is returned if the condition is false. It provides a concise way to express conditional logic in a single line of code.
*/

\```


\```java {}
public class TernaryExample {
    public static void main(String[] args) {
        int number = 10;
        
        String result = (number > 0) ? "Positive" : "Non-positive";
        System.out.println(result);
    }
}



/*
In this example, we have a variable number assigned a value of 10. The ternary operator ? : is used to evaluate the condition (number > 0). If the condition is true, the value "Positive" is assigned to the result variable; otherwise, the value "Non-positive" is assigned. Finally, the value of result is printed to the console using System.out.println().

The ternary operator in Java follows the same general syntax: condition ? value1 : value2. The condition is evaluated, and depending on whether it's true or false, either value1 or value2 is returned or assigned accordingly.
*/

\```

\```kotlin {}

fun main() {
    val number = 10

    val result = if (number > 0) "Positive" else "Non-positive"
    println(result)
}


/*
In this example, the condition number > 0 is evaluated. If the condition is true, the value "Positive" is assigned to the variable result; otherwise, the value "Non-positive" is assigned. The value of result is then printed to the console using println().

Kotlin does not have a dedicated ternary operator like some other languages. Instead, you can achieve the same functionality using the if-else expression, as shown in the example. The if-else expression in Kotlin can act as a ternary operator by evaluating the condition and returning the corresponding value based on the condition.
*/
\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    int number = 10;

    std::string result = (number > 0) ? "Positive" : "Non-positive";
    std::cout << result << std::endl;

    return 0;
}



/*
In this example, we have a variable number assigned a value of 10. The ternary operator (number > 0) ? "Positive" : "Non-positive" is used to conditionally assign the value "Positive" to the variable result if the condition number > 0 evaluates to true. Otherwise, the value "Non-positive" is assigned. The value of result is then printed to the console using std::cout.

Please note that in C++, the ternary operator is commonly used for conditional expressions, but it can also be used for assignments or other expressions where the result depends on a condition.
*/
\```

\```objective-c {}
int number = 10;
NSString *result = (number > 5) ? @"Greater than 5" : @"Less than or equal to 5";
NSLog(@"%@", result);


/*
In this example, we have a variable number assigned a value of 10. The ternary operator ? : is used to assign different values to the result variable based on the condition (number > 5).

If the condition is true (i.e., number is greater than 5), the value "Greater than 5" is assigned to result. Otherwise, if the condition is false (i.e., number is less than or equal to 5), the value "Less than or equal to 5" is assigned to result.

Finally, the result value is logged to the console using NSLog.
 */
\```

\```swift {}
let number = 10

let result = number > 0 ? "Positive" : "Non-positive"
print(result)

/*
In this example, the condition number > 0 is evaluated. If the condition is true, the value "Positive" is assigned to the result variable; otherwise, the value "Non-positive" is assigned. The value of result is then printed to the console using print().

The ternary operator in Swift follows the same syntax as many other programming languages, with the format condition ? value1 : value2. It provides a concise way to express conditional assignments or expressions with a single line of code.
*/

\```

\```go {}
package main

import "fmt"

func main() {
    number := 10

    result := ""
    if number > 0 {
        result = "Positive"
    } else {
        result = "Non-positive"
    }

    fmt.Println(result)
}


/*
In this example, the if-else statement is used to assign the value to the result variable based on the condition number > 0. If the condition is true, "Positive" is assigned to result; otherwise, "Non-positive" is assigned. The value of result is then printed to the console.

While Go does not have a ternary operator, the if-else statement can provide similar conditional assignment or expression evaluation based on conditions.
*/
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

Here's a general structure of a for loop:
``` python
for (initialization; condition; update) {
    // code block to be executed
}


```

**For loops in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have for loops  for iteraction operations.
Lets check for loops in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  for (int i = 0; i < 5; i++) {
    print(i);
  }
}



/*
In this Dart example, the for loop will iterate five times, printing the values of i from 0 to 4. Let's break down the code:
1. The loop starts with the initialization statement int i = 0, where we declare and initialize the control variable i to 0.
2. The condition i < 5 is checked before each iteration. As long as the condition is true, the loop will continue executing.
   Once the condition becomes false, the loop terminates.
3. After each iteration, the update statement i++ increments the value of i by 1.
Note: You can modify the code according to your specific needs, such as changing the initialization value, condition, or update statement. 
      The for loop in Dart follows a similar syntax as in other programming languages, making it easy to understand and use for iterative tasks.
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 for (let i = 0; i < 5; i++) {
    console.log(i);
}

/*
In this example, the loop will execute five times because the condition i < 5 is satisfied. The loop starts with an initialization statement let i = 0, which sets the initial value of the control variable i to 0.

The loop then checks the condition i < 5. As long as the condition is true, the code block inside the loop will be executed. In this case, the code block contains a console.log(i) statement that will print the value of i to the console.

After each iteration, the update statement i++ is executed, incrementing the value of i by 1. This ensures that the loop progresses towards the termination condition.

The output of this loop will be:
0
1
2
3
4

 Note that the let keyword is used to declare the variable i within the scope of the loop. This ensures that i is limited to the loop and not accessible outside of it. If you omit the let keyword, the loop variable i will be scoped globally, which may lead to unintended consequences.

 Note: You can modify the initialization, condition, and update statements based on your specific requirements. The for loop provides a concise and flexible way to iterate over a specific number of iterations or traverse through arrays, lists, or other iterable objects in JavaScript
*/

\```

\```php {}
for ($i = 0; $i < 5; $i++) {
    echo $i . "<br>";
}


/*
In this example, the loop will iterate 5 times. The loop starts with the initialization statement $i = 0, sets the condition $i < 5, and increments the value of $i by 1 after each iteration with $i++.

Inside the loop's code block, the value of $i is echoed along with the HTML line break <br>. The output will be:
0
1
2
3
4

Note: You can customize the initialization, condition, and update statements to suit your specific requirements. 
The for loop in PHP operates similarly to those in other programming languages, allowing you to iterate over a fixed number of iterations or iterate through arrays, database results, or other collections of data.
*/

\```


\```java {}
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}




/*
In this example, the for loop will iterate 5 times. Let's break down the components:
1. Initialization: int i = 0 initializes the control variable i to 0 before the loop begins.
2. Condition: i < 5 specifies the condition that needs to be true for the loop to continue executing.
   As long as i is less than 5, the loop will continue.
3. Update: i++ increments the value of i by 1 after each iteration of the loop.

The loop will print the values of i from 0 to 4 using the System.out.println() statement.
Note: You can modify the initialization, condition, and update statements based on your specific requirements. The for loop in Java follows the same basic structure as in other programming languages, making it a widely used loop construct
*/

\```

\```kotlin {}

for (i in 0 until 5) {
    println(i)
}


/*
In this example, the loop will iterate from 0 to 4 (inclusive). Here's a breakdown of how this for loop works:

1. The control variable i is initialized to 0 (i in 0).
2. The loop will continue as long as i is less than 5. The until keyword is used to specify that the upper bound (5) is exclusive (until 5).
3. The loop body consists of a single statement: println(i), which prints the value of i.
4. After each iteration, the value of i is automatically incremented.

When you run this code, it will print the numbers 0 to 4 on separate lines.

You can also customize the increment or decrement step by specifying it explicitly. For example, to iterate over even numbers from 0 to 10, you can use the following code:
*/

for (i in 0..10 step 2) {
    println(i)
}
/*
In this modified example, the .. operator is used to specify a range from 0 to 10 (inclusive), and the step 2 part indicates that the loop should increment i by 2 in each iteration. This loop will print the even numbers 0, 2, 4, 6, 8, and 10.

Kotlin's for loop is flexible and allows you to iterate over ranges, arrays, collections, and other iterable objects. 
You can customize it according to your specific needs by adjusting the range and loop body.

*/
\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    int number = 10;

    std::string result = (number > 0) ? "Positive" : "Non-positive";
    std::cout << result << std::endl;

    return 0;
}



/*
In this example, we have a variable number assigned a value of 10. The ternary operator (number > 0) ? "Positive" : "Non-positive" is used to conditionally assign the value "Positive" to the variable result if the condition number > 0 evaluates to true. Otherwise, the value "Non-positive" is assigned. The value of result is then printed to the console using std::cout.

Please note that in C++, the ternary operator is commonly used for conditional expressions, but it can also be used for assignments or other expressions where the result depends on a condition.
*/
\```

\```objective-c {}

int main() {
    for (int i = 1; i <= 10; i++) {
        std::cout << i << " ";
    }

    return 0;
}


/*
In this example, the loop initializes the variable i to 1 (int i = 1), executes the loop as long as i is less than or equal to 10 (i <= 10), and increments i by 1 in each iteration (i++).

The std::cout statement inside the loop is used to print the value of i followed by a space. The loop will iterate 10 times, and each iteration will print the value of i from 1 to 10.

When you run this program, the output will be:
1 2 3 4 5 6 7 8 9 10

Note: You can modify the initialization, condition, and update statements to suit your specific requirements in a for loop.
 */
\```

\```swift {}
for i in 0..<5 {
    print(i)
}


/*
In this Swift for loop example, it prints the numbers from 0 to 4. The loop uses a range expression 0..<5 to specify the range of values that i will take.

The ..< operator is a half-open range operator in Swift, which means it includes the starting value (0) but excludes the ending value (5). Therefore, the loop iterates for i values 0, 1, 2, 3, and 4.

Note: You can also use the ... operator for a closed range, where both the starting and ending values are included. Here's an example:
*/

for i in 0...4 {
    print(i)
}

/*
This loop will produce the same output, printing the numbers 0 to 4 inclusively.

You can customize the loop by changing the range expression to suit your specific requirements. Swift's for loop is flexible and allows you to iterate over ranges, arrays, dictionaries, and other collections or sequences.

*/
\```

\```go {}
package main

import "fmt"

func main() {
    for i := 0; i < 5; i++ {
        fmt.Println(i)
    }
}



/*
In this example, the for loop initializes i to 0, executes the loop as long as i is less than 5, and increments i by 1 in each iteration. The fmt.Println(i) statement prints the value of i in each iteration.

When you run this program, it will output:

0
1
2
3
4

The structure of the for loop in Go is similar to other programming languages. The initialization, condition, and update statements are enclosed within the parentheses. The := operator is used for initialization, which both declares and assigns the initial value of i to 0.

Note: You can customize the loop based on your specific needs by modifying the initialization, condition, and update statements within the for loop in Go.
*/
\```

```


**While loops:**

A while loop is a control flow statement that allows you to repeatedly execute a block of code as long as a certain condition is true. The loop continues iterating until the condition becomes false. The syntax of a while loop typically includes the condition and the code block to be executed.

Here's a general structure of a while loop:
```python
while (condition) {
    // code block to be executed
}

```
Let's break down each part of the while loop:

1. Condition: The condition is evaluated before each iteration of the loop. 
   If the condition is true, the loop's code block is executed. If the condition is false, the loop terminates, and the program continues to the next line of code after the loop
2. Code block: The code block contains the statements that will be executed as long as the condition is true. 
   It can be a single statement or  a group of statements enclosed in curly braces.




**While loops in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have while loops  for iteraction operations.
Lets check while loops in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  int i = 0;
  
  while (i < 5) {
    print(i);
    i++;
  }
}


/*
In this example, the while loop is used to print the numbers from 0 to 4. The loop continues as long as i is less than 5. Inside the loop, i is incremented by 1 (i++) after each iteration to eventually terminate the loop when i becomes 5.

When you run this program, it will output:
0
1
2
3
4

The structure of the while loop in Dart is similar to other programming languages. The condition is evaluated before each iteration, and if the condition is true, the code block inside the loop is executed. If the condition is false, the loop terminates, and the program continues with the next line of code after the loop.

Note: You can customize the condition and code block according to your specific requirements. While loops in Dart are useful for repeating a block of code until a certain condition is no longer true.
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

 let i = 0;
while (i < 5) {
    console.log(i);
    i++;
}


/*
In this example, the while loop continues as long as the condition i < 5 is true. 
The loop initializes the variable i to 0, prints its value, and increments i by 1 in each iteration using the i++ statement.

When you run this code, it will output:
0
1
2
3
4

The loop runs 5 times because the condition i < 5 is satisfied. 
The control variable i takes on the values 0, 1, 2, 3, and 4 in each iteration.

Note: You can customize the condition and the code block inside the while loop according to your specific requirements. 
While loops are useful when you want to repeat a block of code until a certain condition becomes false in JavaScript.
*/

\```

\```php {}
<?php
$i = 0;
while ($i < 5) {
    echo $i . "\n";
    $i++;
}
?>



/*
In this example, the while loop initializes $i to 0 and continues to execute the loop as long as $i is less than 5. Inside the loop, $i is incremented by 1 ($i++) to eventually terminate the loop when $i becomes 5. The echo statement is used to print the value of $i in each iteration.

When you run this PHP script, it will output:
0
1
2
3
4

The while loop in PHP follows a similar structure to other programming languages. The condition is specified within the parentheses after the while keyword. The code block within the curly braces {} contains the statements that will be executed as long as the condition is true.

Note: You can customize the condition and the code block according to your specific needs. 
While loops in PHP are useful when you want to repeatedly execute a block of code until a certain condition is no longer true.
*/

\```


\```java {}
public class WhileLoopExample {
    public static void main(String[] args) {
        int i = 0;
        while (i < 5) {
            System.out.println(i);
            i++;
        }
    }
}



/*
In this example, the while loop continues as long as the condition i < 5 is true. The loop iterates from 0 to 4. 
Inside the loop, the value of i is printed using System.out.println(i), and then i is incremented by 1 using i++.

When you run this program, it will output:
0
1
2
3
4
The structure of the while loop in Java is similar to other programming languages. 
The condition is enclosed within parentheses after the while keyword. The loop's code block, enclosed within curly braces, contains the statements that will be executed as long as the condition is true.

Note: You can customize the condition and the statements within the while loop to fit your specific needs. While loops are commonly used in Java to repeat a block of code until a certain condition becomes false.

*/

\```

\```kotlin {}

fun main() {
    var i = 0
    while (i < 5) {
        println(i)
        i++
    }
}

/*
In this example, the while loop continues executing the code block as long as the condition i < 5 is true. Inside the loop, println(i) prints the value of i, and i++ increments i by 1 in each iteration.

When you run this program, it will output:
0
1
2
3
4

The structure of the while loop in Kotlin is similar to other programming languages. 
The condition is enclosed within parentheses, and the code block to be executed is defined within curly braces

Note: You can customize the condition and code block based on your specific needs. 
While loops allow you to repeat a block of code until a certain condition becomes false.
*/

\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    int i = 0;
    while (i < 5) {
        std::cout << i << std::endl;
        i++;
    }
    return 0;
}


/*
In this example, the while loop continues executing as long as i is less than 5. The std::cout << i << std::endl; statement prints the value of i in each iteration. The i++ statement increments the value of i by 1 in each iteration to eventually terminate the loop when i becomes 5.

When you run this program, it will output:
0
1
2
3
4

The structure of the while loop in C++ is similar to other programming languages. The condition is placed inside the parentheses after the while keyword, and the code block to be executed is enclosed in curly braces.

Note: You can customize the condition and code block within the while loop to suit your specific needs.
      While loops are useful when you want to repeat a block of code until a particular condition becomes false in C++
*/
\```

\```objective-c {}
int i = 0;
while (i < 5) {
    NSLog(@"%d", i);
    i++;
}


/*
In this example, the while loop continues as long as the condition i < 5 is true. 
The control variable i is initially set to 0. 
Inside the loop, NSLog is used to print the value of i, and then i is incremented by 1 using the i++ statement.

When you run this program, it will output:
0
1
2
3
4

The structure of the while loop in Objective-C is similar to other programming languages. 
The condition is evaluated before each iteration, and if it is true, the code block inside the loop is executed.
Once the condition becomes false, the loop terminates.

Note: You can customize the condition and code block based on your specific requirements. 
While loops are commonly used when you want to repeat a block of code until a certain condition is no longer true in Objective-C programming.

 */
\```

\```swift {}
var i = 0
while i < 5 {
    print(i)
    i += 1
}


/*
In this example, the while loop continues executing as long as the condition i < 5 is true. Inside the loop, print(i) statement prints the value of i, and i += 1 increments i by 1 in each iteration.

When you run this code, it will output:
0
1
2
3
4

The structure of the while loop in Swift is similar to other programming languages. The condition is placed after the while keyword, and the code block to be executed is enclosed within curly braces.

Note: You can customize the condition and the code block based on your specific requirements.
While loops provide a way to repeat a block of code until a certain condition becomes false in the Swift programming language.
*/

\```

\```go {}
package main

import "fmt"

func main() {
    i := 0
    for i < 5 {
        fmt.Println(i)
        i++
    }
}


/*
In this example, the while loop is achieved using the for keyword in Go. The loop continues as long as i is less than 5. 
Inside the loop, fmt.Println(i) prints the value of i, and i++ increments the value of i by 1 in each iteration.

When you run this program, it will output:

0
1
2
3
4

In Go, the for loop can be used to create both while loops and traditional for loops.
By omitting the initialization and update statements, you effectively create a while loop.

Note: You can customize the condition and code block within the for loop according to your specific requirements. While loops in Go are implemented using the for loop structure, providing flexibility to create different types of loops depending on your needs.
*/
\```

```

**Do-While loops:**

In programming, a do-while loop is a control flow structure that executes a block of code at least once, and then repeats the execution as long as a specified condition is true. The key difference between a do-while loop and a regular while loop is that the condition in a do-while loop is evaluated after executing the code block, ensuring that the block is executed at least once.

Here's a general structure of a do-while loop:
```python
do {
    // code block to be executed
} while (condition)


```
Let's break down each part of the do-while loop:

1. Code block: The code block contains the statements that will be executed at least once and potentially multiple times,
   depending on the condition.
2. Condition: The condition is evaluated after each iteration of the loop. 
   If the condition is true, the loop continues, and the code block is  executed again.
   If the condition is false, the loop terminates, and the program continues to the next line of code after the loop.





**Do-While loops in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have for do-while loops  for iteraction operations.
Lets check do-while loops in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  int i = 0;
  
  do {
    print(i);
    i++;
  } while (i < 5);
}



/*
The Dart programming language does not have a built-in do-while loop like some other languages. However, you can achieve a similar effect using a do-while loop construct with a while loop.

In this example, we initialize i to 0 and then execute the loop's code block. After each iteration, i is incremented by 1 (i++).
The loop continues to iterate as long as the condition i < 5 is true.

When you run this program, it will output:
0
1
2
3
4

While Dart does not have a direct do-while loop construct, this equivalent implementation achieves the same result. 
The code block is executed at least once before checking the condition. If the condition is true, the loop continues; otherwise, it terminates.

Note: You can modify the condition and the code block to suit your specific requirements.
The general idea is to ensure that the code block is executed at least once and then continue looping based on the condition.
*/

\```

\```javascript {title: 'JavaScript/TypeScript'}

let i = 0;

do {
    console.log(i);
    i++;
} while (i < 5);



/*
In JavaScript, there is no direct "do-while" loop construct like in some other programming languages. 
However, you can achieve a similar behavior using a combination of a "do-while" loop using a "while" loop structure.

In this example, the loop will execute the code block at least once and continue executing as long as the condition i < 5 is true.
The variable i is initially set to 0, and the console.log(i) statement is executed before the condition is evaluated.
After each iteration, i is incremented by 1 (i++).

When you run this code, it will output:
0
1
2
3
4

Even though JavaScript doesn't have a direct "do-while" loop, this approach achieves the same effect. 
The code block is executed first, and then the condition is evaluated to determine whether to continue with the loop or not.

Note: Remember to update the control variable and the condition inside the loop to avoid an infinite loop and ensure that the loop termination condition is eventually met.
*/

\```

\```php {}
$i = 0;
do {
    echo $i . "<br>";
    $i++;
} while ($i < 5);




/*
In this example, the do-while loop will print the numbers from 0 to 4. 
The initial value of the variable $i is 0, and the loop continues as long as $i is less than 5. 
Inside the loop, $i is incremented by 1 ($i++). 
The code block is executed at least once before the condition is checked.

When you run this PHP code, it will output:
0
1
2
3
4

The loop runs 5 times because the condition $i < 5 is satisfied. The control variable $i takes on the values 0, 1, 2, 3, and 4 in each iteration.
Note: The do-while loop is useful when you want to ensure that the code block is executed at least once, regardless of the condition. It's particularly helpful when you need to process a block of code and then check the condition for further iterations.
*/

\```


\```java {}
public class DoWhileExample {
    public static void main(String[] args) {
        int i = 0;
        do {
            System.out.println(i);
            i++;
        } while (i < 5);
    }
}


/*
In this example, the loop will print the numbers from 0 to 4. The variable i is initially set to 0, and the loop executes the code block which includes printing i and incrementing i by 1. Then, the condition i < 5 is checked. If the condition is true, the loop continues to execute the code block again. The loop terminates when the condition becomes false.

When you run this program, it will output:
0
1
2
3
4

The do-while loop guarantees that the code block will be executed at least once, regardless of the condition. After the first execution, the condition is evaluated, and if it remains true, the loop continues executing.

Note: Remember to update the condition within the loop body to ensure that it will eventually become false, avoiding an infinite loop.

*/

\```

\```kotlin {}

fun main() {
    var i = 0
    do {
        println(i)
        i++
    } while (i < 5)
}


/*
In this example, the loop will print the numbers from 0 to 4. The variable i is initially set to 0, and the loop's code block is executed. Then, the condition i < 5 is checked. If the condition is true, the loop continues, and i is incremented by 1 in each iteration. The loop terminates when i becomes 5.

When you run this program, it will output:
0
1
2
3
4

The do-while loop ensures that the code block is executed at least once, regardless of the condition. 
After the first execution, the condition is checked, and if it evaluates to true, the loop continues executing.

Note: You can customize the code block and the condition according to your specific requirements. 
Do-while loops are useful when you want to ensure that a certain code block executes at least once, even if the condition is initially false.

*/

\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    int i = 0;
    do {
        std::cout << i << std::endl;
        i++;
    } while (i < 5);
    
    return 0;
}

/*
In this example, the do-while loop initializes i to 0 and executes the code block inside the loop. The loop continues executing as long as i is less than 5. Inside the loop, i is incremented by 1 (i++) to eventually terminate the loop when i becomes 5.

When you run this program, it will output:
0
1
2
3
4

The loop runs 5 times because the condition i < 5 is satisfied. The control variable i takes on the values 0, 1, 2, 3, and 4 in each iteration.

Note: You can customize the code block and condition according to your specific requirements. 
Do-while loops are useful when you need to execute a block of code at least once, regardless of the condition, 
and then repeat it as long as the condition is true.

*/
\```

\```objective-c {}
int i = 0;
do {
    NSLog(@"%d", i);
    i++;
} while (i < 5);



/*
In Objective-C, the traditional do-while loop is not available. However, you can achieve similar functionality using a while loop with a slight modification.
In this example, the code block within the do statement is executed first, and then the condition i < 5 is checked. If the condition is true, the loop continues executing. If the condition is false, the loop terminates, and the program moves on to the next line of code after the loop.

When you run this program, it will output:
0
1
2
3
4

Note: Even though Objective-C doesn't have a dedicated do-while loop construct, this approach achieves the same effect by executing the code block at least once before evaluating the condition. You can customize the condition and code block as per your specific requirements.

 */
\```

\```swift {}
var i = 0
repeat {
    print(i)
    i += 1
} while i < 5



/*
In Swift, the traditional do-while loop has been replaced with the repeat-while loop. The repeat-while loop is a control flow statement that executes a block of code repeatedly until a condition becomes false. The block of code is always executed at least once because the condition is checked at the end of each iteration. Here's an example of a repeat-while loop in Swift:

In this example, the loop will print the numbers from 0 to 4. The loop is executed at least once because the condition is checked at the end of each iteration. The variable i is initially set to 0, and the loop continues as long as i is less than 5. Inside the loop, i is incremented by 1 (i += 1) to eventually terminate the loop when i becomes 5.

When you run this code, it will output:
0
1
2
3
4

The repeat-while loop in Swift ensures that the code block is executed before checking the condition. This is similar to the behavior of the traditional do-while loop in other programming languages.

Note: You can customize the condition and the code block inside the repeat-while loop based on your specific needs. Repeat-while loops are helpful when you want to ensure that a block of code is executed at least once, regardless of the condition.
*/

\```

\```go {}
package main

import "fmt"

func main() {
    i := 0
    for {
        fmt.Println(i)
        i++
        if i >= 5 {
            break
        }
    }
}



/*
In Go language, there is no specific do-while loop construct. However, you can achieve a similar behavior using a for loop with a break statement.

In this example, the for loop runs indefinitely until the break statement is encountered. Inside the loop, fmt.Println(i) statement prints the value of i, which starts from 0. Then, i is incremented by 1 (i++). The if i >= 5 condition checks if i has reached 5 or more. If the condition is true, the break statement is executed, and the loop terminates.

When you run this program, it will output:
0
1
2
3
4

Note: Although Go doesn't have a built-in do-while loop, you can achieve the same effect using a for loop with a conditional break statement placed at the appropriate position.

*/
\```

```

## <a name="a3" href="#b3">3.</a> Switch statements in different programming languages

A switch statement is a control flow statement found in many programming languages, including Go. It allows you to select and execute different blocks of code based on the value of an expression or variable. The syntax of a switch statement typically includes multiple case statements and an optional default statement.

Here's a general structure of a switch statement:

```golang
switch expression {
case value1:
    // code block executed when expression equals value1
case value2:
    // code block executed when expression equals value2
...
default:
    // code block executed when none of the cases match the expression
}

```
Let's break down each part of the switch statement:
1. Expression: The expression is evaluated, and its value is compared against the values in each case statement. It can be of any type that can be compared for equality, such as integers, strings, or even custom types.

2. Case Statements: Each case statement represents a specific value that the expression is compared against. If the expression matches a case value, the corresponding code block is executed.

3. Code Block: The code block associated with each case statement contains the statements to be executed when the expression matches the case value.

4. Default: The default statement is optional and is executed when none of the case values match the expression. It is typically used as a fallback option.





**Switch statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have switch statements to execute blocks of codes.
Lets check switch statements in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
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

1. The switch keyword initiates the switch statement, followed by the expression to be evaluated (day in this case).

2. Inside the curly braces, you define multiple case statements. Each case represents a specific value that the expression is compared against.

3. When a match is found between the expression and a case value, the code block associated with that case is executed. In this example, each code block contains a console.log() statement to output the corresponding day of the week.

4. The break statement is used after each code block to exit the switch statement and prevent execution of the subsequent code blocks. Without the break, the switch statement would fall through to the next case, executing code blocks until a break or the end of the switch statement is encountered.

5. The default case is optional and is executed when none of the case values match the expression. It serves as a fallback option if none of the other cases are satisfied.

Note: You can customize the switch statement by adding or removing cases, adjusting the code blocks, and modifying the expression to fit your specific requirements. The switch statement in JavaScript provides a concise way to handle multiple conditions based on the value of an expression.
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

Here's the breakdown of the PHP switch statement:

1. The variable $day is evaluated and compared against each case value.

2. If a case value matches the value of $day, the corresponding code block is executed. Each case block ends with a break statement to prevent fall-through, meaning once a matching case is found, the code execution exits the switch statement.

3. If none of the case values match the value of $day, the code block associated with the default case is executed. The default case is optional and serves as a fallback option when no matching cases are found.

Note: You can customize the switch statement by modifying the case values, code blocks, and the default case according to your specific requirements. Switch statements provide an organized way to handle different cases based on the value of an expression in PHP.
*/

\```


\```java {}
public class SwitchExample {
    public static void main(String[] args) {
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
    }
}


/*
In this example, the switch statement compares the value of the variable day against different cases. Since day is 3, the code block associated with the case 3 is executed, and it prints "Wednesday" to the console.

When you run this program, it will output: Wednesday

The syntax of the switch statement in Java is similar to other programming languages. The switch expression is evaluated, and each case value is compared against the expression. The code block associated with the matching case is executed. The break statement is used to exit the switch statement after a case is matched. The default case is optional and is executed when none of the case values match the expression.

Note: You can customize the switch statement by adding or removing case statements and adjusting the code blocks to suit your specific needs. The switch statement provides a convenient way to handle multiple conditions based on the value of an expression in Java.
*/

\```

\```kotlin {}

fun main() {
    val dayOfWeek = 3

    when (dayOfWeek) {
        1 -> println("Monday")
        2 -> println("Tuesday")
        3 -> println("Wednesday")
        4 -> println("Thursday")
        5 -> println("Friday")
        else -> println("Weekend")
    }
}



/*
In this example, the when keyword is used to initiate the switch statement. It compares the value of dayOfWeek against different cases. Since dayOfWeek is 3, the code block associated with 3 -> println("Wednesday") is executed, and it prints "Wednesday" to the console.

When you run this program, it will output: Wednesday

Note: In Kotlin, the when expression is used as a replacement for the traditional switch statement found in some other programming languages. It provides a more flexible and powerful way to handle multiple conditions based on the value of an expression. You can customize the switch statement by adding or removing cases and adjusting the code blocks as needed.

*/


\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
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

    return 0;
}


/*
In this example, the switch statement compares the value of the variable day against different cases. Since day is 3, the code block associated with case 3 is executed, and it prints "Wednesday" to the console.

When you run this program, it will output: Wednesday

The syntax of the switch statement in C++ is similar to the one in Go, with the switch keyword followed by the expression in parentheses. Each case represents a specific value to be compared against the expression. The code block associated with each case is executed when a match is found. The break statement is used to exit the switch statement after executing the corresponding code block. The optional default case is executed when none of the cases match the expression.

Note: You can customize the switch statement by adding or removing cases and adjusting the code blocks to handle different scenarios based on the value of the expression.
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

Each case block is terminated by a break statement to prevent fall-through behavior. The break statement exits the switch statement after executing the corresponding code block. Without the break statement, the code would continue executing the subsequent case blocks until a break or the end of the switch statement is encountered.

The default case is optional and is executed when none of the case values match the expression. It serves as a fallback option when the expression doesn't match any of the specified cases.

Note: You can customize the switch statement by adding or removing case statements and adjusting the code blocks to handle different values or conditions based on your specific requirements. Switch statements provide a convenient way to handle multiple cases based on the value of an expression in Objective-C.
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

If you change the value of fruit to "banana" or "orange", the respective code block will be executed.

The structure of the switch statement in Swift is similar to other programming languages. Each case represents a specific value or pattern that the variable or expression is compared against. The code block associated with the matching case is executed.

You can also use a default case, which is optional, to handle cases when none of the specific cases match the variable or expression being switched on.

Note: Feel free to modify the values and code blocks in the switch statement according to your needs. 
The switch statement in Swift provides a concise and expressive way to handle multiple conditions
based on the value of a variable or expression.
*/

\```

\```go {}
package main

import "fmt"

func main() {
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
}


/*
In this example, the switch statement is used to compare the value of the variable fruit against different cases. Depending on the value of fruit, the corresponding code block is executed.

When you run this program, it will output: 
Selected fruit: Apple

Since the value of fruit is "apple", the code block associated with the case "apple" is executed, and it prints "Selected fruit: Apple" to the console.

You can add more case statements to the switch statement to handle different values of the variable fruit. The default case is optional and is executed when none of the cases match the value of fruit.

Note: Feel free to modify the example and customize the case statements and code blocks according to your specific requirements. 
Switch statements are useful for making decisions based on the value of an expression or variable.

*/
\```

```


## <a name="a4" href="#b4">4.</a> Break statements in different programming languages

The break statement is a control flow statement that is commonly used within loops or switch statements. It allows you to prematurely exit from a loop or terminate the execution of a switch statement. When the break statement is encountered, the program immediately exits the loop or switch statement, and execution continues with the next line of code after the loop or switch.

Here are two common scenarios where the break statement is used:

Loop Termination: Within a loop, when a certain condition is met, you can use the break statement to exit the loop before it has completed all iterations. This is often used when you want to prematurely end the loop based on a specific condition.

Here's a general structure of a break statement:

```golang
for i := 0; i < 10; i++ {
    if i == 5 {
        break
    }
    fmt.Println(i)
}

/*
In this example, the break statement is used when i equals 5. When the condition is true, the loop is terminated, and the program continues with the next line of code after the loop.
*/

```

Switch Statement Termination: In a switch statement, the break statement is used to terminate the execution of the switch and exit the block of code associated with it. This prevents the program from executing subsequent case statements.

```golang
fruit := "apple"

switch fruit {
case "apple":
    fmt.Println("Selected fruit: Apple")
    break
case "banana":
    fmt.Println("Selected fruit: Banana")
    break
default:
    fmt.Println("Unknown fruit")
}

/*
In this example, when fruit is "apple", the code block associated with the case "apple" is executed. The break statement immediately exits the switch statement, preventing the execution of subsequent cases.

It's important to note that the break statement only terminates the innermost loop or switch statement in which it is located. If you have nested loops or switch statements, a break statement will only affect the innermost construct.

The break statement provides control over the flow of your program, allowing you to exit loops or switch statements prematurely based on certain conditions.
*/

```





**Break statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have break statements to execute blocks of codes.
Lets check break statements in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  for (int i = 0; i < 10; i++) {
    if (i == 5) {
      break;
    }
    print(i);
  }
}



/*
In the Dart programming language, the break statement is used to exit from loops or switch statements. 

In this example, a for loop is used to iterate from 0 to 9. Inside the loop, an if statement checks if the current value of i is equal to 5. When i is equal to 5, the break statement is executed, which terminates the loop immediately. As a result, only the numbers 0 to 4 are printed.

When you run this Dart code, it will output:
0
1
2
3
4

The break statement is not limited to just for loops. It can also be used within while loops, do-while loops, and switch statements to exit the loop or terminate the switch statement prematurely.
Here's another example that demonstrates the usage of the break statement in a switch statement:
*/
void main() {
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

When you run this code, it will output:
0
1
2

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

Note: The break statement is a powerful tool for controlling the flow of execution in JavaScript. It allows you to exit loops or switch statements prematurely based on certain conditions.

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

When you run this PHP code, it will output:
0
1
2
3
4

The loop runs until $i is equal to 5, and then the break statement is encountered, causing the loop to exit immediately. As a result, only the numbers 0 to 4 are printed.

The break statement can also be used with other loop constructs such as while or do-while loops, as well as with switch statements in PHP. Its purpose remains the same: to exit the innermost loop or terminate the execution of a switch statement.

Note: Feel free to modify the example and experiment with different conditions and loop constructs to see how the break statement affects the flow of your PHP code.
*/

\```


\```java {}
public class BreakExample {
    public static void main(String[] args) {
        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                break;
            }
            System.out.println(i);
        }
    }
}



/*
In this example, a for loop is used to iterate from 0 to 9. Within the loop, there's an if statement that checks if i is equal to 5. If the condition is true, the break statement is encountered, and the loop is terminated immediately.

When you run this program, it will output:
0
1
2
3
4

As soon as i becomes 5, the break statement is executed, and the loop is terminated. Thus, only the numbers 0 to 4 are printed to the console.

The break statement can also be used in other constructs, such as while and do-while loops, and it serves the same purpose of prematurely exiting the loop. Additionally, it can be used in switch statements to exit the switch block.

Note: Feel free to customize the example and experiment with different conditions and loops to see how the break statement affects the program's execution flow.
*/

\```

\```kotlin {}

fun main() {
    val fruits = listOf("apple", "banana", "orange", "pear", "grape")

    for (fruit in fruits) {
        if (fruit == "orange") {
            println("Found orange!")
            break
        }
        println("Current fruit: $fruit")
    }
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

Note: The break statement works similarly in Kotlin as in other programming languages, allowing you to exit a loop prematurely based on a specific condition.

*/


\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    for (int i = 0; i < 10; i++) {
        if (i == 5) {
            break;
        }
        std::cout << i << std::endl;
    }
    
    return 0;
}



/*
In this example, the break statement is used within a for loop. The loop iterates from 0 to 9, but when i equals 5, the break statement is encountered. As a result, the loop is terminated, and the program moves on to the next line of code after the loop.

When you run this program, it will output:
0
1
2
3
4

The loop stops when i becomes 5 due to the break statement, so the numbers 0 to 4 are printed. After that, the program exits the loop and continues with the next line of code.

The break statement can also be used in other control structures such as switch statements. Its purpose remains the same—to exit the innermost loop or terminate the execution of a switch statement.

Feel free to modify the example and experiment with the break statement to suit your specific needs.
*/
\```

\```objective-c {}

int main(int argc, const char * argv[]) {
    @autoreleasepool {
        for (int i = 0; i < 10; i++) {
            if (i == 5) {
                break;
            }
            NSLog(@"%d", i);
        }
    }
    return 0;
}


/*
In this example, the break statement is used within a for loop. The loop iterates from 0 to 9, but when i equals 5, the break statement is encountered, and the loop is immediately terminated. The program then continues with the next line of code after the loop.

When you run this Objective-C program, it will output:
0
1
2
3
4

As soon as i becomes 5, the loop is exited, and the remaining iterations are skipped.

Note: The break statement in Objective-C works similarly to other programming languages.
It provides a way to prematurely terminate a loop or exit a switch statement, depending on where it is used.
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

When you run this code, it will output:
1
2
3
4
As soon as the number becomes 5, the break statement is encountered, and the loop is terminated. 
The program continues with the next line of code after the loop.
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

Note: The break statement in Swift, similar to other programming languages, provides control over the flow of execution, allowing you to exit loops or switch statements prematurely based on specific conditions.
*/

\```

\```go {}
package main

import "fmt"

func main() {
	for i := 0; i < 5; i++ {
		if i == 3 {
			break
		}
		fmt.Println(i)
	}
}



/*
In this example, the for loop runs from i=0 to i=4. However, when i equals 3, the break statement is encountered, causing an immediate exit from the loop. As a result, the loop terminates, and the program continues with the next line of code after the loop.

When you run this program, it will output:
0
1
2

As you can see, the loop is terminated when i becomes 3 because of the break statement. The numbers 0, 1, and 2 are printed to the console, and the loop ends without further iterations.

Note: You can utilize the break statement in various situations within loops or switch statements to control the flow of your program based on specific conditions.

*/
\```

```


## <a name="a5" href="#b5">5.</a> Continue Statement in various programming languages

The continue statement is a control flow statement that is commonly used within loops. It allows you to skip the remaining code within the current iteration of a loop and move on to the next iteration. When the continue statement is encountered, the program immediately jumps to the next iteration without executing any further statements in the loop for that particular iteration.


**Continue statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, have continue statements to execute blocks of codes.
Lets check continue statements in the above languages

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
void main() {
  for (var i = 0; i < 5; i++) {
    if (i == 2) {
      continue;
    }
    print(i);
  }
}


/*
In this example, the for loop runs from i=0 to i=4. When i equals 2, the continue statement is encountered.
As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement. The loop continues with the next iteration, printing the remaining numbers.

Note: The continue statement works similarly in most programming languages, including Dart. 
It allows you to control the flow of execution within loops and skip certain iterations based on specific conditions.
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

When you run this code, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement. The loop continues with the next iteration, printing the remaining numbers.

Note: The continue statement is useful when you want to skip certain iterations or exclude specific values from being processed within a loop. It allows you to control the flow of execution and customize the behavior of your loops based on specific conditions.
The continue statement can be used with for loops, while loops, and do-while loops in JavaScript.
*/


\```

\```php {}
<?php

for ($i = 0; $i < 5; $i++) {
    if ($i == 2) {
        continue;
    }
    echo $i . "\n";
}

/*
In this PHP example, the for loop runs from $i=0 to $i=4. When $i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this code, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement. 
The loop continues with the next iteration, executing the remaining iterations and printing the corresponding numbers.

Note: The continue statement in PHP, similar to other programming languages, allows you to control the flow of execution within loops and selectively skip certain iterations based on specific conditions.
*/


\```


\```java {}
public class ContinueExample {
    public static void main(String[] args) {
        for (int i = 0; i < 5; i++) {
            if (i == 2) {
                continue;
            }
            System.out.println(i);
        }
    }
}


/*
In this example, the for loop runs from i=0 to i=4. However, when i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement.
The loop continues with the next iteration, printing the remaining numbers.

The continue statement in Java, similar to other programming languages, is useful when you want to skip certain iterations or exclude specific values from being processed within a loop. 
It allows you to control the flow of execution and customize the behavior of your loops based on specific conditions.
*/

\```

\```kotlin {}

fun main() {
    for (i in 0 until 5) {
        if (i == 2) {
            continue
        }
        println(i)
    }
}



/*
In this Kotlin example, the for loop runs from i=0 to i=4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement. 
The loop continues with the next iteration, printing the remaining numbers.

Note: The continue statement works similarly in Kotlin as it does in other programming languages. 
It allows you to skip specific iterations of a loop based on certain conditions, providing you with more control over the flow of your program.

*/


\```

\```c++ {title: 'C/C++'}
#include <iostream>

int main() {
    for (int i = 0; i < 5; i++) {
        if (i == 2) {
            continue;
        }
        std::cout << i << std::endl;
    }

    return 0;
}


/*
In this example, the for loop runs from i=0 to i=4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output:
0
1
3
4
As you can see, the number 2 is skipped in the output because of the continue statement. The loop continues with the next iteration, printing the remaining numbers.

The continue statement can be used within loops to skip certain iterations or exclude specific values from being processed. It allows you to control the flow of execution and customize the behavior of your loops based on specific conditions in C++.
*/
\```

\```objective-c {}

int main() {
    for (int i = 0; i < 5; i++) {
        if (i == 2) {
            continue;
        }
        NSLog(@"%d", i);
    }
    
    return 0;
}

/*
In this Objective-C example, we have a for loop that iterates from i=0 to i=4. When i equals 2, the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement. The loop continues with the next iteration, printing the remaining numbers.

Note: The continue statement in Objective-C is similar to other programming languages and allows you to control the flow of execution within loops. It helps you skip specific iterations or exclude certain values from further processing.
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

When you run this program, it will output:
0
1
3
4

As you can see, the number 2 is skipped in the output because of the continue statement. The loop continues with the next iteration, printing the remaining numbers.

Note: The continue statement in Swift works similarly to other programming languages. It allows you to skip specific iterations of a loop based on certain conditions. You can use it to customize the behavior of your loops and control which iterations should be executed.

*/



\```

\```go {}
package main

import "fmt"

func main() {
	for i := 0; i < 5; i++ {
		if i%2 == 0 {
			continue
		}
		fmt.Println(i)
	}
}


/*
In this example, the for loop runs from i=0 to i=4. However, when i is an even number (divisible by 2), the continue statement is encountered. As a result, the remaining statements within that iteration of the loop are skipped, and the program moves on to the next iteration.

When you run this program, it will output:
1
3

As you can see, the numbers 0, 2, and 4 (which are even) are skipped in the output because of the continue statement. The loop continues with the next iteration, printing only the odd numbers.

Note: You can utilize the continue statement in various situations within loops to selectively skip iterations based on specific conditions.
This allows you to control the flow of execution and customize the behavior of your loops according to your needs.

*/
\```

```

## <a name="a6" href="#b6">6.</a> Return Statement in verious programming languages

In programming, a return statement is used to exit a function and optionally provide a value back to the caller of that function.
When a return statement is executed, the control flow of the program returns to the point where the function was called, and the value specified in the return statement (if any) is passed back.

Here's a general syntax of a return statement:
```python
def my_function():
    # code within the function
    return value


```


**Return statements in various languages:**

JavaScript/TypeScript, Dart, PHP, Java, C/C++, Swift, Kotlin, Objective-C  and Golang, use return statements in some operations.

> For demo purposes, the code below will be automatically added a main function if necessary when running.

```tabs

\```dart {}
int addNumbers(int a, int b) {
  int sum = a + b;
  return sum;
}

void main() {
  int result = addNumbers(5, 3);
  print('The sum is: $result');
}



/*
In this example, we have a function called addNumbers that takes two integer parameters, a and b. Inside the function, we calculate the sum of a and b and store it in the variable sum. Then, we use the return statement return sum to exit the function and return the value of sum back to the caller.

In the main function, we call addNumbers(5, 3) and assign the returned value to the variable result. Finally, we print the value of result using the print statement.

When you run this Dart code, it will output:
The sum is: 8

This demonstrates how the return statement allows us to pass a computed value from a function back to the calling code.
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

Note: The return statement allows us to obtain the result of the function's computation and use it in further operations or store it for later use.
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

Note: The return statement can be used to return any valid PHP data type, such as numbers, strings, arrays, objects, or even boolean values.
*/


\```


\```java {}
public class Example {
    public static void main(String[] args) {
        int result = addNumbers(5, 10);
        System.out.println("The sum is: " + result);
    }
    
    public static int addNumbers(int a, int b) {
        int sum = a + b;
        return sum;
    }
}



/*
In this example, we have a method called addNumbers that takes two integer parameters a and b. Inside the method, we calculate the sum of a and b and store it in the variable sum. Then, the return statement is used to exit the method and pass the value of sum back to the caller.

In the main method, we call the addNumbers method with the arguments 5 and 10. The returned value from the addNumbers method is stored in the variable result. Finally, we print the result to the console, which would output:
The sum is: 15

This demonstrates how the return statement is used to return a value from a method in Java.

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

In this example, we pass the arguments 5 and 6 to the multiply function. The function performs the multiplication and returns the result, which is then stored in the product variable. Finally, we print the value of product, which is 30 in this case.

*/


\```

\```c++ {title: 'C/C++'}
#include <iostream>

int multiply(int a, int b) {
    int result = a * b;
    return result;  // Returning the calculated result
}

int main() {
    int x = 5;
    int y = 3;
    int product = multiply(x, y);  // Calling the multiply function

    std::cout << "The product of " << x << " and " << y << " is: " << product << std::endl;

    return 0;
}


/*
In the above example, we have a function named multiply that takes two integers a and b as parameters. It calculates their product and assigns it to a variable named result. The return statement is then used to exit the function and return the value of result back to the caller.

In the main function, we declare two integers x and y and assign them the values of 5 and 3, respectively. We then call the multiply function, passing x and y as arguments. The returned value is stored in the variable product. Finally, we print the product using std::cout.

When you run the program, it will output:
The product of 5 and 3 is: 15

This demonstrates how the return statement can be used to pass a value from a function back to the caller.
*/
\```

\```objective-c {}
- (int)sum:(int)num1 and:(int)num2 {
    int result = num1 + num2;
    return result;
}


/*
In the above example, we have a method named sum:and: that takes two integers as input parameters (num1 and num2). The method calculates the sum of num1 and num2 and stores the result in the result variable. Finally, the return statement is used to return the value of result back to the caller of the method.

Here's how you would call this method and receive the returned value:
int a = 5;
int b = 3;
int sumResult = [self sum:a and:b];
NSLog(@"The sum is: %d", sumResult);

In the example above, we create two integers (a and b) with values 5 and 3, respectively. We then call the sum:and: method by sending the message to the object (self) and passing the values of a and b as arguments. The returned value is stored in the sumResult variable, which can be further used or printed as shown using NSLog.
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
package main

import "fmt"

func add(a, b int) int {
    return a + b
}

func main() {
    result := add(5, 3)
    fmt.Println("The sum is:", result)
}



/*
In this example, we have a function called add that takes two integer parameters, a and b. The function adds the two parameters together using the + operator and returns the sum as an int value.

Inside the main function, we call the add function with the arguments 5 and 3, and the returned value is stored in the result variable. Finally, we print the result using fmt.Println.

When you run this program, it will output:
The sum is: 8

Here, the return statement return a + b exits the add function and passes back the sum of a and b to the caller, which is then assigned to the result variable in the main function.

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