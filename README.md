Regex Tutorial
A Regular expression defines a search pattern that can check if a string contains certain letters, numbers, special characters, sets or combinations, and even white spaces.

Summary
This regex tutorial will explain the validation process of an email address for jonathan.doe@gmail.com.

/^[a-z0-9._%+-]+@[a-zA-Z0-9.-]+.[a-zA-Z]{2,}$/

// will enclose the regex string

^ start of the string

[a-z0-9.%+-] matches any character in the string

+will match as many times as possible

@ matches the character '@'

. matches the character '.'

{2,} matches the previous token to as many times possible

$ indicates the end of the string

Table of Contents
Anchors
Quantifiers
Grouping Constructs
Bracket Expressions
Character Classes
The OR Operator
Flags
Character Escapes
Regex Components
A regular expression is literal, meaning that it must be wrapped in slash characters (/) for the start and end of the expression.

Anchors
Anchors are symbols that signify the beginning (^) and ending ($) of the expression.

Quantifiers
Quantifiers are considered 'greedy' in that they match as many instances in a pattern as possible. += one or more matches

*= zero or more matches

?= zero to one time

{} = will match a pattern exactly in different ways {8}, {8,}, {8,16} Which means it will find the preceded pattern a minimum of 8 times , max of 16 times.

[] = Represents a range of characters. [a-z]

[a-z] = Lowercase range

[A-Z] = Uppercase range

[0-9] = numeric or digit range

[!@#$%&*_-] special character or nonalphanumeric range

Quantifiers
Quantifiers can be made negative by using ? Symbol after it so it will match as few instances as possible

Grouping Constructs
Grouping Constructs utilize parenthasis (()) to separate multiple groups or subexpressions in the same expression.

Bracket Expressions
Bracket expressions represent anything inside the square brackets ([]) as a positive range of characters or patterns that contain all the characters we want to include.

Character Classes
A Character Class defines a set of characters to match any one in the string for a full match. Positive and negative character groups are also character classes.

The OR Operator
The OR operator (|) can be used to verify this expression like 1|2|3 to find any one match.

Flags
Flags are located at the outside right of the expression and indicate how to search 'g' = Global search for all possibilities in the string.

'i' = Insensitive case search in the string

'm' = Multi-line search

Character Escapes
A backlash () is a character that escapes another characters literal position

Author
My name is Rhonda Van Dam and I am a Junior Full Stack Web Developer. You can view more of my work at my GitHub address. https://github.com/Rhondoid
