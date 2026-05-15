HYBRID ONTOLOGY EXTRACTION FROM RESEARCH PAPERS

## Overview
A hybrid pipeline that combines LLM-based entity extraction with 
existing domain ontologies to automate terminology extraction from 
biomedical research papers. The system reduces hallucinations by 
grounding LLM outputs against structured ontological knowledge, 
improving semantic consistency and scalability in knowledge graph 
construction.

## Motivation
Manual extraction of biomedical terminology is labor-intensive and 
inconsistent. Pure LLM approaches suffer from hallucination and 
repetition. This system combines the strengths of both: ontology 
structure for consistency, LLMs for extension & coverage.

## System Architecture
The below image denotes the system work flow.

![Hybrid Ontology Extraction System flow](https://github.com/user-attachments/assets/0f3b4af0-a8f3-48c9-84d6-cfc7eff9ed2f)

## Insights
- Use of confidence intervals in prompts for extraction of terms & relationships played a key role in finding good results.
- The hybrid approach significantly minimizes inconsistencies, improves semantic quality, and scales more effectively across extensive corpora.

## Tech Stack
Python, GPT, Ontology Protégé, RDF, NLP Libraries

## Documentation
See the `/Documentation` folder for the full project report.

