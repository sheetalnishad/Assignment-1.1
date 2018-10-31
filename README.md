1. Say True or False for the below statements:
• Prescriptive Analytics used to predict the future outcomes?
Ans. False. prescriptive analytics is about recommendations and what action is required.

• Base R packages installed automatically?
Ans. True. Base R packages comes with R Studio.

2. What is Recycling of elements in a vector?
Ans. R automatically recycles, or repeats, elements of the shorter Vector
When applying an operation to two vectors that requires them to be the same length, R automatically
recycles,
or repeats, elements of the shorter one, until it is long enough to match the longer Vector.

3. Give an example of recycling of elements.
Ans.Ex-1 m&lt;-c(1,2,4)
n&lt;-c(6,0,9,10,13)
Here vector m has only 3 elements and vector n has 5 elements.
when we add the two it will give following results.
[1] 7 2 13 11 15
but it will give us warning message saying
longer object length is not a multiple of shorter object length
