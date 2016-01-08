# Start Questions
1. My mother and I talked last night
 It said : Tell me more about your family.
2. I said no!
 It said : Why so negative?
3. The weather is nice
 It said : You don't say.
4. Do you know my brother?
 It said : Why so negative?

## Exercises
Keyword : Flaming hot cheetos
Response : Those are the best things in the entire world
Keyword : idiot
response : Well I'm glad you can tell the truth
Keyword : meep
response : MEEEEEEEEEEEP


When more than one keyword appears in a string, the program will put the response to the first key word in the statement and if the statement contains no at all, regardless of any other keywords it will reply with "Why so negative".
In order to prioritize responses in the reply method all you would have to do is rearrange the if and else is statements because it checks through the if and else if statements linearly. If you want a keyword or phrase to be checked first simply put it ahead of another else if statement.

 ### Question
 The problem with a keyword included in another word is that the response will be the response to the keyword in the code of Magpie which in the case of "I know all the state capitals" makes no sense to reply with "Why so negative". Magpie will check through the string and see if no is in the string and if no is embedded in a word like know it will think that no is in the string and reply accordingly. With "I like vegetables smothered in cheese" it will scan through the string and find out that mother is in smothered and reply with the response to mother even though the entire word is not smothered. 