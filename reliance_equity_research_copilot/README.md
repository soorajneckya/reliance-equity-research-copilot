# NSE Reliance Copilot — Prompt-Engineered Equity Research Assistant

## Files
- `Reliance_Equity_Research_Copilot.ipynb`: end-to-end project notebook.
- `data/synthetic_market_events_75.csv`: 75 labelled synthetic event examples.
- `data/synthetic_qa_corpus_40.csv`: 40 synthetic QA pairs.
- `data/synthetic_reliance_prices_demo.csv`: synthetic price/volume demo only.
- `data/verified_ril_fy2025_segment_facts.csv`: selected FY2025 segment facts from Reliance's official annual-report website.
- `CHAIN_OF_THOUGHT_VS_TREE_OF_THOUGHTS_MEMO.md`: comparison memo.
- `DEMO_RECORDING_SCRIPT.md`: short demonstration script.
- `requirements.txt`: dependencies.

## Important
The brief requires actual historical prices and the real annual report. This package includes selected official segment facts, but the price file is synthetic and clearly labelled. Replace it with the assignment's Kaggle dataset and add page-level annual-report evidence before publishing a rating. Do not present the demo output as a live recommendation.

Official report: https://www.ril.com/ar2024-25/index.html
Official segment overview: https://www.ril.com/ar2024-25/reliance-at-a-glance.html
Historical prices specified in brief: https://www.kaggle.com/datasets/dhruvanurag20/reliance-data
NSE annual report archive: https://www.nseindia.com/companies-listing/corporate-filings-annual-reports

Run `pip install -r requirements.txt`, open the notebook, and run top to bottom. An API key is optional; deterministic demonstrations run without one.
All outputs are educational research support only, not investment advice.
