# spaCy-Resume-Analyser

This project provides a comprehensive toolkit for analyzing resume data, extracting insights using Natural Language Processing (NLP), and visualizing the distribution of job categories, skills, and other relevant information. It leverages powerful libraries such as spaCy for entity recognition and Gensim for topic modeling, along with visualization libraries like pyLDAvis, WordCloud, Plotly, and Matplotlib.

## Features

- **Resume Entity Recognition**: Custom entity recognition using spaCy's `EntityRuler` for identifying specific entities like skills and job categories.
- **Topic Modeling**: Utilizes Gensim's LDA model to uncover prevalent topics within resumes.
- **Data Visualization**: Offers a variety of visualization methods to display the analysis results, such as job category distribution, skill word clouds, and topic distributions using libraries like pyLDAvis and Plotly.
- **Data Cleaning and Preprocessing**: Implements text cleaning and preprocessing techniques to prepare resume data for analysis.

## Installation

Before you can run the project, you need to install the required libraries. You can install them using pip:

```bash
pip install spacy gensim pyLDAvis pandas numpy jsonlines matplotlib plotly wordcloud nltk
```

Additionally, you'll need to download the spaCy English language model:

```bash
python -m spacy download en_core_web_lg
```

## Usage

1. **Setting Up Your Environment**:
   - Ensure all dependencies are installed.
   - Download the necessary spaCy model.

2. **Loading Your Data**:
   - this project utilizes a custom dataset, jz_skill_patterns.jsonl
     
3. **Running the Analysis**:
   - Execute the script to perform entity recognition, topic modeling, and data visualization.
   - Customize the analysis and visualization by modifying the script according to your dataset and requirements.

4. **Visualization**:
   - Use the provided visualization code snippets to generate graphs and word clouds, showcasing the analysis results.

5. **Custom Entity Recognition**:
   - Modify the JSONL file with your custom patterns for skill extraction and run the entity ruler component to enhance entity recognition.
