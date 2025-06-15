## Text Classification with NLP & PoS Tagging

### 1. Goal  
To convert English sentences into structured "emoji symphonies" by classifying each word based on its PoS (part of speech) and mapping it to a corresponding musical emoji.

### 2. Dataset  
Source: Provided [big.txt](https://github.com/yehyifan/Text_Classification_with_NLP_and_PoS_Tagging/blob/main/big.txt) corpus of English sentences

- Content: A large plain-text file containing various English sentences  
- Output: A list of tuples mapping each sentence to a sequence of emojis  
- Emoji Mapping Rules:  
  - Stopwords → 🎵  
  - Nouns (PoS tag starts with `N`) → 🎸  
  - Verbs (PoS tag starts with `V`) → 🎹  
  - Adjectives (PoS tag starts with `J`) → 🎷  
  - Others → 🎤

### 3. Tools and Libraries  
- Libraries: `nltk`, `pandas`, `re`, `wordnet`, `tqdm`  
- NLP Techniques:  
  - Tokenization (word and sentence)  
  - Stopword removal  
  - PoS tagging  
  - WordNet-based lexical analysis

### 4. Procedure and Results  
Please view the full [notebook](https://github.com/yehyifan/Text_Classification_with_NLP_and_PoS_Tagging/blob/main/Text_Classification_with_NLP_and_PoS_Tagging_.ipynb) for implementation and examples.
