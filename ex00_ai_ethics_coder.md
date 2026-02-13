# PART A

## Write down your honest answers:

### How have you used AI for coding so far?
I use AI as a tool to assist me in situations where i'm stuck.

### Do you ask AI for solutions before trying yourself?
No, i don't ask AI for solutions before i try solving, i try to solve first and i use Ai to check for cases where i can't find solutions or to confirm if i missed a step.

### Can you explain code you've submitted without AI's help?
yes i can explain codes i write without AI, i use AI when i'm stuck for problem solving

### What would happen if AI was suddenly unavailable during an exam or interview?
i will solve the problem to the best of my ability, i believe every problem has a solution with multiple approaches

## Identify your current pattern: Which learner are you now? 
### Learner B: "AI is my learning amplifier"

Attempts the problem first

Asks: "Why does this approach work? What are the trade-offs?"

Tests understanding by explaining concepts

Uses AI to explore deeper, not to avoid thinking

### Write a brief paragraph: Where are you now, and where do you want to be?
I am a learner who uses Ai to amplify my learning but i want to reach a level where i have very little dependency on Ai, i want to use Ai to speedup productivity.



# PART B

## PALINDROME SOLUTION 

```python 
def is_palindrome(word):

    for char in " ,.!?":
        word = word.replace(char, "")
    
    length = len(word)

    word = word.lower()

    
# length = 7
    #0 != 7-0-1 then give false if not give true
    # R A C E C A R
    # 0 1 2 3 4 5 

    for w in range(0, length // 2):
        if (word[w] != word[length-w-1]): 
            return w
    return True

string1 = "racecar"
print(is_palindrome(string1))

string2 = "hello"
print(is_palindrome(string2))

string3 = "A man a plan a canal Panama"
print(is_palindrome(string3))

```

## REFLECTION

### What did you learn by struggling first?
I learn to understand the problem before even looking for a solution

### How is your understanding different than if you'd just asked for the solution?
My understanding is better because i know what i'm looking for and how to approach it

### Can you now implement similar functions (reverse a string, find duplicates) without AI?
yes i can do it without using AI

### What mental model did you build?
Solution oriented mindset, i look for solutions myself before seeking external help or support, more like the 15 minutes rule.



# PART D
## I will use AI when:

After I've attempted a problem for at least 20 minutes

To understand why my solution works/doesn't

To explore alternatives after I have a working solution

I want to be sure i've handled edge cases

## I will NOT use AI when:

I haven't tried the problem myself

I'm taking an assessment or test

I need to build fundamentals

I haven't understood the documentation of a particular language

## I know I'm using AI fairly when:

I can explain my code without looking at AI's response

I could solve similar problems without AI

I feel more confident in my abilities

I can explain problems to peers without help or being stuck

_EMMANUEL 10-02-2026_



# PART E: REAL-WORLD SCENARIO ANALYSIS

## Interview: "Explain how you'd implement a caching system." If you always relied on AI, can you answer?
if i always relied on AI to design systems i won't be able to answer the question because i don't know the basis of cashing system design, this is why we're meant to build and learn before asking Ai for assistance.

## Production bug at 2 AM: AI is unavailable. Can you debug code you don't fully understand?
Most likely i may not depending on the scenario, if it's a code i'm familiar with i might be able to debug it.

## New tech with little documentation: If you never learned to read docs and experiment, what happens?
i'll read the little documentation, search stack overflow if i'm having difficulties understanding a particular concept and check other people's work on that particular project to see their approach while i ask my peers.

## Write a paragraph: How does using AI fairly now prepare you for these scenarios?
First off i handle it to the best of my abilities, check reviews, ask for help from peers before i use Ai for difficult parts or concept.


# PART F: BUILDING IRREPLACEBALE SKILLS
## SKILL ASSESSMENT
|             *SKILL*                |   *RATING*   | 
|------------------------------------|--------------|
|Problem decomposition               |     4/5      |
|Systems thinking                    |     3/5      |
|Critical evaluati                   |     4/5      |
|Debugging mindset                   |     4/5      |
|Conceptual understanding (the "why")|     5/5      |

## ACTION PLAN: 3 specific actions this week to improve it without outsourcing thinking to AI.
 My lowest rated skill is SYSTEM THINKING -
 1. i will make sure i understand the basis of every language
 2. i will make sure i understand the logic behind special functions and components in a system
 3. i will make sure i understand how to utilize different tools and how to use them togther to solve a problem

