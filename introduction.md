# Regular Expression Introduction

## Regular Expression Modifiers
**Modifiers** can be used to perform case-insensitive more global searches:

| Modifier | Description |
|:--|:--|
| i | Perform case-insensitive matching |
| g | Perform a global match rather than stopping after the first match |
| m | Perform multiline matching |

## Regular Expression Patterns

**Brackets** are used to find a range of characters:

| Expression | Description |
|:--|:--|
| [abc] | Find any of the characters between the brackets |
| [0-9] | Find any of the digits between the brackets |
| (x\|y) | Find any of the alternatives separated with \| |

**Metacharacters** are characters with a special meaning:

| Metacharacter | Description |
|:--|:--|
| \d | Find a digit |
| \s | Find a whitespace character |
| \b | Find a match at the beginning of or at the end of a word |
| \uxxx | Find the Unicode character specified by the hexadecimal number xxx |

**Quantifiers** define quantities

| Quantifier | Description |
|:--|:--|
| n+ | Matches any string that contains at least one *n* |
| n* | Matches any string that contains zero or more occurrences of *n* |
| n? | Matches any string that contains zero or one occurrences of *n* |


## Recommendation
A good site to exp and understand regular expression:
[regex101](https://regex101.com/)

## Reference
[W3School](https://www.w3schools.com/js/js_regexp.asp)