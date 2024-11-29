# Analysis of TV Show Transcripts: Friends, HIMYM, and TBBT

## 📚 Project Overview
This project is a collaborative effort focusing on analyzing transcripts from the TV shows **Friends**, **How I Met Your Mother (HIMYM)**, and **The Big Bang Theory (TBBT)**. The goal is to explore the content structure, character interactions, and recurring phrases, as well as conduct sentiment and emotional analyses. 

The workflow combines:
1. **Python-based text analysis** for cleaning, processing, and visualizing data.
2. **Interactive Power BI dashboards** for exploring trends and patterns.

---

## 🚀 Workflow
### 1. Data Cleaning (`1_FINAL_himym_friends_tbbt_clean.ipynb`)
- Import and preprocess datasets for Friends, HIMYM, and TBBT.
- Clean missing values, standardize columns, and format dates for uniformity.
- Prepare data for further analysis by dropping unnecessary columns.

### 2. Text Processing (`2_FINAL_himym_friends_tbbt_process.ipynb`)
- Perform tokenization, lemmatization, and removal of stop words.
- Generate n-grams (unigrams, bigrams, trigrams) for further analysis.
- Map lemmatized tokens to emotions using the NRC Emotion Lexicon.
- Define reusable functions for text cleaning, tokenization, and analysis.

### 3. Visualization (`3_FINAL_visual.ipynb`)
- Generate heatmaps showing character mentions and interactions.
- Analyze specific phrases and their usage patterns across episodes.
- Create visual summaries like bar charts and heatmaps to compare the frequency of emotions or phrases.

### 4. Power BI Dashboards
- Interactive dashboards provide deeper insights into trends, such as:
  - Emotional dynamics across episodes.
  - Recurring phrases in characters’ dialogues.
  - Character interactions visualized through dynamic filtering.

### 5. Exploration (`4_Playground.ipynb`)
- Experiment with additional analysis methods, refine existing approaches, and test hypotheses.

