# swift-scripts

Mac OS X shell scripts written in Swift. Because why not?

## Contents

### hello

Usage: ./hello [Your Name]

Explanation 
* Kinda of boring, replies with "Hi [Your Name]!"
* Basically a hello world swift script

### morse

* Usage 1: ./morse
* Usage 2: ./morse [Englosh message to encode into morse]
* Usage 3: ./morse [Morse code message to decode into English]

Explanation
* If you enter the command with no input (usage 1) you get a table of english letters and their morse code counter parts
* If you enter the command with input (usage 2) your input is translated into morse code! (Awesome!)
* If you enter the command with input (usage 3) your input is translated into English (if it was morse code)

Example 1
* Input: ./morse morse code rocks
* Output: -- --- .-. ... . / -.-. --- -.. . / .-. --- -.-. -.- ...

Example 2
* input: ./morse -- --- .-. ... . / -.-. --- -.. . / .-. --- -.-. -.- ...
* Output: MORSE CODE ROCKS
