FallVelocity 1.3
----------------

A first attempt to write a program for a scientific simulation, because simulations are one of the main goals of this "progress"- project these small programs build up.

The velocity of mass falling down will be calculated.

So far just the fall acceleration of the Earth is used, 9.81 m/s^2.
Also the precision is limited to 2 digits.


1   double t, v; int r;
2 
3   main()
4   {
5   r=0;
6   while (r)
7   {
8   v=9.81*t;
9   }
10  }


ATTENTION:

When this program is used without a debugger, the while- loop easily can run infinitely.
Small infinite loops like this one can heat up the processor when running.

Thus make shure to use a debugger and set breakpoints as mentioned below when using this program.


Usage:

The usage and result examination has to be done with a debugger.

First set a breakpoint at line 4.

Set another breakpoint at line 9.

Run the program.

Set the variables as follows:

  r (for "run") to 1 if the program should continue for further calculations
                   0 if the program should stop and terminate
				   
  t to the time passed from the mass starting to fall
  
Examine the result in variable v

Continue the program execution for a new entry of a value for the time t.

If the program should terminate, set variable r to 0.




Version history
---------------

Version 1.3

Inserted an empty line between the variable definitions and the main()- function to furthermore beautify the code and make it easier to read and maintain.


Version 1.2

Placed the opening curly bracket in a new line, also the one at the while loop, to make the code easier to read and maintain.


Version 1.1

Placed the while loop in a new line to make the code more easy to read and to maintain.


Version 1.0

Initial version

