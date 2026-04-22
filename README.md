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
| 6 | Scoring, TF-IDF & VSM | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch6.html) |
| 7 | Efficient Scoring & IR Components | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch7.html) |
| 8 | IR Evaluation | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch8.html) |
| 9 | Relevance Feedback & Query Expansion | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch9.html) |
| 10 | Probabilistic IR | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch10.html) |
| 11 | Text Classification, Naive Bayes & LSI | Ready · 15 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch11.html) |
| 21 | Link Analysis | Ready · 20 MC · 5 Classic | [Open →](https://rmz-oz.github.io/information_retrieval/ch21.html) |

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

**Chapter 6 — Scoring, TF-IDF & Vector Space Model**
Parametric and zone indexes, weighted zone scoring, machine-learned relevance weights, tf-idf weighting, vector space model, cosine similarity, COSINESCORE algorithm, SMART notation, sublinear tf, pivoted document length normalization.

**Chapter 7 — Efficient Scoring & IR System Components**
Champion lists, static quality scores g(d), tiered indexes, impact-ordered postings, early termination, WAND algorithm, cluster pruning (√N leaders), DAAT vs TAAT, query-independent evidence, safe vs unsafe ranking.

**Chapter 8 — IR Evaluation**
Precision, Recall, F-measure (β parameter), contingency table, MAP (Mean Average Precision), P@k, R-Precision, break-even point, ROC curve, AUC, Kappa statistic (inter-rater agreement), relevance pooling, A/B testing, static vs dynamic snippets.

**Chapter 9 — Relevance Feedback & Query Expansion**
Relevance feedback process, Rocchio algorithm (q_m = α·q₀ + β·centroid(D_r) − γ·centroid(D_nr)), pseudo relevance feedback, query drift, global analysis methods, thesaurus (manual/automatic), WordNet, MeSH, query log mining, synonymy vs polysemy.

**Chapter 10 — Probabilistic IR**
Bayes theorem, Probability Ranking Principle (PRP), Binary Independence Model (BIM), p_t/u_t definitions, RSV scoring, Laplace smoothing (p_t=(r_t+0.5)/(r+1)), RSV≈IDF connection, BM25 (k₁ and b parameters), RSJ weights.

**Chapter 11 — Text Classification, Naive Bayes & LSI**
Text classification (γ: X → C), supervised learning, Multinomial Naive Bayes, Bernoulli NB, Laplace smoothing for P(t|c), kNN classifier, Rocchio centroid classifier, LSI/SVD (A = UΣVᵀ, rank-k approximation), macro vs micro averaging, feature selection.

**Chapter 21 — Link Analysis**
Web as a graph, anchor text, link spam, PageRank (random surfer model, teleport operation, Markov chains, power iteration, topic-specific and personalized PageRank), HITS (hub & authority scores, iterative update rules, AAᵀ / AᵀA eigenvectors, base set construction).
