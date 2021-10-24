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
| FarsiYar PersianNER <br> [[website]](https://github.com/Text-Mining/Persian-NER) [[download_part3]](https://github.com/Text-Mining/Persian-NER/blob/master/Persian-NER-part3.txt) [[download_part4]](https://github.com/Text-Mining/Persian-NER/blob/master/Persian-NER-part4.txt) [[download_part5]](https://github.com/Text-Mining/Persian-NER/blob/master/Persian-NER-part5.txt) | The dataset includes about 25,000,000 tokens and about 1,000,000 Persian sentences in total based on Persian Wikipedia Corpus. The NER tags are in IOB format. More than 1000 volunteers contributed tag improvements to this dataset via web panel or android app. They release updated tags every two weeks. |
| PEYMA<br>[[website]](http://nsurl.org/tasks/task-7-named-entity-recognition-ner-for-farsi/) [[download]](http://en.itrc.ac.ir/sites/default/files/pictures/NER.rar) | A medium size corpus with 7 classes of named entities. This corpus contains more than 700 news documents. It has been prepared by Iran Telecommunication Research Center (ITRC). |
| ParsNER-Social<br>[[website]](https://github.com/majidasgari/ParsNER/tree/master/persian/) [[paper]](http://jad.shahroodut.ac.ir/article_2023.html) | ParsNER-Social corpus constructed from the social media contents, including 10 Telegram channels in 10 different categories: sport, economics, gaming, IT news, general news, travel, art, academic, fun, and health. It shows the number of different NER tags, including the person, location, organization, and miscellaneous named entities in each category. |
