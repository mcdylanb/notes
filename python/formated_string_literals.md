### Problem 
- while working on python using variables in a string is different compared to C or Java

### Solution
- there are couple solutions, but one of them is called **Formatted String Literals**

### Formatted String Literals
- A formatted string literal or f-string is a string literal that is prefixed with 'f' or 'F'. These strings may contain replacement fields, which are expressions delimited by curly braces {}. While other string literals always have a constant value, formatted strings are really expressions evaluated at run time.

### Example
```
>>> name = "Fred"
>>> f"He said his name is {name}."
"He said his name is 'Fred'."

### Resource
- (https://docs.python.org/3.6/reference/lexical_analysis.html#f-strings)[https://docs.python.org/3.6/reference/lexical_analysis.html#f-strings]
- (https://matthew-brett.github.io/teaching/string_formatting.html)[https://matthew-brett.github.io/teaching/string_formatting.html]
