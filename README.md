# CSE 422 — Information Retrieval

Acibadem University · Manning et al. — Introduction to Information Retrieval

Interactive course notes and quiz system. All content is in English.

**Live Site:** [rmz-oz.github.io/information_retrieval](https://rmz-oz.github.io/information_retrieval/)

| Chapter | Topic | Status | Link |
|---------|-------|--------|------|
| 1 | Boolean Retrieval | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch1.html) |
| 2 | The Term Vocabulary | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch2.html) |
| 3 | Dictionaries & Tolerant Retrieval | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch3.html) |
| 4 | Index Construction | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch4.html) |
| 5 | Index Compression | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch5.html) |
| 6 | Scoring, TF-IDF & VSM | Coming Soon | — |

## Topics Covered

**Chapter 1 — Boolean Retrieval**
Inverted index construction, INTERSECT algorithm, query optimization, Boolean vs. ranked retrieval.

**Chapter 2 — The Term Vocabulary**
Tokenization, stop words, normalization, stemming (Porter), lemmatization, skip pointers, positional index, phrase queries.

**Chapter 3 — Dictionaries and Tolerant Retrieval**
Hashing vs. B-trees, wildcard queries (trailing/leading/general), permuterm index, k-gram index, edit distance (Levenshtein), Jaccard coefficient, context-sensitive spelling correction, Soundex.

**Chapter 4 — Index Construction**
Hardware basics (seek time, transfer rate, RCV1 stats), BSBI (Blocked Sort-Based Indexing, O(T log T)), SPIMI (Single-Pass In-Memory Indexing, O(T)), MapReduce distributed indexing, dynamic indexing, logarithmic merging, security and access control.

**Chapter 5 — Index Compression**
Heaps' law (vocabulary growth), Zipf's law (term frequency distribution), lossless vs. lossy compression, dictionary compression (fixed-width, string, blocked storage, front coding), gap encoding, VB codes, γ codes, δ codes.
