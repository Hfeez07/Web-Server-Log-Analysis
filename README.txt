# Web Server Log Analysis

This project analyzes HTTP log data from the Calgary dataset or a provided sample.
It uses Python and Pandas to perform tasks such as:

- Counting log entries, unique hosts, and error codes
- Finding top requested and failed filenames
- Aggregating daily bandwidth usage
- Visualizing hourly request patterns

## Features

- Handles real `.gz` log file or falls back to sample data
- Parses Apache log format
- Answers 10 common log analysis questions
- Includes inline explanations and assertions
- Generates plots with Seaborn

## Usage

Run the notebook in Jupyter:

```bash
jupyter notebook analysis_exported.ipynb
```

Or run the Python script:

```bash
python analysis_exported.py
```

Make sure you have the required libraries:

```bash
pip install pandas matplotlib seaborn
```

## Visualization

The output includes:
- Hourly request volume
- Top filenames and error breakdowns

---
This is a professional template suitable for interviews or real-world log analysis tasks.
