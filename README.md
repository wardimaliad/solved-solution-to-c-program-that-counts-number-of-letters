Download Link: https://assignmentchef.com/product/solved-solution-to-c-program-that-counts-number-of-letters
<br>
Write a c program that counts number of letters…

Write a program with a main() function and at least (3) functions definitions (and corresponding function prototypes and function calls). The program will:

1. read 1 character at a time until reaching EOF, (similar to the counting.c program)

2. use function getchar() to get one character from the user,

3. count the uppercase and lowercase letters of the alphabet, and

4. store the counts in an array of 26 elements.

5. The index of the array corresponds to each letter of the alphabet.‘a’ will be index 0‘b’ will be index 1‘c’ will be index 2etc.

6.The counts of each letter are stored as the elements of this array. This is similar to how an array is used to store the counts for the roll of a dice in this program: random2.c.

7. At end of program, print out the letters and counts.

8. Do NOT use 26 if-statements or a 26 case switch-statement in your code.

9. The array should be a local variable in the main() function. Make sure that you past your array to your functions. Below is an example main() function:

int main(){//create array for 26 lettersint letters[SIZE] = {0};printInstructions();loopAndCountLetters(letters);outputResults(letters, SIZE);return 0;}

Exmaple outputs:

This program will count the letters of the alphabet.Type several sentences, or use input redirection to input a file.To exit program, enter EOF (end of file) by pressing Crtl-D.AaaBBBbbbbabcdefABCDEFzZThe character counts are:a 5b 9c 2d 2e 2f 2g 0h 0i 0j 0k 0l 0m 0n 0o 0p 0q 0r 0s 0t 0u 0v 0w 0x 0y 0z 2

This program will count the letters of the alphabet.Type several sentences, or use input redirection to input a file.To exit program, enter EOF (end of file) by pressing Crtl-D.The quick brown fox jumps over the lazy dog.The character counts are:a 1b 1c 1d 1e 3f 1g 1h 2i 1j 1k 1l 1m 1n 1o 4p 1q 1r 2s 1t 2u 2v 1w 1x 1y 1z 1


