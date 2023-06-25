Describe:  wordCounter()

Test:  "It should return 1 if a passage has just one word.
Code:
const text = "hello";
wordCounter(text):
Expected Output: 1

Test:  "It should return 2 if a passage has two words."
Code:
const text = "hello there";
wordCounter(text);
Expected Output: 2

Test:  "It shoudl return 0 for an empty string."
Code:  wordCounter("");
Expected Output: 0

Test:  "It should return 0 for a string that is only spaces"
Code: wordCounter("         ");
Expected Output:  0

TestJ" "It should not copunt numbers as words."
Code:  wordCounter("hi dude 14");
Expected Output: 2


Describe:  numberOfOccurencesInText()

Test: "It should return 0 occurreces of a word for an epoty string"
Code:
const test = "";
const word = "red";
numberOfOccurrencesInText(word, Text);
Expected Output:  0

Test:  "It should return 1 occurence of a word when the word and thte text are the same."
Code:
const text = "red";
const word = "red";
numberOfOccurencesInText(word, Text);
Expected Output: 1

Text:  "It should return 0 occurences of a word when the word and the text are different."
Code:
const text = 'red'
const word = 'blue'
numberOfOccurencesInText(word, text);
Expected Output: 0

Test:  "It should return the number of occurrences of a word"
Code:
const text = 'red'
const word = 'red blue red red red green'
numberOfOccurrencesInText(word, text);
Expected Output:  4

Test:  "It should return the number of occurences of a word regardless of case."


Test:  "It should not count empty strings or spaces as words".
Code:
const word = "";
const text = "red RED Red!";
numberOfOccurrencesInText(word, text);
Expected Output: 0


