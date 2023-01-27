# Java-17-Challenge

Hi, My name is Jeremiah and I will be presenting an example using Regex (Regular Expression).

## Summary

The regex I will be using for my project is Matching An Email. 
I will be explaining the tools suhch as an anchor and quantifers that helps understand Regex. 
For example, /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ is an expression. 
The [a-z] is a string that can contain any lowercase letter between a-z. 
The [0-9] is a strig that can contain any number between 0-9. The [.-]+)@([] can contain any symbol that contains a .-]+)@([. 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)

## Regex Components
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/


### Anchors
The ^ anchor signifies a string that begins with the characters that follow it. This could be in one of two formats.
The $ anchor signifies a string that ends with the characters that precede it.
For example,  when i use  ^The , it will become the exact string of "The". We would not use "the", because regex is case sensitive.

### Quantifiers
I use quantifiers a few times in my expression above. The quantifiers sets the limit of the string that my regex matches.
The "+" sign in my regex means the pattern matches one or more times.
The curly brackets "{}" would provide three different ways to set limits for a match.
I used an example I learned online, which showed me how I can set a minimum and maximum character limit for a unsername.
The {3,16} quantifier would mean a pattern thats minimum od 3 times and a maximum of 16 times.


### Bracket Expressions
The [a-z] is a string that can contain any lowercase letter between a-z.
The bracket expression is anything inside a set of squared brackets.
The hyphen and underscore (-_)  are special characters between the alphanumeric characters to represent a range of the possible characters. 
Another bracket expression is [0-9], which is when string can contain any number between 0–9.
When I put all of the expressions I mentioned above to make a pattern, it will look like this [a-z0-9_-]. This expression is an example that will match any string that includes any combination of lowercase letters between a and z, any number between 0 and 9, and the special characters of an hyphen or undderscore.

## Author

Jeremiah Warren

I would like to really thank my instructors for taking the time out of their lives to help guide me to the top.


[Jeremiah GitHub](https://github.com/Jwarren619?tab=repositories)