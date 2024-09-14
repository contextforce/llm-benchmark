# SEO Testing

## Question: Counting character or words
GPT is trained with sub-word not characters or full word. So, it will have challenges to deal with the following questions.
```
how many 'r' in "strawberry"?
```
* gpt-4o answer: 2 (wrong)

## Question: Follow instructions/ restriction for writing
This challenge gpt-4o as it needs to do the first trial and cannot lookback and fix.
```
Write a six line poem about squirrels playing koalas at soccer that meets the following constraints:
- In line 2: the last word should end with i.
- In line 3: the second word begins with "u"
- In line 5, the second-to-last word is eucalytus
- In the final line, each word has 2 syllables.
```
* gpt-4o answers it wrongly.

<br>
<br>

# Coding

## Question: Give me SVG code 
```
Give me the SVG code for a smiley. It should be simple. Reply with only the valid SVG code and nothing else.
```
<br>
<br>

# Logical Thinking

## Question: How many sisters?
```
Sally (a girl) has 3 brothers. Each brother has 2 sisters. How many sisters does Sally have? Let's think step by step.
```
* Correct answer is 1

## Question: How many killers?
```
There are three killers in a room. Someone enters the room and kills one of them. Nobody leaves the room. How many killers are left in the room? Explain your reasoning step by step.
```
* 3 killers alive but 1 was killed and dead
  
## Question: Marble 
```
A marble is put in a glass cup. The glass is then turned upside down and put on a table. Then the glass is picked up and put in a microwave. Where's the marble? Explain your reasoning step by step.
```

<br>
<br>

# Semantic Understanding

## Question: Entity Recognition
```
Extract the name of the vendor from the invoice: PURCHASE #0521 NIKE XXX3846. Reply with only the name.
```
* Nike
