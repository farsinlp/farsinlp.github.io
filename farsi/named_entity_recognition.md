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
| ArmanPersoNERCorpus <br> [[website]](https://github.com/HaniehP/PersianNER) [[download]](https://github.com/HaniehP/PersianNER/blob/master/ArmanPersoNERCorpus.zip) | The dataset includes 250,015 tokens and 7,682 Persian sentences in total. It is available in 3 folds to be used in turn as training and test sets. Each file contains one token, along with its manually annotated named-entity tag, per line. The NER tags are in IOB format. |
| FarsiYar PersianNER <br> [[website]](https://github.com/Text-Mining/Persian-NER) [[download_part3]](https://github.com/Text-Mining/Persian-NER/blob/master/Persian-NER-part3.txt) [[download_part4]](https://github.com/Text-Mining/Persian-NER/blob/master/Persian-NER-part4.txt) [[download_part5]](https://github.com/Text-Mining/Persian-NER/blob/master/Persian-NER-part5.txt) | The dataset includes about 25,000,000 tokens and about 1,000,000 Persian sentences in total based on Persian Wikipedia Corpus. The NER tags are in IOB format. More than 1000 volunteers contributed tag improvements to this dataset via web panel or android app. They release updated tags every two weeks.
