# INT Data Types

**Integer data** is the numeric value with no decimal point or fraction. It includes both positive and negative value.

## 1. Int Data Type

**Type:**
Integer values without fractional part 11,25 etc. 

**Size:**
It takes to 2 or 4 bytes in memory.

**Range:**
-32768 &rightarrow; 32767.

**Type in code:**
`int`

## 2. Short Data Type

It is also called short int.

**Type:**
Integer values.

**Size:**
2 bytes.

**Range:**
(-2<sup>15</sup> &rightarrow; 2<sup>15</sup>-1) *OR* (-32768 &rightarrow; 32767)

**Type in code:**
`short int`

## 3. Unsigned int data type

**Type:**
only positive integer value.

**Size:**
2 bytes.

**Range:**
0 &rightarrow;  2<sup>16</sup> -1

**Type in code:**
`unsigned int`

## 4. Long data type

It is also called long int.

 **Type:**
 Long integer value.

 **Size:**
 4 bytes.

 **Range:**
 -2,147,483,648 &rightarrow; 2,147,483,647

**Type in code:**
`long int`

## 5. Unsigned long data type

It is also called unsigned long int.

**Type:**
Large positive integer value.

**Size:**
4 bytes.

**Range:**
0 &rightarrow; 4,294,967,295

**Type in code:**
`unsigned long int`

## C Language Code Example

```c
#include<stdio.h>
int main(){
    int num1 = 5;
    short int num2 = 10;
    unsigned int num4= 15;
    long int num5= 20;
    unsigned long int num6 = 25;
}
```
