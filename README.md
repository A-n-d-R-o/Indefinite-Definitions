# Indefinite-Definitions
An investigation into the "dictionary paradox": each word needs more words to be formally defined and described, as do the words in its definition. For a given sentence, this program replaces each word in the sentence with its definition, iteratively. The aim of this program is to see what, if any, patterns emerge, such as the most relied word used in definitions.<br><br>

This is a question I've been wanting to investgate for quite some time, and this is the first real attempt at an investigation. However, due to the exponential growth of ammended sentences, the number of iterations viable for computation is low. This program only provides a superficial look into a process which I believe could reveal some pretty interesting patterns at much larger scales. <br><br>

The dictionary used is the in-memory English language dictionary, [english-dictionary 1.0.24](https://pypi.org/project/english-dictionary/). This means the results obtained from the program are very specific to this dictionary, and likely won't reflect more established dictionaries, such as the Oxford English Dictionary.
