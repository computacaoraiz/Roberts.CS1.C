# Roberts.CS1.C: `cslib` library for C

[Eric S. Roberts](https://cs.stanford.edu/people/eroberts/) published an
excellent introductory book on computer science using the C programming language
as a learning tool, titled **The Art and Science of C: An Introduction to
Computer Science (A Library-Based Introduction to Computer Science)**
(Addison-Wesley, 1995):

![Foto da cada do
TAASOC](https://raw.githubusercontent.com/computacaoraiz/Roberts.CS1.C/master/imgs/taasoc.jpg)

This book introduces the **fundamentals of computer science** and the
**fundamentals of programming** using the C language. It's very well-written,
extremely educational, and uses a special library of functions prepared by the
author himself to simplify understanding of fundamental concepts for students.

Since it’s quite an old book (published in 1995), it does show some signs of
aging (it uses the ANSI/C89 standard). However, it remains an excellent
reference because:

* It genuinely teaches the fundamentals of computer science;
* It truly teaches the fundamentals of programming;
* It accomplishes this using the C language; and
* It incorporates a **library of helper functions** that the author created to
  prevent students from getting bogged down in C’s details before understanding
  the core concepts and fundamentals: the **`cslib`** library.

One advantage of the book’s age is that it is no longer in print and can be
found second-hand in bookstores for a very affordable price (around $5.00).

The original FTP server from Addison-Wesley that hosted the `cslib` distribution
code accompanying the book in 1995 no longer exists. However, various fragments
of these codes can still be found scattered across the Internet. I attempted to
gather as much of the original book’s code as possible and "recreate" the
original FTP server structure in this Roberts.CS1.C repository.

I am fairly confident that the available codes are nearly complete, with the
following exceptions:

* I'm not certain that the code in the mac-think-c subdirectory is complete;
* I have yet to add the codes from the simplified directory (although these
    codes are printed in the book itself, the author mentioned in a README that
    he made a few small changes not reflected in the printed version. I’m still
    trying to locate this modified code);
* I successfully tested the codes in the standard and unix-xwindows directories
    (I am using the library from the unix-xwindows directory);
* I haven’t tested the codes for Mac or PC (Borland or Turbo).

In addition to the original codes, I generated PDF versions of the README files
(and a few of other files) to make reading and printing easier.

If you want to use the `cslib` library written by Roberts, you must follow the
installation instructions in the README (and other) files in this repository. It
is absolutely crucial that you compile the libraries and use the gccx script
generated in this process to compile programs created with these libraries.

If you have any piece of code from the *cslib* library that is not included in
this repository, or if you even have a complete copy of the original code, I
kindly ask you to share it with me so that I can freely distribute it here. By
doing so, you will be contributing to computer science students worldwide.
