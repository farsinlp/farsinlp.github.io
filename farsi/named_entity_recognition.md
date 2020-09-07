# Named Entity Recognition

Named entity recognition (NER) is the task of tagging entities in text with their corresponding type.
Approaches typically use BIO notation, which differentiates the beginning (B) and the inside (I) of entities.
O is used for non-entity tokens.

Example:

| Mark | Watney | visited | Mars |
| --- | ---| --- | --- |
| B-PER | I-PER | O | B-LOC |


| Title | Description |
| ----- | ----------- |
| ArmanPersoNERCorpus [[website]](https://github.com/HaniehP/PersianNER) [[download]](https://github.com/HaniehP/PersianNER/blob/master/ArmanPersoNERCorpus.zip) | The dataset includes 250,015 tokens and 7,682 Persian sentences in total. It is available in 3 folds to be used in turn as training and test sets. Each file contains one token, along with its manually annotated named-entity tag, per line. The NER tags are in IOB format. |
