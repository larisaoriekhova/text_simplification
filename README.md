# text_simplification

Text simplification project.

## Dataset ##
Texts from newsela.com Geography library were splitted into pairs complex sentence - one or more simple sentences.
Also part of dataset uset in Split-and-rephrase project was used (Monument, City, Airport and Building categories).

    @article{sharma2017nlgeval,
      author  = {Sharma, Shikhar and El Asri, Layla and Schulz, Hannes and Zumer, Jeremie},
      title   = {Relevance of Unsupervised Metrics in Task-Oriented Dialogue for Evaluating Natural Language Generation},
      journal = {CoRR},
      volume  = {abs/1706.09799},
      year    = {2017},
      url     = {http://arxiv.org/abs/1706.09799}
    }

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