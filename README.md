# N-stair-problem--recursion

There is a stair with N=3 steps, recursion will tell us how many ways we can climb the stair from 0 to 3. Recursion is function which calls itself within the function body. The forward call will continue until base case is fullfilled (3-2-1-0). Then the backward call starts; the answer we get from base case will be the function output of previous step. Following this process we can reach towards (0-1-2-3) call again. The final answer would be the function output of N=3.

