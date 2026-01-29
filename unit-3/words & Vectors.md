# Words & Vectors

- In Natural Language Processing, words (tokens) are the basic units of text.
- Raw text is symbolic and cannot be directly processed by machine learning algorithms.
- Therefore, words must be transformed into a numerical representation.
- Each word is treated as a feature in a mathematical model.

## Need for Vector Representation

- Machine learning models operate on numerical data.
- Linguistic information must be mapped into a vector space.
- Vector representations allow:
  - Mathematical operations
  - Statistical learning
 
## Term–Document Matrix (TDM)

A term–document matrix is a table that shows how many times each word appears in each document.
- Rows → words (terms)
- Columns → documents
- Cell value → frequency of the word in that document


<img width="1093" height="542" alt="image" src="https://github.com/user-attachments/assets/f4ba58f1-a7ea-47a3-9b67-a08daeb83b20" />

- Word vector is a row vector rather than a column vector.
- Each entry in the vector represents the frequency of the word with respect to that particular dimesnion.


## Word-Word matrix

- In Term–Document Matrix, Documents are very large contexts, so we use words as context instead of documents.
- Instead of term-document matrix, we use the term-term matrix, more commonly called the word-word matrix (or the term-context matrix) in which the columns are labeled by words rather than documents.
- Rows → target words
- Columns → context words
- Cell value → number of times two words co-occur

<img width="1083" height="552" alt="image" src="https://github.com/user-attachments/assets/5be2e62f-de1d-4836-9e3b-33673f75a265" />


