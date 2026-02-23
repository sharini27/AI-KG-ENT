# enron-email-kg-milestone1

# Enron Email KG Pipeline - Milestone 1

## Overview
Data ingestion, cleaning, transformation pipeline for Enron emails → Neo4j KG

## Files
- `Milestone1_DataIngestion.ipynb` - Full pipeline (run all cells)
- `enron_dataset_full.csv` - Raw 362k emails (549MB)
- `sample_edges.csv` - Top communication pairs
- `enron_kg_script.cypher` - Neo4j load script

## Setup
1. `pip install -r requirements.txt`
2. `jupyter notebook Milestone1_DataIngestion.ipynb`
3. Run all cells → generates CSVs/Cypher

## Outputs
- NetworkX visualization
- Cypher triples for Neo4j KG
- Top communicators analysis

**Next:** Flask API endpoints
EOF

 Create requirements.txt (your key packages)
pip freeze | grep -E "(pandas|datasets|networkx|matplotlib)" > requirements.txt
cat requirements.txt  # Should show: pandas, datasets, networkx, matplotlib# AI-KG-ENT
