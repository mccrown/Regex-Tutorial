# Regex Tutorial

This is a tutorial to explain the meaning and function of regex characters. This will be done by breaking down each character one by one.

## Summary
The regex that I will break down will be for matching an email. It consists of this bit of code.

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)


### Anchors
The Anchors included in the section of code include the following:
* `/` These will be on the outside of an expression calling the start and end of the expression
* `^` This signifies the beginning of a string and matches it. It does not however match a character. It only matches the position.
* `$` This is the symbol for the end of a string and matches it. It does not however match a character. It only matches the position.

### Quantifiers
The Quantifiers included in the section of code include the following:
* `+` This needs to match one or more tokens in front of it
* `{2,6}` This will match 2-6 of the tokens in front of it

### Character Classes
The Character Classes included in the section of code include the following:
* `[]` (character set) This matches the characters within the brackets to the characters in front of a string are not in brackets
* `\.` (escaped character) This matches a '.' and the dot matches any character with exception to line breaks. It also is equal to `[^\n\r]`.
* `a-z` (range) This matches the characters in the range from a through z
* `0-9` (range) This matches the characters in the range from 0 through 9
* `_` (character) This matches a '_'
* `-` (character) This matches a '-'
* `@` (character) This matches a '@'
* `\d` (digit) This will match any number character from 0-9

### Grouping and Capturing
The Grouping and Capturing characters included in the section of code include the following:
* `()` (character set) This groups everything inside and makes a capture group. It can then be extracted as a substring or used as a backreference.

### Bracket Expressions
The Bracket Expressions included in the section of code include the following:
* `[]` (character set) This matches the characters within the brackets to the characters in front of a string are not in brackets


## Author

Conner McCown