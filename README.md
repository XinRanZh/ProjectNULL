# ProjectNULL
A turing complete programming Language, contain only TAB, SPACE and ENTER, so it looks fully blank. 一种图灵完备的编程语言，只由Tab空格和回车组成，所以看起来是空白的

## Structure and principle:
Refer to BrainFuck, this language consists of seven instructions, an array of infinite length and a pointer that can move on the array to achieve a complete single-band Turing machine simulation.

## How to use:
Initially, every element in this array is 0, and the pointer points to the zeroth element, and then executes according to the following seven instructions.

1."SPACE" : the value of the element pointed to by the current pointer + 1
2."SPACE"+"SPACE" : the value of the element pointed to by the current pointer - 1
3."TAB" : The pointer moves one place to the right
4."TAB" + "TAB" : The pointer moves one place to the left
5."TAB" + "SPACE" : When the element pointed is 0, jump to the matching 6 *(5/6 matching like brackets)*
6. "SPACE" + "TAB": When the element pointed is NOT 0, jump to the matching 5 *(5/6 matching like brackets)*
7. "TAB" + "SPACE" + "TAB" : Output the element pointed by the pointer in the form of ASCII code

Instructions and Instructions are distinguished by ENTER, everything that is not TAB, SPACE and ENTER will be regarded as Comment
