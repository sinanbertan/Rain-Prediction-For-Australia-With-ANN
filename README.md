
# Rain-Prediction-For-Australia-With-ANN

- This project focuses on predicting of Rain in Australia. The project includes machine learning,deep learning, exploratory data analysis (EDA), and data visualization techniques to gain insights into the dataset and understand its patterns. The project uses the weatherAUS.csv dataset, which can be downloaded from Kaggle: https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package
# ACKNOWLEDGEMENTS

### DATA CONTENT
- This dataset contains about 10 years of daily weather observations from many locations across Australia.

- RainTomorrow is the target variable to predict. It means -- did it rain the next day, Yes or No? This column is Yes if the rain for that day was 1mm or more.

### FEATURE CONTENT

* minTemp: Minimum temperature (°C)
* maxTemp: Maximum temperature (°C)
* Rainfall (mm)
* Evaporation (mm) : evaporation is measured in the open pan and is defined as the depth of water that would evaporate from a free water surface in an open pan of unrestricted area, under the influence of the given weather conditions of a certain place and time.
* Sunshine (hours)
* windGustDir: Direction of strongest wind gust
* windGustSpeed: Speed of strongest wind gust (km/h)
* windDir9am: Wind direction at 9am
* windDir3pm: Wind direction at 3pm
* windSpeed9am: Wind speed at 9am (km/hr)
* windSpeed3pm: Wind speed at 3pm (km/hr)
* humidity9am: Relative humidity at 9am (%)
* humidity3pm: Relative humidity at 3pm (%)
* pressure9am: Atmospheric pressure at 9am (hpa)
* pressure3pm: Atmospheric pressure at 3pm (hpa)
* cloud9am: Fraction of sky obscured by cloud at 9am (oktas)
* cloud3pm: Fraction of sky obscured by cloud at 3pm (oktas)
* temp9am: Temperature at 9am (°C)
* temp3pm: Temperature at 3pm (°C)
* raintoday: Rain today (boolean)
* raintomorrow: Rain tomorrow (boolean)

## Installation
The following tools were used for this analysis:

- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scipy
- Sklearn
- Keras
- Tenserflow

- To run this project, you will need to have Python 3 installed on your machine. You can install the required libraries by running the following command:


- pip install pandas matplotlib seaborn numpy plotly Sklearn Keras Tenserflow
    
## Usage 
- To run the analysis, simply execute the notebook. The script will generate several visualizations that help illustrate analysis of data.
## Roadmap

[1. IMPORTING LIBRARIES](#1)
    
[2. LOADING DATA](#2)  

[3. DATA CONTENT](#3)

[4. EXPLORATORY DATA ANALYSIS](#4)

[5. DATA VISUALIZATION AND CLEANINGS](#5)

[6. OUTLIER DETECTON](#6)

[7. DATA PREPROCESSING](#7)     

[8. MODEL BUILDING AND TRAINING](#8) 
   
[9. MODEL EVALUATION](#9)

[10. CONCLUSION](#10)


 The analysis includes visualizations using Matplotlib, Plotly and Seaborn.

## Contributing

- Contributions to this project are welcome. If you notice any errors or have ideas for additional analyses, please feel free to open an issue or submit a pull request.


## Conclusion 

* After I have done the Exploratory Data Analysis, I have found out that there are outliers in the dataset. I have used the IQR method to fill the outliers with median. And then I have done data visualization to get insight from data. After that I have built ANN model with 5 layers. After training model, I got %83.57 accuracy score from my model. 

