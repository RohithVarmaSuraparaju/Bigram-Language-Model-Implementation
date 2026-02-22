# 700771851
# Rohith Varma S

Bigram Language Model (MLE)

Training Corpus:
1. "<s> I love NLP </s>"
2. "<s> I love deep learning </s>"
3. "<s> deep learning is fun </s>"

Program Description:
This notebook implements a Bigram Language Model using
Maximum Likelihood Estimation (MLE).

Steps Performed:
1. Compute unigram counts (word frequencies).
2. Compute bigram counts (pair frequencies).
3. Estimate bigram probabilities using:
      P(w2 | w1) = Count(w1, w2) / Count(w1)
4. Implement a function to calculate sentence probability
   by multiplying bigram probabilities.
5. Test the model on two sentences:
      - "<s> I love NLP </s>"
      - "<s> I love deep learning </s>"
6. Compare probabilities and print which sentence
   the model prefers.

Expected Results:
P("<s> I love NLP </s>") = 0.3333
P("<s> I love deep learning </s>") = 0.1667

Conclusion:
The model prefers "<s> I love NLP </s>"
because it has higher probability under the trained bigram model.
