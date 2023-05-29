# RegEx Tutorial

RegEx also called regular expressions are code sequences used to define search patterns for specific coding inputs. These can be used to validate patterns for search inputs, text inputs, database inputs etc. 

## Summary

Regular expressions for email are used to validate user name, seperator, and domain. A common regex pattern is :
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Boundaries](#boundaries)

## Regex Components

### Anchors
In regex anchors are used to denote the beginning and end of a specific section of regex. In our email regex ^ indicates the beginning of a string and $ indicates the end of that same string.
### Quantifiers
In regex quantifiers are used to set a limit on how many characters are in a string of a preceding token. ([a-z\.]{2,6}) indicates that this section of the regex pattern can any lowercase letter a-z and must be between 2 and 6 letters.
### Character Classes
Character classes indicate what character types can be used in differenct sections of the regex sequence. These can include letters, digits, special characters, white space, hexadecimal digits and words. ([a-z0-9_\.-]+) indicates this section of the regex can be any lower case character a-z, any signal digit number 0-9. and special characters _/.-
### Flags

Flags are special identifiers that can added to regex in order to give it a special functionality. A lower case G placed at the end of the regex sequence gives that input the ability to enact a global search which creates an array of previously inputted values and looks for the closest matching input as you are typing.
### Grouping and Capturing
Captured groups specify what characters can be used between specific anchors. Paranthesis () denote a strict series of characters while square brackets [] denote that a range can be used.
### Bracket Expressions
As mentioned before bracket expressions tell us what range of character types we are allowed to use in a specific regex section. [da-z] tells us that we can use any range of digits or lowercase letters a-z.
### Boundaries
Boundaries allow you to anchor different sections of the regex sequence to indicate the beginning and end of specific rule. An ^ and $ indicate the beginning and ending of a string, square brackets [] indicate the beginning and end of a possible character range. b\ /b indicate the beginning and end of a strict word boundary.

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
James Pierce is the author of this regex document. Sites used are https://www.regexpal.com/?fam=104026, and https://cheatography.com/davechild/cheat-sheets/regular-expressions/. My github is [james59222](https://github.com/james59222)
