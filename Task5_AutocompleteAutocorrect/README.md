# Level 2, Task 5 - Autocomplete and Autocorrect Data Analytics

**Goal:** Build and compare simple autocomplete and autocorrect systems on a real text corpus, and measure how well they work.

**Tools:** Python, pandas, NLTK, pyspellchecker, collections, matplotlib, seaborn, Jupyter Notebook

**Dataset:** Ten books from Project Gutenberg, loaded through NLTK's built-in `gutenberg` corpus (no separate download needed).

## Approach
1. Loaded and preprocessed the corpus (lowercasing, punctuation removal, stopword removal for the frequency chart)
2. Split each book 90% train / 10% test
3. Autocomplete: bigram and trigram next-word models with backoff, plus word completion from typed letters
4. Autocorrect: `pyspellchecker` vs a custom corrector built on edit distance and corpus word frequencies
5. Measured precision, recall and accuracy, and drew confusion matrices (correct/incorrect before vs. after)

## Results
| Task | Approach | Result |
|---|---|---|
| Autocomplete | Bigram | _Recall@3 value_ |
| Autocomplete | Trigram + backoff | _Recall@3 value_ |
| Autocorrect | pyspellchecker | _Precision / Recall value_ |
| Autocorrect | Custom corpus-based | _Precision / Recall value_ |

## Key findings
- _Finding 1_
- _Finding 2_
- _Finding 3_

## How to run
1. `pip install pandas numpy matplotlib seaborn nltk pyspellchecker jupyter`
2. Open `autocomplete_autocorrect.ipynb` and run all cells (the NLTK corpus downloads automatically).
