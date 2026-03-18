## Overview

Awesome Text Generation Evaluation provides comprehensive resources for evaluating natural language generation systems, crucial for assessing model quality beyond simple accuracy.

## Reference-Based Metrics

### BLEU
Bilingual Evaluation Understudy - measures n-gram overlap with references, commonly used in machine translation.

### ROUGE
Recall-Oriented Understudy for Gisting Evaluation - focuses on recall, used for summarization.

### METEOR
METric for Evaluation of Translation with Explicit ORdering - considers synonyms and paraphrases.

### CIDEr
Consensus-based Image Description Evaluation - designed for image captioning.

## Reference-Free Metrics

### Perplexity
Measures how well model predicts text, lower is better.

### BERTScore
Uses BERT embeddings to compute semantic similarity.

### BLEURT
BERT-based learned metric trained on human judgments.

## Learned Metrics

### Supervised
Trained on human ratings:
- BLEURT
- COMET
- Prism

### Unsupervised
- BERTScore
- MoverScore
- SMS (Sentence Mover's Similarity)

## Human Evaluation

### Criteria
- Fluency
- Coherence
- Relevance
- Informativeness
- Factual correctness

### Methodologies
- Likert scale ratings
- Pairwise comparisons
- Ranking
- Error annotation

## GPT-Based Evaluation

Using large language models as evaluators:
- GPT-4 as judge
- Chain-of-thought evaluation
- Multi-aspect assessment

## Task-Specific Metrics

### Summarization
- ROUGE variants
- Factual consistency
- Coverage

### Dialogue
- Response appropriateness
- Context relevance
- Diversity

### Story Generation
- Coherence
- Creativity
- Plot consistency

## Challenges

- Correlation with human judgment
- Evaluation of creativity
- Factual accuracy assessment
- Bias in metrics
- Multi-lingual evaluation