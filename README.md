# text_simplification
Text simplification project.

## Dataset ##
Texts from newsela.com Geography library were splitted into pairs complex sentence - one or more simple sentences.
Also part of dataset uset in Split-and-rephrase project (https://arxiv.org/abs/1707.06971, https://github.com/shashiongithub/Split-and-Rephrase) was used (Monument, City, Airport and Building categories).

## Requirements ##
To run baseline and see results:
 - python 2.7
 - spacy 2.0+ with english model downloaded

To run metrics:
 - textstat (https://pypi.org/project/textstat/)
 - nlg-eval (https://github.com/Maluuba/nlg-eval) 

## Run ##
At the moment baseline of the project is ready.
You can run notebooks/baseline.ipynb to test it.