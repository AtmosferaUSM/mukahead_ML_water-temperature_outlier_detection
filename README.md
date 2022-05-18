# Detecting outliers in a univariate time series dataset using unsupervised combined statistical methods: A case study on surface water temperature. Ecological Informatics
This is the accompanying Github page for the code and data of the "Detecting outliers in a univariate time series dataset using unsupervised combined statistical methods: A case study on surface water temperature" paper.

## Abstract
The surface water temperature is a vital ecological and climate variable, and its monitoring is critical. An extensive sensor network measures the ocean, but outliers pervade the monitoring data due to the sudden change in the water surface level. No single algorithm can identify the outlier efficiently. Hence, this work aims to propose and evaluate the performance of three statistical-based outlier detection algorithms for the water surface temperature: 1) the Standard Z-Score method, 2) the Modified Z-Score coupled with decomposition, and 3) the Exponential Moving Average with the Coupled Modified Z-Score and decomposition. A threshold was set to flag the outlier values. The models' performance was evaluated using the F-score method. Results showed that an increase in outlier detection might reduce the precision of identifying the actual outlier. Based on the results, the Exponential Moving Average with the Modified Z-Score gave the highest F-score value (= 0.83) compared to the other two individual methods. Therefore, this proposed algorithm is recommended to detect outliers efficiently in large surface water temperature datasets.

## Cite the paper
Jamshidi, E.J., Yusup, Y. Kayode, J.S., Kamaruddin, M.A. (2022), Detecting outliers in a univariate time series dataset using unsupervised combined statistical methods: A case study on surface water temperature. Ecological Informatics. 69, 101672. https://doi.org/10.1016/j.ecoinf.2022.101672

## The analysis code and requirements
The exploratory data analysis and the outlier detection algorithm are written in Python and in the Jupyter Notebook. Some Python packages may need to be installed before the code can be run.

## Dataset
The dataset can be downloaded at the link: https://github.com/AtmosferaUSM/outlier-detection-water-temperature/blob/main/data/water_temp.json.
For the rest of the data, you can download them at https://atmosfera.usm.my.
