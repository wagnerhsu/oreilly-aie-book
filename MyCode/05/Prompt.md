## Adopt a persona
```powershell
Give the essay below a score from 1 to 5, with 1 being very bad and 5 being very good. Be concise. Output only the score and nothing else.

"I like chickens. Chickens are fluffy and they give tasty eggs."

# Add a persona
You're a first-grade teacher. Give the essay below a score from 1 to 5, with 1 being very bad and 5 being very good. Be concise. Output only the score and nothing else.

"I like chickens. Chickens are fluffy and they give tasty eggs."
```

## Provider examples
```powershell
Will Santa bring me presents on Christmas?

# With example
Q: Is the tooth fairy real?
A: Of course! Put your tooth under your pillow tonight. The tooth fairy might visit and leave you something.
Q: Will Santa bring me presents on Christmas?
A:

# 
Label the following item as edible or inedible.
Input: chickpea
Output: edible
Input: box
Output: inedible
Input: pizza
Output:

#
Label the following item as edible or inedible.

chickpea --> edible
box --> inedible
pizza -->
```
## Output format
```powershell
Label the following item as edible or inedible.
pineapple pizza --> edible
cardboard --> inedible
chicken
#
Label the following item as edible or inedible.

pineapple pizza --> edible
cardboard --> inedible
chicken -->

```
## Give the models to think
```powershell
Which animal is faster: cats or dogs? Think step by step before arriving at an answer.
#
Which animal is faster: cats or dogs? Explain your rationale before giving an answer.
#
Which animal is faster: cats or dogs? Follow these steps to find an answer:
1. Determine the speed of the fastest dog breed.
2. Determine the speed of the fastest cat breed.
3. Determine which one is faster.
```

## Let LLM make prompt
```powershell
Help me write a concise prompt for an application that grades college essays between 1 and 5
```
