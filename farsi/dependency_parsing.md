# Dependency parsing

Dependency parsing is the task of extracting a dependency parse of a sentence that represents its grammatical
structure and defines the relationships between "head" words and words, which modify those heads.

Example:

```
     root
      |
      | +-------dobj---------+
      | |                    |
nsubj | |   +------det-----+ | +-----nmod------+
+--+  | |   |              | | |               |
|  |  | |   |      +-nmod-+| | |      +-case-+ |
+  |  + |   +      +      || + |      +      | |
I  prefer  the  morning   flight  through  Denver
```

Relations among the words are illustrated above the sentence with directed, labeled
arcs from heads to dependents (+ indicates the dependent).

| Title | Description |
| ----- | ----------- |
| Persian CoNLL 2017<br>[[website]](https://lindat.mff.cuni.cz/repository/xmlui/handle/11234/1-1989) [[download]](https://lindat.mff.cuni.cz/repository/xmlui/bitstream/handle/11234/1-1989/Persian-annotated-conll17.tar?sequence=33&isAllowed=y) | Automatic segmentation, tokenization and morphological and syntactic annotations of raw texts, provided for the CoNLL 2017 Shared Task in UD Parsing. |
| Uppsala Persian Dependency Treebank: UPDT<br>[[website]](https://sites.google.com/site/mojganserajicom/home/updt) [[download]](https://sites.google.com/site/mojganserajicom/home/updt/updt-1-3/UPDT.1.3.tar?attredirects=0&d=1) | UPDT is a dependency-based syntactically annotated corpus. The treebank consists of 6000 sentences (151,671 tokens) of written text in CoNLL-format and is developed through a bootstrapping procedure involving the open source data-driven dependency parser MaltParser, and manual validation of the annotation. |
| Persian Syntactic Dependency Treebank<br>[[website]](https://www.peykaregan.ir/dataset/%D9%BE%DB%8C%DA%A9%D8%B1%D9%87-%D9%88%D8%A7%D8%A8%D8%B3%D8%AA%DA%AF%DB%8C-%D9%86%D8%AD%D9%88%DB%8C-%D8%B2%D8%A8%D8%A7%D9%86-%D9%81%D8%A7%D8%B1%D8%B3%DB%8C) | This treebank has 29,982 annotated sentences including samples from almost all verbs of the Persian valency lexicon. |
| The Persian Universal Dependency Treebank (PerUDT)<br>[[website]](https://github.com/UniversalDependencies/UD_Persian-PerDT/tree/dev) | PerUDT is the result of automatic coversion of Persian Dependency Treebank (PerDT) with extensive manual corrections. The original Treebank consists of 29K sentences sampled from contemporary Persian text in different genres including: news, academic papers, magazine articles and fictions. |
