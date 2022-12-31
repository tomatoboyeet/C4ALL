# C4ALL
C language for everyone.


C1: ints
Ints are very interesting.
The data type that can represent all data.
Ints are short terms for integers, a round number.
Meaning, all natural numbers, and all negetive natural numbers.
Ints can be only natural. If they support both, they are signed.
If they support only positive, they are unsigned.
Minus and plus are 1 bit of data. If we dont use it in signing it,
We can use another bit of data.
Ints are read like so
Lets call the binary representation x.
Lets say its 1010.
The calculation is adding all the results of the following calculation:
2^(n-1)/*V
We assume the n begins as 1 here.
V is value, the value of 1 or 0.
Now lets calculate.
2^0/*0=0
2^1/*1=2
2^2*0=0
2^3*1=8
0+2+0+8=10
So 1010 is 10.
You can play with it, but now we know what an int is.
Ints come in different sizes.
8b, 16b, 32b, 64b.
b is not B in computing.
Small b is a bit, capital b is a byte.
A byte is 8 bits.
So we have 1B,2B,4B,8B.
We count data sizes by 2^V.
V is how much bits we have.
So 8 bit is 256. From here the numbers get bigger.
If we calculate it, we know that
2^(x*2) = (2^x)^2
That means that if we have x bits,
And want to know the size if it was twice as big,
We can either power it by two, or multiply x by two in the calculation.
Wow, that was a lot of math.
From here, we know the concepts, and can move on.
