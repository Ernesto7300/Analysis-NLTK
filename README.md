# NLTK Analysis

## Purpose

This repository is an **exploratory and validation workspace** for the use of **classical Natural Language Processing (NLP) techniques**, as provided by **NLTK**, in the context of my doctoral research.

The purpose is to **systematically evaluate** what symbolic and statistical NLP methods (pre-transformer era) can and cannot do with respect to:

- linguistic structure
- shallow semantics
- semantic contrast and contradiction
- the gap between linguistic form and factual meaning

This repository deliberately treats NLTK **not as a production tool**, but as a **conceptual baseline** against which more modern embedding- and LLM-based approaches can be compared.

---

## Scope of the Analysis

The repository integrates **a broad set of NLTK functions**, applied to small, controlled examples, in order to study their semantic reach and limitations.

### 1. Baseline linguistic processing
- Sentence and word tokenization
- Part-of-speech tagging (English)
- Stopword removal
- Stemming and lemmatization

These steps establish the **linguistic surface structure** of statements.

---

### 2. Shallow syntactic analysis
- Chunking (NP, VP patterns)
- Shallow parse trees

Used to test whether syntactic structure alone is sufficient to:
- distinguish types of claims (comparative, universal, conditional)
- detect potential semantic tension

---

### 3. Lexical semantics
- WordNet synsets
- Hypernym / hyponym relations
- Lexical similarity

This level explores **word-level meaning**, not sentence-level understanding.

---

### 4. Distributional statistics
- Frequency distributions
- N-grams
- Co-occurrence patterns

These analyses serve as a reminder of what “statistics over text” can capture *before* embeddings.

---

### 5. Named Entity Recognition (NER)
- MaxEnt-based NER chunking

Included mainly as a **negative example**: many scientifically meaningful statements contain *no named entities at all*, highlighting the mismatch between typical NLP benchmarks and epistemic reasoning tasks.

---

### 6. Rule-based semantic heuristics
- Pattern-based claim classification (e.g. comparative vs universal)
- Heuristic contradiction detection
- Explicit decision trees grounded in background assumptions

These heuristics are **intentionally explicit and auditable**, contrasting with opaque learned representations.

---

## What This Repository Is *Not*

This repository explicitly **does not aim to**:

- achieve semantic understanding in a strong sense
- infer physical truth from language alone
- compete with transformer-based models
- hide reasoning inside black-box models

NLTK is used here precisely because its limits are **transparent**.

---

## Methodological Position

The guiding assumption is:

> Linguistic structure ≠ semantic truth.

NLTK provides tools to analyze **how statements are formed**, not **whether they are true**.

This makes it particularly suitable for:
- exposing implicit assumptions
- identifying underspecified claims
- separating linguistic contradiction from factual contradiction

---
## Structure

Structure may evolve as the analysis progresses.

---

## Reproducibility

- All analyses are deterministic.
- Rules and heuristics are explicitly encoded.
- No hidden training or fine-tuning is involved.
- Results are reproducible across environments.

---

## Relation to the Thesis

This repository plays the role of a **conceptual baseline** in the thesis.

It is used to:
- demonstrate what classical NLP can and cannot do
- motivate the transition to embeddings and LLMs
- support arguments about weak vs strong emergence in semantic systems
- show why purely symbolic or shallow statistical methods fail to scale to semantic grounding

---

## Status

This repository is **work in progress**.
It is intended to evolve alongside the thesis and may include negative results by design.

---

## License

This repository is intended for academic and research purposes.
Licensing details will be added once the structure stabilizes.


