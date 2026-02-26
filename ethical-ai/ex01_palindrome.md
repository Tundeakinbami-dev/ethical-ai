1. Writing a Pseudocode for a Function to check if a word is palindrome

def isPalindrome(word)
left = 0
right = len(word)-1
while left < right
if word [left] != word [right]
Return false
left += 1
right -= 1
return true

//calling the function
result = isPalindrome(word)
print(result)

2. Using Python to Implement the code and Testing with Examples like 'racecar', 'hello', and 'A man a plan a canal Panama'.

```python
def isPalindrome(word)
//left is set to 0
left = 0
//right is length of word minus 1
right = len(word)-1
//while left is less than right
while left < right
//if length of word is not equal to right the function should return false
if word [left] != word [right]
Return false
//increment left by 1 to move pointers inward
left += 1
//decrement right by 1 to move pointers inward
right -= 1
return true
```

//calling the function

result = isPalindrome("racecar")
print(result)
result = isPalindrome("hello")
print(result)
result = isPalindrome("A man a plan a canal Panama")
print(result)

3.  I learnt this using enough online search resources to understand what palindrome means,and how to write palindrome using pseudocode.

I have a clearer understanding compared to when i started learning what pseudocode means.

Presently, I can now write a similar pseudocode function perfectly without the help of AI.
