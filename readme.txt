FallVelocity 1.0
----------------

A first attempt to write a program for a scientific simulation, because simulations are one of the main goals of this "progress"- project these small programs build up.

The velocity of mass falling down will be calculated.

So far just the fall acceleration of the Earth is used, 9.81 m/s^2.
Also the precision is limited to 2 digits.


1  double t, v; int r;
2  main(){
3  r=0;while (r){
4  v=9.81*t;
5  }
6  }


ATTENTION:

When this program is used without a debugger, the while- loop can easily run infinitely.
Small infinite loops like this can heat up the processor while running.

So, make shure using a debugger and set breakpoints as mentioned below when using this program.

Usage:

The usage and result examination has to be done with a debugger.

First set a breakpoint at line 3.

Set another breakpoint at line 5.

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

Version 1.0

Initial version

