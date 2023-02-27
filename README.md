<h1 align="center" id="title">Spelling Error Correction</h1>

*Read this in other languages: [English](README.md), [Turkish](README.tr.md).*

<p id="description">This code is an implementation of a spelling checker that checks if words from a specified dictionary file are spelled correctly. The application works by determining the most probable correction candidate for a word. It creates a Counter object that counts the occurrences of all words in the specified word dictionary file and calculates the probabilities of possible words. The correction candidates are generated using functions that include all possible modifications such as deleting adding or changing a letter in the word. Among these correction candidates those that are known to exist in the word dictionary file are selected and if there is no possible correction candidate the word itself is chosen. To determine if the corrected words are correct the program compares them to a list of correct words read from a correct word list file. Finally the program calculates an accuracy score based on the number of correctly matched words. The user can select the word dictionary file and the correct word list file and an output file is created that contains the corrected words matched to the correct words.</p>

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   SpellingCorrector with Peter Norvig Approach

<h2>🛠️ Installation Steps:</h2>

<p>1. You should just run the program from terminal with python SpellingCorrector command or open a python editor and select the SpellingCorrector.py file and run it. The program ask you 3 file name. First one is for dictionary file. Second one for misspelled word file which will use for prediction and finally third one for correct word file. Third file for calculate accuracy of the prediction.</p>

<p>2. The program ask you 3 file name. First one is for dictionary file. Second one for misspelled word file which will use for prediction and finally third one for correct word file. Third file for calculate accuracy of the prediction.</p>

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Python
*   NLP
*   Sklearn
