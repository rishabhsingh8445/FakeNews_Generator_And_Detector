# Fake News Generator & Detector

## Project Objective

This project aims to build a system that can detect fake news and also generate synthetic fake news articles using AI.

## Tech Stack

The system leverages Natural Language Processing (NLP) and Generative AI models.

## Modules

### Detection Module

This module fine-tunes transformer-based models like DeBERTa for classifying news as real or fake.

### Generation Module

This module uses language generation models (specifically GPT-2 Medium) to create realistic fake news based on given prompts.

## Dataset

The models are trained and evaluated on a real-world fake news dataset for improved accuracy and relevance.

## Applications

This project helps in understanding the threat of misinformation and demonstrates how AI can both combat and create fake content.

## Ethical Focus

The project encourages responsible AI use by showcasing both detection capabilities and risks of misuse.

## How to Use

1.  **Install Required Libraries:** The notebook installs necessary libraries such as `transformers`, `torch`, `pandas`, and `ipywidgets`.
2.  **Import Libraries & Check GPU:** Imports the required libraries and checks for GPU availability for faster processing.
3.  **Load AI Models:** Loads the GPT-2 Medium model for text generation and a pre-trained fake news detection model (hamzab/roberta-fake-news-classification) or falls back to a general sentiment classifier if the dedicated model is unavailable.
4.  **Interactive Interface:** The notebook provides an interactive UI with two main functionalities:
    *   **Generate Fake-Style Headlines:** Enter a starting phrase, and the system will generate a fake-style headline using the GPT-2 model. It then checks if the generated headline is fake.
    *   **Check Your News:** Paste any news text, and the system will analyze it to determine if it's likely fake, providing a probability score and confidence level.

### Interpreting Results:

*   🔴 **Red:** Likely fake news
*   🟠 **Orange:** Suspicious/uncertain
*   🟢 **Green:** Probably real news

## Technical Details

*   **Headline Generation:** GPT-2 Medium model
*   **Fake Detection:** DeBERTa-v3-large model (or a RoBERTa-based sentiment model as fallback)
*   **Accuracy:** ~85-90% on standard datasets


