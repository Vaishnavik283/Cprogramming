
OOPS LAB 

LAB1


TITLE

Write a simple C program to print "Hello world" on screen and understand the complete development process.



THEORY
Compiling program is the process of converting high level programming language into low level programming language that can be executed by computer's central processing unit. To turn a C program into an executable file, a series of steps that involve writing, compiling, and linking the code.
<img width="600" alt="Screenshot 2023-11-27 091150" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/6e69691c-7fc1-4937-a8cb-0f422830429c">



LAB 2 A



Title

Write a C program to print size of different data types.

Theory

The sizeof operator in C is used to determine the size, in bytes, of a data type or a variable. The syntax for using the sizeof operator is as follows: sizeof (type); The %lu or %zu format specifier used for sizeof operator.

<img width="517" alt="Screenshot 2023-11-25 205417" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/8ba67eef-8a1a-4a46-a43a-6495a9677e7f">

LAB 2B
Title
Write a C program to read a number from user and print a table of multiplication for that number.

Aim
To print a table of a number.

Explanation
By using for loop, table of multiplication for any number will be execute.

![image](https://github.com/Vaishnavik283/Cprogramming/assets/148257063/0dfaf8de-04d4-4911-9ba8-b73b0cfc54d8)


LAB 2C :

Title
Write a program to display different star patterns on screen.

Aim
To print star pattern.

Explanation
In this programme, the user wants to make a pattern by entering the number of rows and columns. The programme creates a pattern of stars with two halves: one with ascending rows and the other with descending rows, separated by a newline character. The number of stars in each row is determined by the value of "i" within the respective loops by using nested for loops.

![image](https://github.com/Vaishnavik283/Cprogramming/assets/148257063/b42efc2c-334b-4117-9083-fbfbed189cdd)

LAB 3 A
Title
Write a program to demonstrate pointers. Declare a pointer ptr to interger and equate it to address of integer i. Print value of i, value of &i, value of ptr and value of *ptr.

Theory
A pointer is a variable that stores the memory address of another variable. It "points" to the location in memory where data is stored. int *ptr; declares a pointer ptr that can point to an integer.

Explanation
This program explain how pointers can be used to access memory addresses and the values stored at those addresses
![image](https://github.com/Vaishnavik283/Cprogramming/assets/148257063/bbd76ff0-c058-4d73-9c79-368c7778e85f)


LAB 3 B
Write a program in C to demonstrate function call by value and call by reference by writing a swap function to swap two integers.

Theory
In C programming there are two ways to pass an arguments to functions : call by value and call by reference, These two methods determine how the function receives and operates on its parameters. In call by value, copies of the actual values are made and passed to the function. And In call by reference, arguments pass the memory address of the actual variables to the function.

Explanation
In this program swap1, which is used to swap the values of two integers using pointers, call by reference.

<img width="921" alt="Screenshot 2023-11-27 094428" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/2824d772-9edc-454a-941c-2d6b457fdbda">


LAB 6A

Title
Write a program to declare a char array of 20 characters. Read a word (using scanf or cin >> ) into the char array.

Theory
In programming, a character array is a data structure used to store sequences of characters, such as strings, in a contiguous block of memory. It is a fundamental part of many programming languages and plays a crucial role in text processing, manipulation, and storage. To declare a character array, you specify its data type, the array name, and its size.

Explanation
The given C++ program demonstrates how to declare a character array, read user input into the array, and then display the input back to the user. A character array named word is declared. It has a size of 20 characters, meaning it can store up to 19 characters plus a null-terminator (a special character, '\0', used to mark the end of strings).
![image](https://github.com/Vaishnavik283/Cprogramming/assets/148257063/17bc10dc-d149-4b80-b5b2-1a17710526e8)

LAB 6 B
Title
Display the array and reverse of the array on screen.

Theory
In programming, an array is a data structure that holds a collection of elements of the same data type, arranged sequentially in memory. The elements in an array are typically accessed by an index, with the first element having an index of 0, the second having an index of 1, and so on. An array may contain various types of data, including integers, characters, floating-point numbers, or even complex objects. To display the contents of an array on the screen, we typically use some form of output operation provided by the programming language, such as cout in C++. A loop, often a for or while loop, is used to iterate through the elements of the array, and each element is printed to the screen. The loop continues until all elements have been displayed. Reversing an array means changing the order of its elements such that the first element becomes the last, the second element becomes the second-to-last, and so on. A common approach to reversing an array is to use two pointers (one starting from the beginning, and the other from the end) and swap their elements iteratively. Alternatively, we can use a loop to create a new array that contains the elements of the original array in reverse order. For numeric arrays, we can also perform in-place reversal, which means that we directly modify the original array.

Output



<img width="792" alt="Screenshot 2023-11-27 095804" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/9f9c71c8-3f54-4a44-a14f-0f9f53a13561">


LAB 5

<img width="631" alt="Screenshot 2023-11-29 205654" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/140ac7b8-b63f-4470-a18e-340cbd2993ec">

LAB 10
Title : LAB10
Aim : Operator Overloading
Algorithm :
Initialize Date Class:

Create a class called Date with private variables for day, month, and year. Implement a constructor to set the initial date, and a display function to print the date.

Leap Year Check: Create a function (isLeapYear) to check if a given year is a leap year. A leap year is divisible by 4, but century years must also be divisible by 400.

Days in Month: Create a function (daysInMonth) to determine the number of days in the current month. February has 29 days in a leap year and 28 days otherwise. April, June, September, and November have 30 days, while other months have 31 days.

Overloaded ++ Operator: Overload the ++ operator as a member function in the Date class. Increment the day by 1. Check if the new day exceeds the number of days in the month. If yes, reset the day to 1 and increment the month. If the month exceeds 12, reset the month to 1 and increment the year.

Main Function: In the main function, create an instance of the Date class with an initial date. Display the current date. Use the overloaded ++ operator to increment the date by one day. Display the updated date.

OUTPUT

<img width="553" alt="Screenshot 2023-11-29 210241" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/011908cb-eb50-47c3-9a20-d39f78944a6a">



LAB 11 
Title : LAB11
Aim : Inheritance

Explanation :
Base Class Constructor Call:

When a derived class object is created, the constructor of the base class is called first. This is because the derived class inherits the properties and behavior of the base class, and before any additional initialization specific to the derived class, the base class needs to be properly constructed. If the base class has a parameterized constructor, the derived class's constructor must call it explicitly, passing the required arguments.

Derived Class Constructor Call:

After the base class constructor has been executed, the derived class constructor is called. The derived class constructor can perform its own initialization and may also call the base class constructor explicitly using the base class's constructor within its member initializer list.

Order of Inheritance:

The order in which constructors are called is determined by the order of inheritance. In the example above, Derived publicly inherits from Base, so the Base class constructor is called before the Derived class constructor. If there were multiple base classes, they would be initialized in the order they are listed in the inheritance declaration.

In summary, when a derived class object is defined in C++, the constructors are called in a well-defined order: first the base class constructor(s), in the order of inheritance, and then the derived class constructor. You can use member initializer lists to explicitly call base class constructors if needed. This ensures proper initialization and allows you to set up the derived class's specific behavior while inheriting the characteristics of the base class.

OUTPUT

<img width="482" alt="Screenshot 2023-11-29 210706" src="https://github.com/Vaishnavik283/Cprogramming/assets/148257063/b5a2937c-73a2-4cb4-a9ee-c97da503fe6c">

