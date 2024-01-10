AI Studio Project
Project Overview:
The primary goal of this project was to develop a machine learning model capable of efficiently classifying entities within a dataset comprising 10,000 entries, distinguishing between individuals and companies. Tailored for third-party companies with extensive client bases, the project employed strategic web scraping techniques to enhance data collection and model training. Leveraging Python and popular libraries such as TensorFlow and scikit-learn, we successfully engineered a highly accurate machine learning model. This approach yielded outstanding metrics, including precision, recall, and F1 score consistently above 90%, showcasing the model's effectiveness in classifying entities across various languages (English, Chinese, Arabic, etc.). The incorporation of web scraping facilitated the retrieval of relevant and diverse data, contributing to the robustness of the model. The practical application of this solution aids organizations in rapidly discerning whether their clients are individuals or companies, optimizing service delivery for improved client satisfaction.

Feature Engineering Highlights:
Language Detector:

Implemented a robust language detection feature to accommodate the diverse linguistic context within the dataset, enhancing the model's adaptability across multiple languages.
Word Length Feature:

Engineered a feature capturing word length, contributing to the model's ability to discern patterns based on the length of words, indicative of entity type.
Punctuation Feature:

Introduced a punctuation feature to analyze and leverage the presence of punctuation marks, aiding in the identification of distinct patterns and enhancing entity classification accuracy.
Contains Number Feature:

Integrated a feature to identify the presence of numbers within entities, providing valuable information for distinguishing between individual names and company names.
Contains Company Suffix or Prefix Feature:

Developed a specialized feature to detect the presence of common company suffixes or prefixes, contributing to the precision of the model in identifying entities as companies.
Conjunction/Stopword Feature:

Incorporated a feature focusing on conjunctions and stopwords, refining the model's understanding of language structures and further improving classification accuracy.
Contains Location Name Feature:

Engineered a feature to identify location names within entities, enhancing the model's contextual understanding and aiding in the accurate classification of entities.
Contains Common Person Name Feature:

Implemented a feature to recognize common person names, contributing to the model's ability to accurately identify entities as individuals.
These eight meticulously crafted features collectively played a pivotal role in enhancing the machine learning model's accuracy and effectiveness in classifying entities within the diverse dataset.

