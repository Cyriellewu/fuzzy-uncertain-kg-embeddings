# FKGE-OSC: Fuzzy-Enhanced Uncertain Knowledge Graph Embeddings via Oscillatory Layer Integration

You Wu (first author), Junwei Su, Sirui Zhang, Raymond Shu Tak Lee
Data Science Program, BNU-HKBU United International College

## Overview

Real-world knowledge graphs carry uncertain facts, each with a confidence score. **FKGE-OSC** builds on UKGE (Chen et al., 2019) and improves how those confidence scores are modeled:

- **Fuzzy logic** to represent graded, uncertain membership of relational facts
- **Lee oscillator layer**, a dynamic layer that captures temporal variation and structural dependencies when estimating confidence
- **Probabilistic Soft Logic (PSL)** to infer confidence scores for missing facts

On standard uncertain-KG benchmarks, FKGE-OSC beats existing uncertain KGE models on confidence prediction, relational fact ranking and classification, with lower MSE and MAE, and it stays interpretable.

## Contents

- `Fuzzy-Enhanced Uncertain Knowledge Graph Embeddings via Oscillatory Layer Integration.pdf`: full paper

**Keywords:** knowledge graph embeddings, uncertainty modeling, fuzzy logic, oscillator models, probabilistic soft logic
