# Filipino Word Level Normalization in C++
A C++ program that normalize Filipino words using Damerau–Levenshtein distance algorithm, double metaphone algorithm (modified version for Filipino language) and a language model.

#### Confusion set:
Using Damerau–Levenshtein distance algorithm, a list of candidate words will be produced according to the threshold setting (default = 1) and will be added to confusion set.<br>

double metaphone algorithm will also be used to generate candidate words. All words in the dictionary will be processed by the algorithm to get the phonetic code of each word. The phonetic code of the word to be normalized and the words in the dictionary will be compared using the Damerau–Levenshtein distance algorithm. The result will be added to confusion set according to the threshold setting.

#### Selecting Best Word
A Recurrent Neural Network language model will be used to select the best word from the confusion set.

## Screenshot 
![alt text](/interface.png)

## Modules Used:
	wxWidget 3.1.2 
	tensorflow C++ API 

## Reference:
	working...
