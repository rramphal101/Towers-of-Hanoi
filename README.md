## Towers of Hanoi  

This is my solution to the Towers of Hanoi puzzle.

The Towers of Hanoi is a puzzle with 3 rods and a given number of disks (n). 
To begin, all the disks are placed on the first rod in size order, with the smallest disk at the top and largest at the bottom.
The objective of the puzzle is to move the entire tower from the first rod to the second rod.  

### Rules:  

1. Only one disk can be moved at a time.
2. Disks cannot be a placed on top of a smaller disk (disks can only be placed if the one beneath it is larger).
3. Disks can only be moved if it is at the top of its stack. 

The number of moves required to complete the puzzle is: 2^n - 1, where n is the number of disks.

#### To complie and run:
- You can use a C++ compiler such as `g++ TowersOfHanoi.cpp`
- Then run the executable file with `./a.out`
