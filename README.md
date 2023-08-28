# Encoding financial time series as images – Application of image classification to predict stock price directions of the S&P 500 Index

**Type:** Master's Thesis

**Author:** Mirsad Sukilovic

**1st Examiner:** Prof. Dr. Lessmann

**2nd Examiner:** Prof. Dr. Fabian

## Summary
<div align="justify">
This research investigates machine learning (ML) methodologies for predicting future stock market performance, with an emphasis on the comparative efficiency of raw time series techniques and time series to image encoding methods. The study utilizes data from the S&P 500 stock market from December 2012 to December 2022. Performance indicators, including prediction accuracy, cross-entropy loss, and trading results, are considered for a comprehensive analysis of each method. The empirical findings disclose a discrepancy in the performance of the varying techniques. While the raw time series method occasionally achieves peak accuracy, it is hampered by high variance, compromising its outcomes' reliability. The image encoding method, Markov Transition Fields (MTF), showcases greater reliability in prediction accuracy. Based on the model's predictions, the initial trading strategy indicates that MTF outperforms the other techniques regarding investment returns during the specified period. However, the machine learning (ML) model-based strategy is outperformed by a basic buy-and-hold strategy, indicating the need for further refinement in trading strategy design. The study identifies potential areas for future research, including the enhancement of ML model architecture to suit each encoding technique, modification of the time frame and rolling window size for the time series, and increased computational resources for model training. This investigation contributes to the existing literature on stock market prediction using ML and serves as a foundation for continued exploration in the field.
</div>
<br>

**Keywords:** <br>Machine Learning – Financial time series forecasting – Time series to image encoding –Image classification – Stock price prediction
<br><br>
<p align="center">
  <img width="698" alt="image" src="https://github.com/sukilovm/Encoding-financial-time-series-as-images/assets/74241476/b99b27b6-81b1-45fd-b82a-de3ef8a4eff0">
</p>
<br>





**Thesis_Data**: Generates the raw time series data of the Constituents Dataset. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Data.ipynb)
 <br>
**Thesis_Images**: Encodes the raw time series of the Constituents Dataset as images. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Images.ipynb) <br>
**Thesis_Models**: Fits models and predicts on the Constituents Dataset. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Models.ipynb)<br>
**Thesis_Trading**: Loads models fitted on the Constituents Dataset to predict on the Index Dataset. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Trading.ipynb)

 
