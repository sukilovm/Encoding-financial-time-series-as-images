# Encoding financial time series as images – Application of image classification to predict stock price directions of the S&P 500 Index

**Type:** Master's Thesis

**Author:** Mirsad Sukilovic

**1st Examiner:** Prof. Dr. Lessmann

**2nd Examiner:** Prof. Dr. Fabian

## Summary
<div align="justify">
This research investigates machine learning (ML) methodologies for predicting future stock market performance, with an emphasis on the comparative efficiency of raw time series techniques and time series to image encoding methods. The study utilizes data from the S&P 500 stock market from December 2012 to December 2022. Performance indicators, including prediction accuracy, cross-entropy loss, and trading results, are considered for a comprehensive analysis of each method. The empirical findings disclose a discrepancy in the performance of the varying techniques. While the raw time series method occasionally achieves peak accuracy, it is hampered by high variance, compromising its outcomes' reliability. The image encoding method, Markov Transition Fields (MTF), showcases greater reliability in prediction accuracy. Based on the model's predictions, the initial trading strategy indicates that MTF outperforms the other techniques regarding investment returns during the specified period. However, the machine learning (ML) model-based strategy is outperformed by a basic buy-and-hold strategy, indicating the need for further refinement in trading strategy design. The study identifies potential areas for future research, including the enhancement of ML model architecture to suit each encoding technique, modification of the time frame and rolling window size for the time series, and increased computational resources for model training. This investigation contributes to the existing literature on stock market prediction using ML and serves as a foundation for continued exploration in the field.</div>
<br>

**Keywords:** <br>Machine Learning – Financial time series forecasting – Time series to image encoding –Image classification – Stock price prediction
<br><br>
<p align="center">
  <img width="698" alt="image" src="https://github.com/sukilovm/Encoding-financial-time-series-as-images/assets/74241476/b99b27b6-81b1-45fd-b82a-de3ef8a4eff0">
</p>
<br><br>
  
[Access the full text here.](https://www.researchgate.net/publication/373447921_Encoding_financial_time_series_as_images_-Application_of_image_classification_to_predict_stock_price_directions_of_the_SP_500_Index)
<br><br>
## Working with the repo

**Dependencies**
<div align="justify">
Python: All code in this repository was developed and tested using Python that comes with Google Colab (Pro+) as of August 2023. While specific version numbers might vary, it's generally aligned with Python 3.10.12.
</div>
<br>
<div align="justify">
Libraries: All required libraries and dependencies are installed directly within the Jupyter notebooks using pip install commands. These commands are included at the beginning of each notebook, ensuring all necessary packages are available for successful execution.
</div>
<br>

**Setup** <br><br>
To replicate the development environment:

1. Access Google Colab (Pro+).
2. Upload the Jupyter notebook(s) from this repository.
3. Run the notebook. The necessary libraries will be installed automatically as the notebook progresses.


## Reproducing results

Please run the notebooks in the specified sequence: <br>

**1. Thesis_Data**:<br>Generates the raw time series data of the Constituents Dataset. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Data.ipynb)
 <br> <br>
**2. Thesis_Images**:<br> Encodes the raw time series of the Constituents Dataset as images. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Images.ipynb) <br> Requires the file generated by Thesis_Data.<br> <br>
**3. Thesis_Models**:<br> Fits models and predicts on the Constituents Dataset.[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Models.ipynb)<br> Requires the files generated by Thesis_Images.<br> <br>
**4. Thesis_Trading**:<br> Loads models fitted on the Constituents Dataset to predict on the Index Dataset. [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sukilovm/Encoding-financial-time-series-as-images/blob/main/Thesis_Trading.ipynb) <br> Requires the files generated by Thesis_Models.
<br><br>
Ensure to replace the commented-out file paths in the notebooks based on your preferred file storage system.
 
