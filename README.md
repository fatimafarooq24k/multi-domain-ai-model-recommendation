# Multi-Domain AI Model Recommendation Decision Support System

An AI-powered decision support system that recommends suitable AI models based on user requirements across multiple domains. It uses semantic domain routing and fuzzy-weighted multi-criteria decision-making to rank models according to user-defined priorities.

## Features

- **Multi-Domain Recommendations:** Supports Text/Code LLMs, Image Generation, Video Generation, and Speech/Voice models.
- **Semantic Domain Routing:** Analyzes the user's scenario to identify the relevant AI model category.
- **Fuzzy-Weighted Decision Making:** Converts qualitative importance levels into normalized criterion weights.
- **Multi-Criteria Model Ranking:** Scores and ranks models based on selected criteria.
- **Explainable Recommendations:** Provides explanations and highlights the criteria influencing the results.
- **Interactive Interface:** Built with Gradio for user-friendly scenario analysis and visualization.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Sentence Transformers
- Fuzzy Logic / Multi-Criteria Decision Making
- Matplotlib
- Gradio

## How It Works

1. The user describes an AI-related task or requirement.
2. The system identifies the relevant model domain using keyword matching and semantic similarity.
3. Relevant evaluation criteria are selected based on the scenario.
4. User priorities are converted into normalized weights using fuzzy membership functions.
5. Candidate models are scored and ranked.
6. The system presents recommendations, rankings, and explanations through an interactive interface.

## Supported Domains

- Text and Code Generation
- Image Generation
- Video Generation
- Speech and Voice Generation

## Project Structure

```text
.
├── Multi_Domain_AI_Model_Recommendation_DSS.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Important Note

Model evaluation scores are based on a combination of published benchmark figures and manually normalized qualitative estimates. They are intended for comparative decision support and educational purposes, not as definitive or universally applicable model rankings. Benchmark results, pricing, and model capabilities may change over time.

## Running the Project

The notebook is designed to run in a Python notebook environment such as Google Colab.

Open `Multi_Domain_AI_Model_Recommendation_DSS.ipynb`, run the cells in order, and launch the Gradio interface when prompted.

## Future Improvements

- Improve domain-routing accuracy for ambiguous user requests.
- Add automated tests for routing and recommendation scenarios.
- Strengthen benchmark source documentation and update model data regularly.
- Integrate live model pricing and benchmark information.
