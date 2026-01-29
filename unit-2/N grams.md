# N grams

- An N gram is a sequence of n items from a given sample of text or speech.
- The items can be phonemes, syllables, letters, words or base pairs according to the application.
-  The n-grams are collected from a text or speech corpus.

```
p(A|B) = P(B|A).P(A)
        ____________
            P(B)
```

### Probability of words in a sentence

- To calcualte probability of a sentence, we need to calculate probability of a word, given the sequence of words preceding it.
- We use chain rule to calculate sentence probability.

<img width="1132" height="73" alt="image" src="https://github.com/user-attachments/assets/c54a898f-c7a1-461d-b2d2-5ea3893d0258" />

**Unigram model** : No history used, the model considers the word with highest probability.

**Bigram model** : one word history

**Trigram model** : two word history

**Four-gram model** : three word history

**Five-gram model** : four word history

