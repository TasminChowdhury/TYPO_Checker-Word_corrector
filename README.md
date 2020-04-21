# TYPO_Checker-Word_corrector
this assignment deals with the problem of correcting typos in text without ucing a dictionary
1. I took a large document
2. split the document into 20% (for testing) and 80% (for training)
3. Corrupt the text at 10% and 20%
4. Designed HMM, here state refers to the correct letter that should have been typed, and output refers to the actual letter that was typed.



Results:
For 10% corrupted text:
My test data has 6767 word. But among this total corrupted word is 2586. And viterbi could correct only 498 word.
recall =  17.8137651822
precision =  86.2745098039

For 20% corrupted text:
This time I have 4087 corrupted words from 6767words, and viterbi could correct about 796 word. 
recall =  12.8309572301
precision =  82.8947368421

it is more dependent on recall as it shall correct the data that are actually needs to be corrected.
On corrupting the data with 10% the recall has improved by 4% on average.
