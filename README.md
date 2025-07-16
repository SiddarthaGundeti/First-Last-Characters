# First-Last-Characters

**write a program that reads a word and prints the first and last characters of the word on two lines.**

Input: qwerty

Output: q
        y

Question Explanation:

This program is designed to read a word and print its first and last characters on separate lines. 

Logical Approach:

1.Read Input:
Read a word from the input as a string. Let's call it word.

2.Determine the Length of the Word:
Calculate the length of the word using len(word) and store it in word_length.

3.Find the First Character:
The first character of a word is at index 0. So, extract the first character from word using word[0] and store it in first_character.

4.Find the Last Character:
The last character of a word is at the index word_length - 1. Extract the last character using word[word_length - 1] and store it in last_character.

5.Output:
Print the first_character on the first line.
Print the last_character on the second line.

Example for Clarity:

If the input word is qwerty:
The first character is q.
The last character is y.
The output will be:

q

y

This program effectively captures the essential characteristics of any word, providing its initial and final letters as distinct outputs.
