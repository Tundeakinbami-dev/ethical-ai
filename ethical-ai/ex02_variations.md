```python

def isPalindrome(word)

left = 0

right = len(word)-1

while left < right:

if not word [left].isalnum():
left += 1
continue

if not word [right].isalnum():
right -= 1
continue

if word[left].lower() != word[right].lower():
return false

left += 1
right -= 1

return true

result = isPalindrome("racecar")
print(result)
result = isPalindrome("hello")
print(result)
result = isPalindrome("A man a plan a canal Panama")
print(result)
```

After prompting the AI to make it more efficient, it removed some duplicate syntaxes which i didnt consider at first.
