# 700771851
# Rohith Varma S

Bigram Language Model Implementation

This notebook implements a Bigram Language Model using Maximum Likelihood Estimation (MLE).

Training Corpus:
1. <s> I love NLP </s>
2. <s> I love deep learning </s>
3. <s> deep learning is fun </s>

What the Program Does:
1. Computes unigram counts (word frequencies).
2. Computes bigram counts (pair frequencies).
3. Estimates bigram probabilities using MLE:
      P(w2 | w1) = Count(w1, w2) / Count(w1)
4. Implements a function to compute sentence probability
   by multiplying bigram probabilities.
5. Tests the model on:
      - <s> I love NLP </s>
      - <s> I love deep learning </s>
6. Prints which sentence is more probable.

Expected Results:
P(<s> I love NLP </s>) = 0.3333
P(<s> I love deep learning </s>) = 0.1667

The model prefers:
<s> I love NLP </s>

Reason:
It has higher probability under the trained bigram model.
