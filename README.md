# 700771851
# Rohith Varma S

Bigram Language Model (MLE)

Training Corpus:
1. "&lt;s&gt; I love NLP &lt;/s&gt;"
2. "&lt;s&gt; I love deep learning &lt;/s&gt;"
3. "&lt;s&gt; deep learning is fun &lt;/s&gt;"

Program Description:
This notebook implements a Bigram Language Model using
Maximum Likelihood Estimation (MLE).

Steps Performed:
1. Compute unigram counts (word frequencies).
2. Compute bigram counts (pair frequencies).
3. Estimate bigram probabilities using:
      P(w2 | w1) = Count(w1, w2) / Count(w1)
4. Implement a function to calculate sentence probability.
5. Test the model on:
      - "&lt;s&gt; I love NLP &lt;/s&gt;"
      - "&lt;s&gt; I love deep learning &lt;/s&gt;"
6. Compare probabilities and print which sentence is preferred.

Expected Results:
P("&lt;s&gt; I love NLP &lt;/s&gt;") = 0.3333
P("&lt;s&gt; I love deep learning &lt;/s&gt;") = 0.1667

Conclusion:
The model prefers "&lt;s&gt; I love NLP &lt;/s&gt;"
because it has higher probability.

