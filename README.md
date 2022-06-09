# Task 2 - Text Classifier

## Version 1
Write a program with php that does the following:

1. Make three word tables, in the first 20 medical words (for example: ampoules, vaccines, fever, etc.), in the second table 20 sports words (for example: ball, volleyball, referee, etc.) and in The third has 20 economic words (for example: money, inflation, coins, etc.)
2. Take a text from the user as text from the input, and separate the words of that text and compare them one by one with the words in the three tables above.
3. Count the number of words similar to the text with each of the above tables.
4. Report in the output that for example
   1. Three medical words: ampoule, vaccine, fever 
   2. Two economic words: money, inflation
   3. One sports word: ball
   4. Ten miscellaneous words: existence, show, and ...
   5. As a result, "your text class is medical"

This means that your program must specify which of the above three classes is the input text class.

## Version 2

1. Increase the number of classes to 20 classes (of course, it is necessary to design the program so that the number of classes can be increased to any number, and easily), you can name the classes: class one, class two, .. Enter the twentieth grade and put words inside each one, and if the words in each class are in the other class, it is unobstructed.
2. In the word table (database) for each class, add a column as the weight of the words in that class (for example: the word money in class number four may have one weight and in class number six, the weight of word money may be 5 and in class Another is the weight of the word money is two (set the total weight of the words to one by default, and in each class, change the weight of some words to a larger number).
3. In the report, in addition to announcing the number of similar words in the text, also write the total weight of the words (for example, write: you had 8 words from the sports category with a total weight of 34, and at the end of the report, for example: write that your text belongs to 34 To the sports category.