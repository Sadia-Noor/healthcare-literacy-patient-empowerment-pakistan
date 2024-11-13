# Empowering Healthcare Literacy and Patient Empowerment in Pakistan

This project aims to enhance healthcare literacy and empower patients in Pakistan by utilizing social media data to analyze public sentiment and understand healthcare challenges. By aligning with Sustainable Development Goals (SDGs) 3 (Good Health and Well-being) and 4 (Quality Education), the project promotes health education and patient participation, aiming to improve health outcomes and foster lifelong learning.

## Project Overview

In Pakistan, low health literacy and limited patient empowerment create significant barriers to accessing quality healthcare. This project seeks to address these issues by analyzing social media data, particularly from Twitter, to gain insights into public perceptions and the challenges within the healthcare system. The goal is to create actionable insights that support both healthcare literacy and patient involvement in healthcare decisions.

### Key Objectives
- **Increase healthcare literacy** in Pakistan by analyzing public sentiment and perceptions using social media data.
- **Empower patients** to participate actively in healthcare decisions, improving healthcare outcomes.
- **Support SDGs 3 and 4** by promoting healthcare education and lifelong learning.

## Methodology

1. **Data Collection**: 
   - Collected relevant healthcare data from social media (primarily Twitter) using the Apify web scraping platform, covering tweets from 2020 to 2024.

2. **Data Preprocessing**:
   - Cleaned and processed text data to prepare for analysis, including tokenization, stopword removal, and lemmatization.

3. **Sentiment Analysis**:
   - Employed multiple sentiment analysis techniques, including:
     - **VADER**: Rule-based analysis tailored for social media.
     - **TextBlob**: Lexicon-based sentiment analysis.
     - **RoBERTa**: Deep learning-based model for nuanced sentiment classification.
   - Classified sentiments into positive, neutral, and negative categories.

4. **Exploratory Data Analysis (EDA)**:
   - Visualized tweet lengths, hashtags, and word frequency to identify key themes and patterns in healthcare-related discussions.

5. **Topic Modeling and Named Entity Recognition (NER)**:
   - Used **Latent Dirichlet Allocation (LDA)** for topic modeling to uncover prevalent themes in healthcare discourse.
   - Applied **spaCy's NER** model to extract entities (e.g., people, organizations, locations) from the text.

6. **Machine Learning Models**:
   - Tested various machine learning models (Random Forest, SVC, Logistic Regression) to predict sentiment with accuracy rates as high as 85%.

## Results

- **Sentiment Analysis**: The analysis showed a predominance of neutral tweets, with positive sentiments slightly outweighing negative ones. This indicates a generally moderate public perception of healthcare quality in Pakistan.
- **Model Performance**: The **Random Forest** model achieved the highest accuracy at 85%, making it the most effective model for sentiment classification in this dataset.

## Impact and Conclusion

By analyzing public sentiment towards healthcare, this project provides insights that can inform policy and improve patient empowerment in Pakistan. The findings contribute to SDGs 3 and 4 by advocating for increased healthcare literacy and patient involvement in healthcare decisions.

## Future Work

Future directions include expanding the dataset, incorporating more social media sources, and refining machine learning models to improve accuracy in capturing nuanced sentiments and trends.

## Team

- **Aaqib Ali**
- **Sadia Noor**
- **Javeria Ahmed**

## Acknowledgments

This project was conducted as part of the Social Web Mining course in the MS Data Science program at the School of Electrical Engineering and Computer Science (SEECS), National University of Sciences and Technology (NUST).

## References

1. [Atif, M. et al. (2022). Perceptions of healthcare professionals and patients on the role of the pharmacist in TB management in Pakistan: A qualitative study. *Frontiers*](https://www.frontiersin.org/journals/pharmacology/articles/10.3389/fphar.2022.965806/full)
2. [Khan, N. et al. (2020). Pharmacists' viewpoint towards their professional role in the healthcare system: a survey of hospital settings of Pakistan. *BMC Health Services Research*](https://link.springer.com/article/10.1186/s12913-020-05459-0)
3. [Muhammad, Q. et al. (2023). Healthcare in Pakistan: Navigating challenges and building a brighter future. *Cureus*](https://assets.cureus.com/uploads/editorial/pdf/161591/20230710-4592-1yspsm3.pdf)
