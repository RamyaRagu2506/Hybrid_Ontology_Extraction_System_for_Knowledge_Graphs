## HYBRID ONTOLOGY EXTRACTION FROM RESEARCH PAPERS

## Overview
A hybrid pipeline combining human-defined domain ontologies with 
LLM-based Named Entity Recognition (NER) and semantic relationship 
extraction, refined through similarity metrics and confidence scoring. 
The system automates terminology extraction from research papers while 
grounding LLM outputs against structured ontological knowledge - 
reducing hallucinations and improving semantic consistency at scale.

## Motivation
Manual ontology extraction is labor-intensive and subject to cognitive 
limitations - bias, error-proneness, and inconsistency at scale. 
Fully automated LLM approaches face semantic fidelity and domain 
coverage challenges. This system balances both: human expertise 
defines domain structure, LLMs handle coverage and extraction.

## System Architecture
The below image denotes the system work flow.

![Hybrid Ontology Extraction System flow](https://github.com/user-attachments/assets/0f3b4af0-a8f3-48c9-84d6-cfc7eff9ed2f)

## Evaluation
Experimental comparisons across manual, automated, and hybrid 
approaches on core NLP tasks demonstrate the hybrid method 
significantly outperforms both baselines in semantic consistency 
and scalability across extensive corpora.

## Insights
- Use of confidence intervals in prompts for extraction of terms & relationships played a key role in finding good results.
- The hybrid approach significantly minimizes inconsistencies, improves semantic quality, and scales more effectively across extensive corpora.

## Tech Stack
Python, GPT, Ontology Protégé, RDF, NLP Libraries

## Documentation
See the `/Documentation` folder for the full project report.

