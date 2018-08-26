# C 2: Functions and Structures

## Exercise 2.1
> Without writing the program, can you predict what it will print
at the end? Then, write the program in `functionExample.c`,
and confirm.

## Exercise 2.2
>Run the code and observe its output. Draw a memory diagram
  on your worksheet indicating the stack's contents just before `f2()`
  returns. (Use the stack model described above, remember to ignore printf
  statements). Confirm that our stack  model accurately represents
  the program's behavior.


>Change the program so that `f2()` is called before `f1()`.
  How does the program output change?


>Revert so that `f1()` is called first. Then change the program
  so that `int m` is initialized to 3 in its
  declaration in `f2()`. Does our stack model still accurately represent
  the program behavior? If not, can you guess what the compiler is doing differently?


>Revert so `int m` is not initialized, and `int n = 4`.
  Does our stack model still accurately represent
  the program behavior? If not, can you guess what the compiler is doing differently?

## Exercise 2.3
> What is the compiler error generated?

> Add function prototypes to the top of your `functionExample.c` file and verify
this removes compiler messages when `int main` is moved to the top.


## Exercise 2.4
> Implement the above in `swapExample.c`.
Draw a complete memory picture just before `swap()` returns.

## Exercise 2.5
> What happens in each of the following two modifications of the
`swap` program? Draw a complete
memory diagram on your worksheet. Explain why neither of them work.

## Exercise 2.6
> Implement the above in `structExample.c`. Define another
pointer based location struct called `myHousePtr` and make it point to the `myHouse` variable.
Add another print statement that outputs the values for your new struct.

> What errors do you get if you try to use the wrong operator to access
either a pointer or non-pointer based stack?

## Exercise 2.7
> Add a while loop at the end to print each node's data in turn
using a pointer that successively points to each node.
Write your code in `structExample2.c`

## Exercise 2.8
> Fill in the worksheet memory diagram for the stack and the heap immediately
before your while loop executes.  You do not need to fill in addresses, but you
should draw arrows showing what any pointer variables reference, or write
`NULL` for the contents of any uninitialized pointers.

## Exercise 2.9
> Hand-execute the code and predict what gets printed out in your README.


> Do you think `static` variables are stored on the stack? Why or why not?

## Exercise 2.10
> In `mathproblem.c` write a method that computes the sum
>  
>  <i>1 + 1/2 + 1/4 + ... + 1/2<sup>n</sup></i>
>
> for any input parameter <i>n</i>.
