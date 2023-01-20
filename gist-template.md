# Hex Value Regex

Regular Expressions or Regex's are a Sequence of characters that help specify a search pattern in text, a Hexidecimal (Hex) expressions are a positional system that use 16 individual symbols

## Summary

The Regex code that will be analyzed is the follow ing string: /^#?([a-f0-9]{6}|[a-f0-9]{3})$/  This Hexidecimal code allows us to recognize and find any hexidecimal code.

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

### Anchors

To start off are the Anchors related to the Code, They are ^ and $,

this ^ character signifies the start of the string and this $ signifies the end of the string. An example of this is a regex that starts with  ^ABC wont match a string starting with ABC and XYZ$ wont match any string that doesn't end with XYZ. The regex uses these particular characters to make sure that it matches the full expression.

### Quantifiers

After the Anchors of the expression we move on to the quantifiers that address the Values by declaring them with a ? and {X}. ? matches any proceeding character 0-1 times. This forms a conditional inside of the Regex equation. Since # is proceeded by ?, the expression will match a string that begins with a # or wont match a string.

### OR Operator

The Regex has one large grouping ([a-f0-9]{6}|[a-f0-9]{3}) which is split by the OR operator of |. This signifies the our group has 2 Expressions [a-f0-9]{6} as well as [a-f0-9]{3}. this means our regex will match either of the two parameters set by the expressions. 

### Character Classes

The Character Classes inside of this regex equation are [a-f0-9] which is repeated twice. This creates the Ranges of a-f and 0-9 for the specific section of the Regex. An important side note is this only includes lower case letters from a to f and then the numbers 0-9. 

### Grouping and Capturing

This Regex expressions grouping is combined with the OR Operation and character classes

## In closing:

The way that this expression is described overall is a sequence of characters that start with # or not, with 6 characters in the ranger of a-f and 0-9 OR followed by 3 characters in the same range. 

## Author

Hi, im isaac Thorell, I am a Fullstack Developer student who is always growing and learning, I really enjoy the Backend behind different websites and the connections that need to be formed. 

Github: Ithorell

