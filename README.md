# ProjectNULL
A turing complete programming Language, contain only TAB, SPACE and ENTER, so it looks fully blank. 一种图灵完备的编程语言，只由Tab空格和回车组成，所以看起来是空白的

## Structure and principle:
Refer to BrainFuck, this language consists of seven instructions, an array of infinite length and a pointer that can move on the array to achieve a complete single-band Turing machine simulation.

## How to use:
At the beginning, we have an **Array of infinite length**, where each element is **0**; we have a **pointer**, initially pointing to the 0 place in the Array, and then execute the following seven commands

1.**"SPACE"** : the value of the element pointed to by the current pointer + 1

2.**"SPACE"+"SPACE"** : the value of the element pointed to by the current pointer - 1

3.**"TAB"** : The pointer moves one place to the right

4.**"TAB" + "TAB"** : The pointer moves one place to the left

5.**"TAB" + "SPACE"** : When the element pointed is 0, jump to the matching 6 *(5/6 matching like brackets)*<br><br>
6. **"SPACE" + "TAB"**: When the element pointed is NOT 0, jump to the matching 5 *(5/6 matching like brackets)*<br><br>
7. **"TAB" + "SPACE" + "TAB"** : Output the element pointed by the pointer in the form of ASCII code<br>


**Instructions and Instructions are distinguished by ENTER, everything that is not TAB, SPACE and ENTER will be regarded as Comment**

## Interpreter example
All Turing complete languages can write interpreters for this language. These interpreters can be easily modified from BrainFuck's interpreters. Currently, a very simple Java language interpreter is provided

**JAVA** : https://github.com/XinRanZh/ProjectNULL-JavaDecoder



## Demo Program
### Hello World!
1111111153111153113111311131444426313132331546426337322271111111771117337427471117222222722222222733173117
### Move Data to it's right place
35264523146

## Credit
BrainFuck gave me the basis for inspiration and realization, and Yuan Yuxuan and Lei Yuqi provided English and Chinese names respectively
