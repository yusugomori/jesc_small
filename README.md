# jesc_small

Small Japanese-English Subtitle Corpus. Sentences are extracted from [JESC: Japanese-English Subtitle Corpus](https://nlp.stanford.edu/projects/jesc/index.html), and filtered with the length of 4 to 16 words.

Both Japanese and English sentences are tokenized with [StanfordNLP](https://stanfordnlp.github.io/stanfordnlp/) (v0.2.0).

All texts are encoded in UTF-8. Sentence separator is `'\n'` and word separator is `' '`.

Additionally, all tokenized data can be downloaded from [here](https://drive.google.com/drive/folders/1ldHD6mAJK6Q7vGeu8zk7OXdHPFVcO361?usp=sharing).


## Corpus statistics

| File           | #sentences |  #words  | #vocabulary |
|:---------------|-----------:|---------:|------------:|
| train.en       |    100,000 |  809,353 |      29,682 |
| train.ja       |    100,000 |  808,157 |      46,471 |
| dev.en         |      1,000 |    8,025 |       1,827 |
| dev.ja         |      1,000 |    8,163 |       2,340 |
| test.en        |      1,000 |    8,057 |       1,805 |
| test.ja        |      1,000 |    8,084 |       2,306 |


<br>

This repo is inspired by [small_parallel_enja](https://github.com/odashi/small_parallel_enja).
