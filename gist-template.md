# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components
The '.' will match any single character. For example .ought matches cought, tought etc. 

The '\' lets special characters be used as a single character. for example \.html$ matches any string ending in .html, note the following characters need to be proceeded by a '\'.

The '$' will match any string where the cpecified pattern occurs at the end of the string. For example $line matches 'line', 'pipeline' but not 'lines'.

The '^' matches any string where the specified pattern occurs at the beginning of the string. For example '^line' matches 'lines', 'line' but not 'pipeline', note to be careful when specifying a domain. ^/line will match /line/index.html but not www.domain.com/line.index.html

The '[]' matches any single character in a range or enclosed in brackets. For example '[aeiou]' matches any vowel and '[0-9]' matches any number. using '^' with [^a-z] will find any character that is not a letter.

The '|' indicates an OR operator, for example 'line|car' finds 'car', or 'line'.

The '()' is used for grouping expressions. for example (line[0-9])|(car[0-9]) matches 'line33A' or 'fast_car95b' but not 'line'.

Any single character by itself will match a string containing the single character, for example 'i' matches 'line' but not 'car'.
### Anchors
Anchors dont actually match any characters rather they assert something about the 
string or matching process. 

### Quantifiers
Quantifiers match a number of instances of a character, group, or character class in a string.

### OR Operator
The “or” operator can be used to provide options to match more than one instance.

### Character Classes
A character class allows you to match any symbol from a certain character set.

### Flags
A flag is an optional parameter to a regex that modifies its behavior of searching.

### Grouping and Capturing 
Grouping and capturing enables us to use multiple expressions to check multiple things.

### Bracket Expressions
Bracket expressions allow matching multiple characters or a character range at a position.

### Greedy and Lazy Match
Greedy means your expression will match as large a group as possible, lazy means it will match the smallest group possible.

### Boundaries
Word boundaries match before the first and after the last word characters in a string, as well as any place where before it is a word character or non-word character, and after it is the opposite.

### Back-references
back-references are regular expression commands which refer to a previous part of the matched regular expression.

### Look-ahead and Look-behind
Lookbehind means to check what is before your regex match while lookahead means checking what is after your match.

## Author
Brett Elliott. With the help of google

