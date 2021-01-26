The c program uses pthread to make two separate threads which we use to simultaneously increment and decrement the same global variable i. 
In go it's conceptually the same operations going on, we just use the go routine to run the two functions on different cores.
The reason we don't end up with zero is that one process interrupts the other one as it has just entered the 
for-loop and incremented it's counting variable. This is also the reason we end up with different numbers each time.
