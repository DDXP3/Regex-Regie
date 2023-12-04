# Regex of a Hex Value

    Have you ever wanted to find a Hex Value in a whole pile of data or a whole text? Me neither, I don't even know What a Hex Value is or what it's used for, but let's do it. This will go over how to use a regex to find Hex Values in any pile of text or code.

## Summary

    The reges that I will ge going over is for a Hex value or hex values, Which would look something like this: 
    `/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)

## Regex Components

    This regex has many components such as: 
    
    "^" and "$" which are "anchors", 

    "{}" which is "quantifiers", 

    "()" which is "grouping constructs", 

    "[]" which is "bracket expressions", 

    ".", "\d", "\w", and "\s" which are all "character classes" each which have their own class as implied such as:
        "." which matches any character except the newline character,

        "\d" which matches any arabic numeral digit, which is also equivalent to the bracket expression "[0-9]",

        "\w" which matches any alphanumeric character from the basic latin alphabet, including the underscore "(_)", which is also equivalent to the bracket expression "[A-Za-z0-9_-]",

        and "\s" which matches a single whitespace character, which also includes tabs and line breaks.
    
    and "|" which is "the OR operator".

    This regex does not contain any flags or character escapes.

### Anchors

### Quantifiers

### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
