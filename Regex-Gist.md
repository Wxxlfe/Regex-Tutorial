# Rexex tutorial (replace with your title)
Today we will be going over the concept of Regex, something im not too familiar with so right along side of you,
I will be learning and researching this topic aswell. To my understanding a Regex or Regular Expression is a sequence of characters that
form a search pattern. It is mainly used for pattern matching within strings. Reges allows you to specify rules for seaching and manipulating
stings. Regex patterns can match specific characters, character ranges, or even complex sequences of characters.
Introductory paragraph (replace this with your text)

## Summary
```regex
[A-Za-z0-9._%+-]+@[A-Za-z0-9.-]+\.[A-Za-z]{2,}
 Here we have a Regex that is used to match and extract all emails from a text.


Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components

### Anchors
in this example of a regex, it does not contain an anchor but, anchors are used to specify position in the text such as the (^)
or and end ($)

### Quantifiers
the + quantifier is used to match one or more occurances of the preceding character class or group. 
its ensures that there's at least one occurence of the character class
the (2,) quatiifier is used to match two or more occurences of the preceding chracter class. it ensures there are at least two
letters in the top level domain part of the email

### Grouping Constructs
there are no explicit grouping constructs such as (()) parentheses used in the regex expression. Grouping constructs are used 
for grouping parts of the pattern together

### Bracket Expressions
[A-Za-z0-9._%+-] this matches any uppercase (A-Z), lowercase (a-z) letters or digits (0-9), also special characters (._%+-)
it allows for commonly found characters in an local part of an email address to be found
[A-Za-z0-9.-] Similar to the previous character class, this one matches any uppercase letter,
lowercase letter, digit, or certain special characters (.-). It allows for characters commonly 
found in the domain part of an email address.
[A-Za-z] This character class matches any uppercase or lowercase letter. It's used to specify the TLD part of the email address.

### Character Classes
There are no Character Classes in this exoression

### The OR Operator
There is no explicit use of the OR operator (|) in this regex expression. 
The OR operator is used to specify alternatives within a pattern.
### Flags
There are no flags used in this regex expression. Flags are used to modify the behavior of the
regex engine, such as case-insensitive matching or multiline mode.

### Character Escapes
There are no character escapes (using \) in this regex expression. Character escapes are used
to match special characters literally or to represent characters that have special meanings in
regex.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
