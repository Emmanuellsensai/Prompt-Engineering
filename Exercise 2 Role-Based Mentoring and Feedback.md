# Exercise 2: Role-Based Mentoring and Feedback

## Objective: Use role-based prompts for personalized feedback.

### PROMPT: Act as a mentor reviewing this code. Provide corrections and explain improvements.
```python
users={}
print("Users dictionary initialized:", users)
print("Ready to build!")
```
### OUTPUT: 
> ## Code Review & Corrections
>The provided code contains **syntax errors** that will prevent it from running. Below is the corrected version and a brief explanation of the improvements.
>
>### Corrected Code
>
>```python
>users = {}
>print(f"Users dictionary initialized: {users}")
>print("Ready to build!")
>
>```
> ### Key Improvements
>
>* **Syntax Fix:** Python requires a **comma** or **f-string** to separate a string from a variable in a `print()` function; your original code was missing a separator after the string.
>* **F-Strings:** I used an **f-string** (`f"..."`) for the first print statement, which is the modern, readable standard for embedding variables directly into strings.
>* **Quote Closure:** Your second print statement was missing a starting quotation mark (`"`), which would cause a `SyntaxError`.

### Review the response and check if the role influences feedback style.
> The response was detailed and highlighted steps on what to change in the code like a coding instructor would, although it gave direct answer to the question.