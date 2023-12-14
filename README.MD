<!-- javascript function -->
A function is a block of reusable code designed to perform a particular task.
It is defined with a function keyword,a name,and a parenthesis .The code to be executed is placed inside a curly braces.

-Parameters:listed inside the parenthesis.
-Argument: are the value called when you invoke
-invocation is when you call your function.

function can be;
-reusable block of code
-called many times.
-use same code  for different arguments.

-function return is when you invoke a function and wants to get response back from the user.
A return statement also means the end of a code,after such statement no code wil be executed because inputing return signifies the end of a declared function.

<!-- FUNCTION SYNTAX -->
There are three ways to define a function;
function declaration
function expression
function constructor.

-A function defined by a function expression or by a function declaration inherit the current scope while a function defined by a function constructor does not inherit any scope.

<!-- function parameters -->
function parameter is a simpler identifier that you can access in the local scope.
<!-- there are 3 special parameter syntax -->
- Default parameter:allows formal parameters to be initialized with default values if no values or undefined is passed.
- Rest parameter:allow for representing an indefinite number of an arguments as an array.
- Destructing:allows unpacking elements from arrays or properties from objects,into distinct variables.

<!-- ARRAYS -->

Array is a special variable that can hold more than one value.
Array uses numbers to access it's element while objects uses name to access it's element.

<!-- Array methods -->

Any Array element are accessed using their index i.e start the counting of an array from zero(0).

- length : returns the length side of an array. 
 e.g  const fruit = ["Banana", "Orange", "Apple"];
   let size = fruits.length

- toString : converts an array to a string using toString (). e.g
   const fruit = ["Banana", "Orange", "Apple"];

- join() : joins the array,behaves like toString but you can specify the type of separator you want in the join method.
e.g fruits.join("")
result = "banana","apple"

- pop() and push() :pop is used to remove the last element of an array.
- push add a new element at the end of an array.

- shift() :shifting remove the first element of an array and shift all other element to a lower index.
- unShift() :unShift add a new element at the beginning of an array.

- delete() :Array element can be deleted using delete operator but this leaves it undefined in the console so, it advisable to use shift() and pop() instead.

- conCat() :used to create a new array by merging existing ones to it.
e.g const myGirls = ["tola","ayo"];
    const myBoys = ["tobi","fola"];
    const myStep = ["mide","kunmi"];
    const myChildren = myGirls.conCat(myBoys,myStep);

- flat() :This is the process of reducing the dimension of an array.It creates a new array with sub-array elements concatenated to a specified depth.

- splice() :method use to add new items to an array.
e.g 
const fruit = ["Banana", "Orange", "Apple"];
fruits.splice(2, 0, "Lemon", "Kiwi");
     The (2) defines the position where the new element is to be added.
     The(0) defines how many elements should be added. 
     The rest of the parameters defines the new elements to be added.
splice can also be use to delete an element without leaving holes.e.g
     fruits.spice(0, 1)
    (0) defines the position where new elements should be added.
    (1) defines how many elements to be removed.

- slice() :slices out a piece of an array into a new array i.e it create a new array from the set of array when an index number is specified from the created array,it does not remove any element from the source array. e.g
   const fruit = ["Banana", "Orange", "Apple"];
   const citrus = fruits.slice(1);
<!-- Result -->
"banana"
"orange" ,"apple"
when you slice and indicate an index,the index indicate starts a new line making the index before it the end of a line.

slice can also pass an argument i.e indicate index using parameters. e.g
const fruit = ["Banana", "Orange", "Apple", "Lemon", "Mango"];
   const citrus = fruits.slice(1,3);
   It takes only the fist and second index leaving the third index.

<!-- CONTROL FLOW -->

<!-- if/else statement -->

Are used to execute a block of code if a certain condition is true and a different block of code if the condition is false.

<!-- switch statement -->

Are used to execute a block of code based on the value of a variable or expression.

<!-- LOOPS -->

Are used to execute a block of code multiple times based on a cretain condition. There are two main types of loops in javascript;
-For loop
-Do/while loop

<!-- FOR LOOP -->
 
Runs the code as long as the condition stated is met.

<!-- Do/WHILE LOOP -->

Runs the code once before it check whether the condition is true or false.















































