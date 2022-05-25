# homework4
#how to set up my code
1. for homework 4-1, first import bbcar library
2. then create a function selfturn to let car can turn in a same place
3. next, let the car right selfturn and stop when the distance of ping collected is far bigger than the one collected 1ms before
4. next turn left and turn to the middle
5. then let the car left selfturn and stop like step3
6. then use Pythagorean theorem to calculate the length of the object

7. for homework 4-2, first import bbcar library, and copy the code in QTI program
8. then write a thread to let encoder count the distance
9. when the car go the the black line(0b1111) first time then start the thread
10. next when the car stop at a black line make the main thread sleep for 200ms to let the car go through the black line

#what are the result
1. for 4-1, the distance collected by Ping will be printed out
2. and when stop, it will print d2
3. then turn to the left and stop then it will print d3
4. finally calculate w1 and w2 by d2 and d3 and add them up, the result will be the length
5. for 4-2, if the car first detect 0b1111 it will start record
6. then if the car detect again, it will print out the distance, and make distance = 0, for the next time it detect 0b1111
