
# HIE Result Extractor

A Python tool to automatically extract key information from Hypoxic-Ischemic Encephalopathy (HIE) research papers.

## Quick Start

1. Install requirements:

2. 2. Set up OpenAI API key:
- Create a `.env` file in the project root
- Add: `OPENAI_API_KEY=your_api_key_here`

3. Usage:
- Paste the full paper text into `paper.txt`
- Run: `python main.py`
- Results will be in `study_results.csv`

## What It Does

- Extracts Bayley Scores (II and III)
- Identifies primary outcome information
- Captures additional scores (GMFCS, WPPSI-III, WISC-IV)

## Output

The `study_results.csv` file includes:
- Bayley II and III Cognitive and Language scores
- Primary outcome details
- Additional scores

Just copy-paste the paper, run the script, and get your data!
