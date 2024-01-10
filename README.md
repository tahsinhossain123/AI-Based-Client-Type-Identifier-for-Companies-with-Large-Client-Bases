# AI Studio Project

## Overview

This project focuses on developing a machine learning model to classify entities within a dataset of 10,000 entries, distinguishing between individuals and companies. Tailored for third-party companies with extensive client bases, the project strategically employs web scraping techniques to enhance data collection and model training. Leveraging Python and popular libraries such as TensorFlow and scikit-learn, a highly accurate machine learning model is engineered.

### Key Achievements

- Achieved outstanding metrics (precision, recall, and F1 score consistently above 90%) for entity classification across diverse languages (English, Chinese, Arabic, etc.).
- The incorporation of web scraping enriches the dataset, contributing to the model's robustness.
- Practical application aids organizations in swiftly discerning client types, optimizing service delivery for improved client satisfaction.

## Feature Engineering Highlights

```python
# Feature Engineering
features = [
    "Language Detector",
    "Word Length Feature",
    "Punctuation Feature",
    "Contains Number Feature",
    "Contains Company Suffix or Prefix Feature",
    "Conjunction/Stopword Feature",
    "Contains Location Name Feature",
    "Contains Common Person Name Feature"
]

# Highlighting the significance of each feature
for feature in features:
    print(f"{feature}:")
    print(" - " + "Enhances adaptability across multiple languages." if "Language" in feature else "Captures word length, aiding in discerning patterns indicative of entity type." if "Word Length" in feature else "Analyzes and leverages punctuation marks, enhancing entity classification accuracy." if "Punctuation" in feature else "Identifies the presence of numbers within entities, aiding in distinguishing between individual and company names." if "Contains Number" in feature else "Detects common company suffixes or prefixes, contributing to precision in identifying entities as companies." if "Company Suffix" in feature else "Focuses on conjunctions and stopwords, refining the model's understanding of language structures." if "Conjunction" in feature else "Identifies location names within entities, enhancing contextual understanding." if "Location Name" in feature else "Recognizes common person names, contributing to accurate identification of entities as individuals.")
    print()

