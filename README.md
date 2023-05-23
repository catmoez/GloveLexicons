# GloveLexicons
Emotion-related dictionaries 'trained' based on Stanford GloVe word embeddings. (In the manner of Rheault et al. 2016, but without involving another text corpus).



Created using an approach similar to Rheault et al. 2016 (PLOS)'s seedwords and word embedding vector-based identification of new word lists at two 'poles' of meaning.

Much of the R code is sourced from this project as well. (https://github.com/lrheault/emotion).

The element I have changed is using the default Stanford GloVe word embeddings directly (pretrained; generic) rather than first finetuning the word vectors on the corpus. (https://github.com/stanfordnlp/GloVe).

Please feel free to use, with credit.
