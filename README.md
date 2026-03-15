# MIT_15773_Final_Project_Mar2026

## Introduction

In the modern data-driven economy, social media has become a central platform for customer interaction, brand visibility, and real-time insight into consumer sentiment. Higher levels of consumer–brand engagement on these platforms are closely linked to improved conversion and purchase intention, making engagement a key driver of retail performance, particularly for small and medium enterprises (SMEs). Research further indicates that content characteristics such as readability and depth are positively associated with higher engagement and audience awareness. Therefore, identifying which features of text-based social media posts drive engagement is essential for businesses.

In this study, we developed natural language processing (NLP) models to predict the engagement level of text-based posts across different social media platforms, including Facebook, Twitter, and Instagram, in order to generate actionable insights for customer experience management, brand monitoring, and market intelligence. Specifically, we constructed two models: one using text-only inputs and another using text together with textualized emojis. By comparing these two configurations, we aim to evaluate whether emoji-derived information improves the model’s ability to predict high-engagement posts.

## Dataset
The [Kaggle SocialBuzz Sentiment Analytics](https://www.kaggle.com/datasets/eshummalik/socialbuzz-sentiment-analytics) dataset contains text-based social media posts with associated engagement metrics, including likes, as well as additional attributes such as sentiment labels. In this study, engagement level, measured by the number of likes, is categorised based on a defined threshold and treated as a binary outcome variable. Emojis in the text data are converted into textual representations during preprocessing to support linguistic analysis.

## Files

- `MIT15773_2026_Group21_NOweights.ipynb` <br>
Google Colab notebook containing the models trained without class-weight adjustments.

- `MIT15773_2026_Group21_weights.ipynb` <br>
Google Colab notebook containing the models trained with class-weight adjustments.
