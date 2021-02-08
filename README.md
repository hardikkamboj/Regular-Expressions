# Regular-Expressions

## Match method
re.match(pattern,text) -> searches for the pattern only in the beginning of the string. 

This [file](https://github.com/hardikkamboj/Regular-Expressions/blob/main/RegularExpressionOperations-match.ipynb), covers the following topcis - 
  - Difference between raw string and python string. 
  - match method in re library
  - how to write unit test 
  
## Search, findall,finditer and groups
re.search(pattern,text) -> returns the first match in the text.
re.findall(pattern,text) -> returns a list of all the matches.
re.findieter(pattern,text) -> returns an iterator

This [file](https://github.com/hardikkamboj/Regular-Expressions/blob/main/RegularExpressionOperations-search%2Cfind_all%2Cfind_iter%2Cgroups.ipynb),covers the following topic - 
  - search method in re, and how its different from match
  - findall mehod
  - finditer, and how it covers up the possible disadvantage of findall
  - groups, and how we can name the groups.

## Find and replace, Split
re.sub(pattern, replacement pattern / function, text) -> returns the text where the string matching the pattern is replaced by a string given by the replacement pattern / function 

[This file](https://github.com/hardikkamboj/Regular-Expressions/blob/main/RegularExpressionOperations-Find%20and%20replace%2C%20split.ipynb) covers the following topic- 
  - using re.sub with a pattern 
  - using re.sub with a user defined function 
  - re.split
  
## Single character patterns
[This file](https://github.com/hardikkamboj/Regular-Expressions/blob/main/Single%20character%20pattern%2C%20wildcard.ipynb) covers the following topic - 
  - searching for a single character, and making the search case insensitive. 
  - Using range of characters to search, eg, [a-z]
  - Using wildcard .(dot) to find all characters also, how can we search if we want to search a dot.
  - Finding newlines, using hexadeciaml code and unicode. 
  
## Anchors 
[This file](https://github.com/hardikkamboj/Regular-Expressions/blob/main/Anchors.ipynb) covers the following topic - 
  - searching for a given word (using word boundary)
  - searching for a word at beginning of a string ( by using '^' )
  - enabling multiline mode and searching for a word at the beginning of all lines. 
  - searching for a word at the end of a string (by using '$' )
  - enabling multiline mode and searching for a word at the end of all lines

## Character classes
[This file](https://github.com/hardikkamboj/Regular-Expressions/blob/main/Character%20classes.ipynb) covers the following topic - 
  - searching for word digits using \d character class
  - searching digits in other scripts than english
  - using negation \D
  - seaching for alpa numeric characters using \w
  - using \w in devnagari script
  - using the negation of \w, which is \W
