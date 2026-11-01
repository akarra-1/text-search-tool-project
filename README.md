Text Search Tool

Project Goal:
Whenever we look up a question on the internet, there are tons of websites that don't contain the information we're looking for, or talk about a slightly different topic. It's really time consuming to open and read multiple to just figure out whether it even relevant to my question. This project aims to make that easier by searching text files for specific words or phrases, helping users identify potentially relevant information before spending time reading it in detail.

MVP Scope:
1. Read text file using BufferedReader
2. Get the user's search term through the Scanner.
3. Check whether the search term appears in the text file.
4. Display whether the search term was in the text file.
5. Handle basic errors, such as missing text file,  or empty search term

Future Plans:
1. Displaying the lines containing the search term, so that user only needs to read relevant portions of a text
2. Support case-insensitive reading. This way capitalization won’t impact results
3. Allow the user to search multiple words or phrases 

Tech Stack:
Programming language: Java
User Input: java.util.Scanner
File Reading: java.io.BufferedReader
Error handling: java exception handling
Input files: plain-text .txt files
