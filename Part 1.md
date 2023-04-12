# Functions:

<details>
  <summary>- What statement will terminate the function?</summary>
  
    Return statement.
</details>

<br></br>

<details>
  <summary>- If such statment is missing, what will the function return?</summary>
  
    The function will return None.
</details>

<br></br>

<details>
  <summary>- What problems do round() and round(1,2,4) have?</summary>
  
    The first one needs input, the second one have too many inputs.
</details>

# Logic evaluations:

<details>
  <summary>- What's the possible outcomes of boolean value?</summary>
  
    It's either True or False.
</details>

<br></br>

<details>
  <summary>- When will the Statements connected with AND, return True?</summary>
  
    If and only if, ALL the statements are evaluated as True.
</details>

<br></br>

<details>
  <summary>- When will the Statements connected with AND, return False?</summary>
  
    If one of the statements are evaluated as False.
</details>

<br></br>

<details>
  <summary>- When will the Statements connected with OR, return True?</summary>
  
    If one of the statements are evaluated as True.
</details>

<br></br>

<details>
  <summary>- When will the Statements connected with OR, return False?</summary>
  
    If and only if, ALL the statements are evaluated as False.
</details>

<br></br>

<details>
  <summary>- What's lazy evaluation?</summary>
  
    If multiple statements are connected with logical operators, the results will be evaluated from left to right.
</details>

# Conditional Statement:

<details>
  <summary>- Explain if (cond 1 -> Do A)/elif (cond 2 -> Do B)/else (cond 3 -> Do C) statements</summary>
  
    If statement first, condition 1 satisifed => Do A.
    If condition 1 not statisfied and elif condition satisifed => Do B.
    If both conditions are not satisfied => Do C.
</details>

<br></br>

# Loop(s)

<details>
  <summary>- What is loopable?</summary>
  
    String, List, File, (Dictionary)
</details>

<br></br>

<details>
  <summary>- Is list mutable?</summary>
  
    Yes, i.e. list[0] = 1 is valid.
</details>

<br></br>

<details>
  <summary>- Is string mutable?</summary>
  
    No, operations like string[0] = 'a' is not valid.
</details>

<br></br>

<details>
  <summary>- What's length and index?</summary>
  
    Length is the #of elements, index is the location of the element.

</details>

<br></br>

<details>
  <summary>- How to index the same variable using different numbers?</summary>
  
    Index from left to right, 0 to len() - 1. Or index from right to left, -1 to - len().

</details>

<br></br>

<details>
  <summary>- What are the numbers in range(n)?</summary>
  
    0, 1, 2, ..., n-1.

</details>

<br></br>

<details>
  <summary>- What's are the equivalent ways of expressing range(n)?</summary>
  
    range(0, n) and range(0, n, 1).

</details>

<br></br>

<details>
  <summary>- What are the 3 types of loop? And what are the differences?</summary>
  
    For item loop --- For item in ___ (Can't do modification)
    For index loop --- For index in range(len()) (Can do modification)
    While loop --- initialize i, while i ___, i = ___ (Can do modification)

</details>

# List & String:

<details>
  <summary>- What does append() list method do? What does it return?</summary>
  
      It append ONE element to end of list, return NONE.

</details>

<br></br>

<details>
  <summary>- What does extend() list method do? What does it return?</summary>
  
      It add ONE LIST to end of list, return NONE.

</details>

<br></br>

<details>
  <summary>- What does pop() list method do? What does it return?</summary>
  
      It removes the last element and return the same element.

</details>

<br></br>

<details>
  <summary>- What does remove(item) list method do? What does it return?</summary>
  
      It removes the item from list, return NONE.

</details>

<br></br>

<details>
  <summary>- What does insert(item, index) list method do? What does it return?</summary>
  
      It inserts the item at the index, move the items behind the index one more back, return NONE.

</details>

<br></br>

<details>
  <summary>- What does sort(reverse = True/False) list method do? What does it return?</summary>
  
      It sorts the list ascending(reverse = False, default)/descending(reverse = True) order, it returns NONE.

</details>

<br></br>

<details>
  <summary>- How to concat two strings?</summary>
  
      use "+" operator, i.e 'a' + 'b'.

</details>

<br></br>

<details>
  <summary>- What does find(substring) string method do?</summary>
  
      It returns the STARTING index of the substring in the string, if such substring not found, return -1.

</details>

<br></br>

<details>
  <summary>- islower(), isupper(), isdigit()?</summary>
  
      islower(), isupper(), isdigit returns True if the string is ALL lower/upper/digit. Otherwise return False.

</details>

<br></br>

<details>
  <summary>- What does lower(), upper() string method do? What will happen if the string has digit?</summary>
  
      Returns all lower/upper case input string, the digits will not be affected.

</details>

# Dictionary:

<details>
  <summary>- What properties should the keys have?</summary>
  
      The key should be immutable, i.e. a string.

</details>

<br></br>

<details>
  <summary>- Any requirements for the values in the dictionary?</summary>
  
      The values can be anything.

</details>

<br></br>

<details>
  <summary>- What methods do you use to get the keys and values in the dictionary?</summary>
  
      dict.keys() and dict.values().

</details>

<br></br>

<details>
  <summary>- What are the different ways of deleting keys in the dictionary?</summary>
  
      del dict[key] and dict.pop(key). The first one returns None, the latter one returns the corresponding value.

</details>

<br></br>

<details>
  <summary>- How to add key/value pairs in the dictionary?</summary>
  
      dict[new_key] = value

</details>

<br></br>

<details>
  <summary>- What happens if we call a new key in the dictionary? i.e. dict[new_key]</summary>
  
      It gives a key error.

</details>

<br></br>
