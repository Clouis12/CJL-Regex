# CJL-Regex

# Regex Tutorial on Matching URL.
This is a regular expression that is using an http or https url for websites with very limited special characters in the domain name. 


## REGEX IS
/^(https?:\/\/)?([\da-z\.-]+)\.([a-z\.]{2,6})([\/\w \.-]*)*\/?$/

## Table of Contents

- [Anchors](#anchors)
- [Group and Lazy Match and Bracket Expressions](#Group-and-Lazy-Match)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes and Greedy Quantifier](#greedy-and-lazy-match)



### Anchors 

This Anchor ^ caret symbol indicates that this regular expression must have a match from the beginning.

This Anchor $ dollar symbol indicates that this regular expression must have a match to the end.

### Group and Lazy Match and Bracket Expressions

the s? (lazy match) implies  that the s in https is optional meaning that the http or https is acceptable.

 (https?:\/\/)? (Group because of () ) This means that the prefix http:// or https:// is optional because of the ?.

 ([\da-z\.-]+) \d is equal to any digit from 0-9 or any lower case letter from a-z or \. which is just a normal period or - anything that was just mentioned must appear at least once because of the quantifier + symbol (one or more). [] is a Bracket expression (meanings each item is optional)

### Character Classes and Greedy Quantifier

 [a-z\.]{2,6} (Character Class and Greedy) any lower case letter or a period that appears at least two times but not more than six. 

 * is a quantifier that means 0-many. [\/\w \.-]* this means  \/ a literal or \w  means lowercase letter a-z or any uppercase letter or any number 0-9. 


## Author Christian Louis

Link to Github code: https://github.com/Clouis12/CJL-Regex




