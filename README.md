# NLP Pipeline for Sentence Normalization, Word Embedding, Positional Encoding, and French Translation Using Hugging Face Transformers and NLTK
This code provides a complete workflow for text processing using Hugging Face Transformers and NLTK. It includes modules for sentence normalization, spelling correction, word embedding generation, positional encoding computation, and English-to-French translation.
![image](https://github.com/areeba0/English-to-French-Translation-using-NLTK-and-Hugging-Face-Transformers-MarianMTModel/assets/136759791/06723c08-1a54-496b-b557-6be93bd585dd)

# Dependencies
- Python
- Jupyter notebook
- NumPy: For numerical operations.
- NLTK: For text processing and tokenization.
- Transformers: For a translation using the MarianMT model.
- Pandas: For data handling.

# Key Features
### - Sentence Normalization
### - Spelling Correction
### - Word Embedding Generation
### - Positional Encoding Calculation
### - Translation

# Key Features Implementation
### 1) Sentence Normalization:
Tokenize the input sentence into words and convert all tokens to lowercase. 

### 2) Spelling Correction:
Use WordNet to find the correct spellings for each token. If a token matches a known word in WordNet, it is corrected to its canonical form. This helps in standardizing words before generating embeddings.

### 3) Word Embedding Generation:
Create random numerical vectors (embeddings) for each token. These embeddings represent words in a high-dimensional space, capturing semantic relationships. In practice, you might/can use pre-trained embeddings, but for demonstration purposes, random embeddings are generated.

### 4) Positional Encoding Calculation:
Compute positional encodings for each token. Positional encodings help models understand the order and position of words, which is crucial for interpreting sentence structure, especially in sequence models.

### 5) Translation:
Use the "MarianMT" model to translate the normalized sentence from English to French. The model is pre-trained on a large corpus of bilingual text, allowing it to generate accurate translations. Tokenized input is fed into the model, and the output tokens are decoded to produce the translated sentence.

### 5) Combining Results in a Pandas DataFrame:
Collect and organize all results, including normalized tokens, embeddings, positional encodings, and translations, into a DataFrame. 




