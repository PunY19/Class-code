# Class code
Code created in Basic Programming for NLP and Computational Linguistics class as homework.

### Grammatical error correction
Try using GPT2 to correct the sentence by comparing the sentence score after changing the determiner, verb forms, and preposition with the original one. If the edited sentence scored more than the original sentence then it's assumed that it's a correct form and will be corrected. 

### Named entity recognition. 
Text classification using Conditional Random Fields (CRF) and 10 designed features to detect Thai-named entities.

### LST20 -WangchanBERTa vs. MaxEnt vs. CNN
Compare which model does better in predicting Thai news categories (15 labels) from the LST20 corpus created by NESTEC. The result is shown below.

|Model      |   Accuracy    |   Precision   |   Recall    | F1          |
|-----------|---------------|---------------|-------------|-------------|
|MaxEnt     | 0.79          | 0.63          | 0.48        | 0.51        |
|CNN        | 0.80          | **0.73**      | 0.54        | 0.57        |
|WangchanBERTa| **0.82**    | 0.72          | **0.60**    | **0.63**    |

### Back-translation-and-the-Effects-on-Sentence-Similarity
see https://github.com/ILLUMINA666/Back-translation-and-the-Effects-on-Sentence-Similarity
