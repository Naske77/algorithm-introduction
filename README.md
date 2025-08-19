# English_Sentence Alogrithm

## Description

The English Sentence Algorithm is designed to process a given sentence and extract useful information about it. Specifically, it calculates:

- Total number of characters (excluding spaces)

- Total number of words

- Total number of vowels

This algorithm demonstrates basic string manipulation, iteration, and conditional checks in pseudo-code form.

## Pseudocode

ALGORITHM english_sentence

VAR

    sentence: STRING[N]
    sentence_len: INTEGER
    word_count: INTEGER := 1
    vowel_count: INTEGER
    vowels: STRING:="aeiou"

BEGIN

    FOR i FROM 0 TO [N - 1] STEP 1  DO
        if (vowels.includes(sentence[i])) THEN
            vowel_count := vowel_count + 1
        END_IF
        IF (sentence[i] !== " ") THEN
            sentence_len := sentence_len + 1
        ELSE
            word_count := word_count + 1
        END_IF
    END_FOR

END

## Input

- In the sentence our String was N, becaUSE the "N" was undefined where N is the length of the string..

- The Sentence length was INTEGER :=1

- The Word_Count was an INTEGER with the value of 1

- Vowel_count wass also an INTEGER ie each vowel was +1...

- While the Vowels was a STRING which identified the vowels in the sentence.

- However, the (i)index is from 0 to [N-1]. since N is undefined, we used -1 which create an array to give space for more datas to be added.

### STEP 1:

- If there are Vowels in the sentence, then Vowel_count will be +1 eg: "Hello World" Vowel_count would be(e, o, o) = 3

### END_IF

- If the sentence has a space, "do not include" THEN countinue sentence_len from +1.eg: Sentence_len excluding spaces "Hello World" = 10

### ELSE

- word_count takes each word as 1 without the space eg:"Hello, World" so word_count = 2
