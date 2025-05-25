  String Analysis Algorithm

Project Description

This algorithm, titled StringAnalysis, is designed to analyze a sentence entered by the user one character at a time. The user inputs the sentence character by character, ending with a period (.), and the algorithm calculates and displays:

1. The total number of characters in the sentence (including spaces and punctuation).


2. The number of words in the sentence (assuming words are separated by single spaces).


3. The number of vowels in the sentence (both lowercase and uppercase are considered).



How It Works

The algorithm uses three counters: length, word-count, and vowel-count.

A REPEAT loop is used to read each character until a period (.) is encountered.

For each character:

The length counter is incremented.

If the character is a space (' '), the word-count is increased.

If the character is a vowel (a, e, i, o, u, A, E, I, O, U), the vowel-count is increased.


Once the period is entered, the loop stops and the three results are printed.


Variables Used

length: stores the total number of characters.

word-count: stores the number of words (starts at 1).

vowel-count: stores the number of vowels.

vowel: a string containing all vowels for comparison.

character: used to store each character input by the user.


Important Notes

The sentence must end with a dot (.) to terminate the input.

Each character is entered one at a time, not as a full sentence.

The logic assumes that words are separated by only one space.
