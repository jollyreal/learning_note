# the fun of number 9 in base 10 system

## question 
1. take your birthday of month and days, add them together
2. multiple the answer with 18
3. sum all the digit
4. if the digit larger than 10 sum all the digit again

## answer
any birthday date or any number will converge to 9

## example
### my birthday is 7th of April.
1. 7+4 = 11
2. 11*18 = 198
3. 1+9+8 = 18
4. 1+8 = 9

### random birthday 9th of December
1. 9+12 = 31
2. 31*18 = 558
3. 5+5+8 = 18
4. 1+8 = 9

## proof
### let say any number of "n":

![eqn1](src/fun_of_9_1.png)

### rewrite the equation:

![eqn2](src/fun_of_9_2.png)

### move the equation

![eqn3](src/fun_of_9_3.png)

### factorise the 9 out from the Right Hand Side (RHS)

![eqn4](src/fun_of_9_4.png)

### further carry out sum of digit

for the part

![eqn5](src/fun_of_9_5.png)


no matter what is the number, sum of digit will converge to number 1~9

### and we know

|multiple|sum of digit|
|:-:|:-:|
|9*1 = 09|0+9 = 9|
|9*2 = 18|1+8 = 9|
|9*3 = 27|2+7 = 9|
|9*4 = 36|3+6 = 9|
|9*5 = 45|4+5 = 9|
|9*6 = 54|5+4 = 9|
|9*7 = 63|6+3 = 9|
|9*8 = 72|7+2 = 9|
|9*9 = 81|8+1 = 9|

the table above show that no matter any single digit of number as long as a single digit number multiply with 9, the sum of digit will end up to be 9

## reference
1. https://math.stackexchange.com/questions/1221698/why-is-the-sum-of-the-digits-in-a-multiple-of-9-also-a-multiple-of-9
2. http://www.eklavya.org/magic9-1.html
