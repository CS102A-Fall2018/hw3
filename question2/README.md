## Question 2

Write the logic for setbits(x,p,n,y) in main() that prints x with the n bits that begin at position p set to the rightmost n bits of y, leaving the other bits unchanged. Input x=17, p=2, n=2, y=8. In addition, try an sample input of your choice. (K&R Exercise 2-6)

Examples:  
x=17 -> 10001  
p=2  
n=2  
y=8 -> 01000  
  
The n bits at position p is, in this case: 00  
The right most n bits of y is, in this case: 00  
Hence, the answer is 10001 or 17 in decimal.  
  
Maybe a better example would be:  
x=17 -> 11001  
p=3  
n=3  
y=2 -> 00010  
  
The n bits at position p is, in this case: 100  
The right most n bits of y is, in this case: 010  
Hence, the answer is 10101 (replace the 100 part with 010), or 13 in
decimal.  

Compilation Steps:

Output:
