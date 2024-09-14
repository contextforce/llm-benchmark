# Testing

## Question 1: Counting character frequency
GPT is trained with sub-word not characters or full word. So, it will have challenges to deal with the following questions.
```
how many 'r' in "strawberry"?
```
* gpt-4o answer: 2 (wrong)

## Question 2: Follow instructions/ restriction for writing
This challenge gpt-4o as it needs to do the first trial and cannot lookback and fix.
```
Write a six line poem about squirrels playing koalas at soccer that meets the following constraints:
- In line 2: the last word should end with i.
- In line 3: the second word begins with "u"
- In line 5, the second-to-last word is eucalytus
- In the final line, each word has 2 syllables.
```
* gpt-4o answers it wrongly.

## Question 3: Give me SVG code 
```
Give me the SVG code for a smiley. It should be simple. Reply with only the valid SVG code and nothing else.
```

## Question 4: How many sisters?
```
Sally (a girl) has 3 brothers. Each brother has 2 sisters. How many sisters does Sally have? Let's think step by step.
```
* Correct answer is 1

## Question 5: Entity Recognition
```
Extract the name of the vendor from the invoice: PURCHASE #0521 NIKE XXX3846. Reply with only the name.
```
* Nike
