# 42_get_next_line
<h3>Assignment</h3>

This project is about programming a function that returns a line
read from a file descriptor.

<h3>Goal</h3>

Make you learn a highly interesting new concept in C programming: static
variables.

<h3>What do you need to search before doing get_next_line</h3>
<h4>Static Veriables</h4>
If you have never heard of static variables you have to study about it. 

It has two main features :

-  Static variables have a property of preserving their value even after they are out of their scope! Hence, static variables preserve their previous value in their previous scope and are not initialized again in the new scope.

-  Static variables do not required to be initialized. They are automatically initialized to NULL.

<h4>Read function</h4>

Read() - read from a file descriptor <br>
The function read() attempts to read up to <i>count</i> bytes from file descriptor <i>fd</i> into the buffer starting at <i>buf</i>. <br>
read(int <b>fd</b>, void <b>*buf</b>, size_t <b>count</b>); <br>

<h4>Malloc and Free</h4>

Long story short, malloc() is used to allocate memory.
- The malloc() function allocates size bytes and returns a pointer
       to the allocated memory.  The memory is not initialized.  If size
       is 0, then malloc() returns either NULL, or a unique pointer
       value that can later be successfully passed to free().
       
Long story short, free() is used to free the memory space pointed by the pointer.
- The malloc() function allocates size bytes and returns a pointer
       to the allocated memory.  The memory is not initialized.  If size
       is 0, then malloc() returns either NULL, or a unique pointer
       value that can later be successfully passed to free().

<hr>
I hope you found it interesting! <br>
And if you are going to do get_next_line, I wish you good luck and hope that you learned something here!
