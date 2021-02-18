# Augmented-Generative-Chatbot

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10q2S6bSfgQQPOEtWmsZ-pmOn1HoQWljj?usp=sharing)

This project reviews the use of augmentations techniques in NLP to optimise GPT-2 text generation performance.
Several samples have been tested, examining different augmentation procedure such as corpus replication, random word shuffling and synonym substitution using GloVe as static non-contextual linear embedding model.
The result shows whenever it is effective to augment a text corpus before GPT-2 fine-tuning processing, and how this augmentation influences the resulting output.


# Colab GPU activation:

Navigate to Edit→Notebook Settings
select GPU from the Hardware Accelerator drop-down

# Prerequisites

Prerequisites satisfied by Google Colab.

# Models evaluation settings

Most sucessful experments happen with corpus replication, 50 steps and temperature 0.6.

Please see Appendix 8 and 14 inside the Examples_outputs folder to verify the chatbot behaviour.

# Project sources

https://github.com/tensorflow/tensorflow

https://github.com/codelucas/newspaper

https://github.com/minimaxir/gpt-2-simple

https://github.com/makcedward/nlpaug

https://github.com/nltk/nltk

