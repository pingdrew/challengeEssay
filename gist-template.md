# Computational Writing

This project for the ut coding bootcamp is about practicing technical writing skills by laying down thoughts about key computer science concepts in a professional manner so I can get better at using key words to better describe things.

## Summary

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

## Regex Comp1nts

### Anchors

Anchors are special characters used in regular expressions to specify where a match should occur within a string. The `^` anchors the match to the start of a line, ensuring the pattern begins there, while the `$` anchors it to the end, ensuring the pattern concludes at that position. Anchors help define the boundaries for pattern matching.

### Quantifiers

Quantifiers are symbols that determine the number of times a particular element or group should occur in a regular expression. For instance, the `*` denotes 0 or more occurrences, the `+` signifies 1 or more occurrences, and the `?` indicates 0 or 1 occurrence. Quantifiers are crucial for specifying repetition in patterns.


### Grouping Constructs

Grouping constructs are denoted by parentheses in regular expressions and serve to create subpatterns within a larger pattern. They allow you to apply quantifiers, alternations `the OR operator`, or other modifiers to a specific group of characters. Grouping makes it easier to control and capture parts of a matched text.


### Bracket Expressions

Bracket expressions, enclosed within square brackets [], define character sets or ranges that the regular expression should match. For example, `a-z` matches any lowercase letter, `0-9` matches any digit, and `aeiou` matches any vowel. Bracket expressions offer a way to specify character choices within a pattern, increasing pattern flexibility.


### Character Classes

Character classes are predefined sets of characters represented by a `\` followed by a specific letter or character. For example, `\d` represents digits `0-9`, `\w` represents word characters `letters, digits, and underscores`, and `\s` represents whitespace characters `spaces, tabs, line breaks`. Character classes simplify the inclusion of common character sets in patterns.


### The OR Operator

The OR operator, denoted by the `|`, allows you to specify multiple alternatives within a regular expression. It enables the pattern to match any 1 of the specified alternatives. For instance, `cat|dog` matches either `cat` or `dog`. The OR operator is helpful for pattern branching.


### Flags

Flags are modifiers that can be added to the end of a regular expression to change its behavior. Common flags include `i` for case-insensitive matching, `g` for global matching `finding all matches`, and `m` for multiline matching `treating each line as a separate string`. Flags tailor how the regular expression engine processes patterns.


### Character Escapes

Character escapes are sequences that start with a `\` followed by a character. They are used to match specific characters literally, even if those characters have special meanings in regular expressions. For instance, `\n` represents a newline character, and `\t` represents a tab character. Character escapes prevent these characters from being interpreted as part of the regex syntax.

## Author

Andrew Wilson, current student of the UT full-stack flex 3 month coding bootcamp as of August 25th, 2023.

Github profile:
https://github.com/pingdrew