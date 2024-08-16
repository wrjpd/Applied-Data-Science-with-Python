# Spelling Correction
- A common way to check for mis-spelt words and correct them is to find valid words that share similar spelling
- Requires:
    -  a dictionary of valid words (nltk.corpus)
    -  some way to measure spelling similarity
 

## Levenshtein distance
- Edit distance : Number of changes that need to be made to strin A to get to string B
- it measures:
    - Insertions
    - Deletions
    - Substitutions
 
## N-grams
- Character sequences in a word of size n
- Can also be used for word sequences
- How can n-grams help in spell-checking?
    - If two words have similar spelling, they share many n-grams
 

#### Jaccard similarity
- Used to measure similarity of set
- **Jaccard index / coefficiente of similarity of two sets A and B** = interaction of A and B / union of A and B