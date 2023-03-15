# Regex Tutorial

Regex, short for "regular expression", is a sequence of characters that forms a search pattern. It is a powerful tool used in computer science and programming for manipulating and analyzing text data.

Regex is used to match specific patterns in strings or text documents. It provides a way to define a pattern of characters to match and can be used to validate user input, extract specific data from a larger set, and manipulate or transform text data.

Regex is supported in many programming languages and software applications, including Python, Java, JavaScript, and many more. The syntax of regular expressions can vary slightly between implementations, but the fundamental concepts remain the same.

## Summary

In this tutorial, we will cover the proper use a regex to match emails, with the following expression: /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
The regular expression starts with the caret (^) anchor, which denotes the start of the string, and ends with the dollar sign ($) anchor, which denotes the end of the string. This means that the regex will only match strings that start with the pattern specified and end with the pattern specified.

### Quantifiers
The following quantifiers are used in the regex:

- +: matches the preceding pattern one or more times
- {2,6}: matches the preceding pattern between 2 and 6 times

### OR Operator
There is no use of the OR operator in this regex.

### Character Classes
The following character classes are used in the regex:

- [a-z0-9_\.-]: matches any lowercase alphabet, digit, underscore, period, or hyphen
- [\da-z\.-]: matches any digit, lowercase alphabet, period, or hyphen
- [a-z\.]: matches any lowercase alphabet or period

### Flags
There are no flags used in this regex.

### Grouping and Capturing
The regex uses grouping and capturing by enclosing certain parts of the pattern in parentheses:

- ([a-z0-9_\.-]+): captures one or more lowercase alphabets, digits, underscores, periods, or hyphens before the @ symbol
- ([\da-z\.-]+): captures one or more digits, lowercase alphabets, periods, or hyphens after the @ symbol and before the period
- ([a-z\.]{2,6}): captures a sequence of lowercase alphabets and periods between 2 and 6 characters long after the period

### Bracket Expressions
- [a-z0-9_.-]: matches any lowercase alphabet, digit, underscore, period, or hyphen
- [\da-z.-]: matches any digit, lowercase alphabet, period, or hyphen
- [a-z.]: matches any lowercase alphabet or period

### Greedy and Lazy Match
The regex does not use lazy matching.

### Boundaries
The regex does not use any boundary matching.

### Back-references
The regex does not use any back-references.

### Look-ahead and Look-behind
The regex does not use any look-ahead or look-behind assertions.

## Author
Dhruvin Patel 

I am UCF coding bootcamp student and my github link is: https://github.com/dhruvin0777 
