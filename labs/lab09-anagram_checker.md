# Lab 09: Anagram Checker

Let's write an anagram checker.

## Anagram

Two words are anagrams of each other if the letters of one can be rearranged to fit the other. e.g. `anagram` and `nag a ram`.

Write a program that lets the user enter two strings, and tells them if they are anagrams of each other.

1. Convert each word to lower case (`lower`)
2. Remove all the spaces from each word by replacing them with empty strings (`replace`)
3. Sort the letters of each word (`sort`)
4. Check if the two are equal

```
>>> enter the first word: anagram
>>> enter the second word: nag a ram
>>> 'anagram' and 'nag a ram' are anagrams
```

# Advanced Version 1

Make your program ignore capital letters and punctuation.

# Advanced Version 2

Let the user enter as many words as they choose. If every word is an anagram of every other word, let the user know.

