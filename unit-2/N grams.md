# N grams

- N gram is a continuous sequence of n words extracted from a given text or sentence.
- Here **N** represents the number of consecutive items considered together.
- The items can be phonemes, syllables, letters, words or base pairs according to the application.
- N grams are widely used in NLP, to model langugae and predict word sequences. 
- The n-grams are collected from a text or speech corpus.


### Probability of words in a sentence

- To calcualte probability of a sentence, we need to calculate probability of a word, given the sequence of words preceding it.
- We use chain rule to calculate sentence probability.

<img width="1132" height="73" alt="image" src="https://github.com/user-attachments/assets/c54a898f-c7a1-461d-b2d2-5ea3893d0258" />

**Unigram model** : No history used, the model considers the word with highest probability.

**Bigram model** : one word history

**Trigram model** : two word history

**Four-gram model** : three word history

**Five-gram model** : four word history

## Unigram Model

<img width="1399" height="355" alt="image" src="https://github.com/user-attachments/assets/4a227151-b148-4adc-8c1c-5fd61f7b6ecd" />

<img width="1361" height="605" alt="image" src="https://github.com/user-attachments/assets/bcc5069c-d25e-4af4-b93a-26b6cb6df3b7" />

<img width="1324" height="128" alt="image" src="https://github.com/user-attachments/assets/c3ea2fe0-b0a7-43f7-85ac-67aa1b9eaa4b" />

## Bigram Model

<img width="1360" height="320" alt="image" src="https://github.com/user-attachments/assets/bcdf5951-b292-409f-90b9-c5b7b89125d9" />

<img width="1378" height="519" alt="image" src="https://github.com/user-attachments/assets/5be738d0-8e85-4d9d-aadb-e9fc93108286" />

<img width="1364" height="133" alt="image" src="https://github.com/user-attachments/assets/ae80926e-cafe-470b-a3cf-36c9fd8e8a8f" />

## Trigram Model

<img width="1429" height="306" alt="image" src="https://github.com/user-attachments/assets/d1c68d89-5b56-41a7-befc-fcb87aca29d4" />

<img width="1353" height="439" alt="image" src="https://github.com/user-attachments/assets/17f9e3b8-f25c-4734-bcb4-098a84a36450" />

<img width="1378" height="123" alt="image" src="https://github.com/user-attachments/assets/89f4f9d0-0053-4fa2-94ca-ffea1e9100fe" />
