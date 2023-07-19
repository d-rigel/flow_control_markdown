# If-else if-else statement in 13 different languages 

![functions image](https://1.bp.blogspot.com/-dnz1LagEoMU/XfiAduKMbUI/AAAAAAAAE4k/Of4U7Ev6w_s_IFabFXQqGe1SAHsDtM40wCLcBGAsYHQ/s1600/if-else-if%2Bladder.png)


In programming, an "if else if else" statement is used when there are multiple conditions to evaluate and execute different blocks of code based on those conditions. It allows you to specify multiple conditions and corresponding code blocks to execute based on the outcome of those conditions. Here's an example of an "if else if else" statement in different programming languages.


**javaScript:**

```javascript
let number = 10;

if (number > 0) {
    console.log("Number is positive");
} else if (number < 0) {
    console.log("Number is negative");
} else {
    console.log("Number is zero");
}

```


**Dart:**

```dart
int number = 5;

  if (number > 10) {
    print("Number is greater than 10");
  } else if (number > 5) {
    print("Number is greater than 5 but not greater than 10");
  } else {
    print("Number is 5 or less");
}

```

**Php:**

```php
$number = 10;

if ($number > 0) {
    echo "Number is positive";
} else if ($number < 0) {
    echo "Number is negative";
} else {
    echo "Number is zero";
}

```

**Java:**

```java
int number = 5;

if (number > 10) {
    System.out.println("Number is greater than 10");
        } else if (number > 5) {
    System.out.println("Number is greater than 5 but not greater than 10");
        } else {
    System.out.println("Number is 5 or less");
}

```

**C++:**

```c++
int number = 10;

if (number > 0) {
    std::cout << "Number is positive" << std::endl;
} else if (number < 0) {
    std::cout << "Number is negative" << std::endl;
} else {
        std::cout << "Number is zero" << std::endl;
}

```


**Objective-c:**

```objective-c
int number = 5;

if (number > 10) {
     NSLog(@"Number is greater than 10");
        } else if (number > 5) {
            NSLog(@"Number is greater than 5 but not greater than 10");
        } else {
     NSLog(@"Number is 5 or less");
}

```

**Swift:**

```swift
let number = 10

if number > 0 {
    print("Number is positive")
} else if number < 0 {
    print("Number is negative")
} else {
    print("Number is zero")
}


```

**Kotlin:**

```kotlin
val number = 10

if (number > 10) {
    println("Number is greater than 10")
} else if (number < 10) {
    println("Number is less than 10")
} else {
    println("Number is equal to 10")
}


```

**Python:**

```python
number = 10

if number > 0:
    print("Number is positive")
elif number < 0:
    print("Number is negative")
else:
    print("Number is zero")


```

**Go:**

```go
number := 10

if number > 10 {
	fmt.Println("Number is greater than 10")
} else if number < 10 {
	fmt.Println("Number is less than 10")
} else {
	fmt.Println("Number is equal to 10")
}

```

**Rust:**

```rust
let number = 10;

if number > 0 {
    println!("Number is positive");
} else if number < 0 {
    println!("Number is negative");
} else {
    println!("Number is zero");
}

```


**C#:**

```c#
int number = 10;

if (number > 10)
    {
        Console.WriteLine("Number is greater than 10");
    }
        else if (number < 10)
    {
        Console.WriteLine("Number is less than 10");
    }
        else
    {
        Console.WriteLine("Number is equal to 10");
}

```

**Ruby:**

```ruby
number = 10

if number > 0
  puts "Number is positive"
elsif number < 0
  puts "Number is negative"
else
  puts "Number is zero"
end

```






Note that the specific syntax and keywords may vary slightly depending on the programming language you're using, but the general concept of an "if-else if-else" statement remains the same.