# Regex of a Hex Value

    Have you ever wanted to find a Hex Value in a whole pile of data or a whole text? Me neither, I don't even know What a Hex Value is or what it's used for, but let's do it. This will go over how to use a regex to find Hex Values in any pile of text or code.

## Summary

    The regex that I will be going over is for a Hex Value or Hex Values, Which would look something like this: 
        /^#?([a-f0-9]{6}|[a-f0-9]{3})$/ or ([a-f0-9]{6}|[a-f0-9]{3})
    
    Example Hex Values:
        abcdef
        1ab23c
        123456
        126
        abc
        a2f

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Summed Up](#summed-up)

## Regex Components

    This regex has many components such as: 

        anchors which are "^" and "$", 

        quantifiers which are "?", "{6}" and "{3}",

        grouping constructs which is "()",

        bracket expressions which is "[]",

        character classes which are "a-f" and 0-9,

        and OR operator which is "|",

        this regex does not contain any flags or character escapes.

### Anchors

    The anchor "^" states where the string starts, while the anchor "$" states where the string ends.

### Quantifiers

    The quantifier "?" states that the matches of the pattern is either zero or one, while the quantifiers of "{6}" and "{3}" states that the matches of the pattern is 6 times and 3 times.

### Grouping Constructs

    The grouping construct "()" states the pattern that is trying to be matched and the quantity of it.

### Bracket Expressions

    The bracket expression "[]" states the pattern that is trying to be matched.

### Character Classes

    The character classes "a-f" states that it's trying to match with a letter of either a, b, c, d, e, or f, while "0-9" states that it's trying to match with a number between 0 to 9.

### The OR Operator

    The OR operator "|" states that it's either matched with one set of pattern or another.

### Summed Up

    To sum everything up:
        "a-f0-9" states that it's either an a, b, c, d, e, f, or a number from 0 to 9, and "{6}" states that it's matched 6 times. You can look at the examples of Hex Values on the Summary. "|" states that the first part is viable or the next part is viable too, which is mostly the same but with "{3}" which states that it's matched 3 times. Again, examples can be seen on the summary.
    
    So a Hex Value can be either 6 or 3 characters long, containing any combanation of numbers between 0 to 9 and/or a, b, c, d, e, or f.

## Author

    Sichoun Nplhaib Lee - https://github.com/DDXP3

## Credits

    https://coding-boot-camp.github.io/full-stack/computer-science/regex-tutorial