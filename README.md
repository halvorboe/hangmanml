# Hangman ML 

A statistical hangman bot using NLP.

## How does it work?

The bot downloads a large dataset of text and analyzes it. Using that text it can acuratly find patterns in text
giving better predictions for hangman.

The general idea is that you solve the question.

Given what I know about the word, what is the letter that appears in the most words that fit the pattern.

So for example, given three words.

abc
cbc
aed

the bot would start guessing either c for the last letter or a for the first letter, because that is the most likely to be correct.

66% chance.

let's say the word was bcc and it guessed c for the last letter. 

## Implementation details 

Using cloudflare workers.

/upload
/predict
/record 
/interface