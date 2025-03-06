# NLP-Final-Project

This repository contains code and data for analyzing potential biases in AI resume ranking systems. The project examines how models like GPT-3.5-turbo and GPT-4o-mini rank resumes across different job positions and analyzes patterns in these rankings.

## Project Structure

```
├── data/
│   ├── input/             # Original data files
│   ├── intermediary/      # Processed data from models
│   └── output/            # Final analysis results
├── notebooks/             # Jupyter notebooks for analysis
├── requirements.txt       # Python dependencies
└── README.md              # This file
```

## Setup

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Create a `.env` file in the notebooks directory with your API keys:
   ```
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

The main notebooks are:
- `analyze_input_data.ipynb`: Exploratory analysis of the input resumes
- `rank_resumes.ipynb`: Perform the ranking using AI models
- analysis_ranking_bias.ipynb: Analyze results for demographic biases
