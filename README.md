# C4ALL
C language for everyone.


C1: variables
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
2^(n-1)•V
We assume the n begins as 1 here.
V is value, the value of 1 or 0.
Now lets calculate.
2^0•0=0
2^1•1=2
2^2•0=0
2^3•1=8
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
2^(x•2) = (2^x)^2
That means that if we have x bits,
And want to know the size if it was twice as big,
We can either power it by two, or multiply x by two in the calculation.
Wow, that was a lot of math.
From here, we know the concepts, and can move on.

Yes, this was a lot.
Now, lets learn the variable types.
We begin at the float, long float, and double.
Floats represent non round numbers.
Such as 69.420 or 420.69.
Floats are 4B, doubles 8B, long floats 16B.
Long float is also named long double.
Long float is the biggest single data type.
Next up we got the ints.
The int family is bigger.
We have int, long int, long long int, char.
Char is 1B, int and short int 2B, long int 4B, long long int 8B.
If we have a name like "long long", we can just not write the int.
So short int is the same as short.
Chars later have another meaning, but thats later.

Theres also const, short term for constant variables.
Const means that the variable is constant, unchangable.
Const variables are faster, since theres nothing slower about them.

Next, we got the register memory.
Our computer uses 3 memory locations.
Ram, hard drive or ssd, and registers.
The speed of the processor is limited by the speed of light.
So, the further the component is, the harder it is to reach.
The hard drive is really far.
Ram is rather close.
The registers are in the processor, the closest.
To make a variable in the registers, we will use the register keyword.

Now we know all the current data types we will need.
Now lets learn about how we practically make variables.
We can make combinations of:
const register int
register unsigned long long
The variable is as complex as that.
Now, like in math, lets name it well.
long long x;
The semicolon means ending a code line.
Now whenever we mention x, it will return x's value.
Lets set it to 10.
x=10;
Now if we call x, it will be 10.


C2: functions and function nature

Functions in mathematics are premade calculations.
In c, functions are predefined actions we can call, with arguments.
