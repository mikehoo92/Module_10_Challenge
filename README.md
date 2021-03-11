# Cryptocurrency Advisor

This notebook clusters cryptocurrencies by their performance in different time periods. We will plot the results so that we can visually show the performance to the board. This proposed idea will not only depend on returns and volatility, rather factors that might impact the crypto market—leading to better performance for your portfolio.

![](Images/bokeh_plot.png)

---

## Technologies

This project uses a Jupyter Notebook in Jupyter Lab with the following libraries:

- Pandas: to help with the robust amount of features that will help analyze and organize the data.
- HvPlot: to create interactive data visualizations that are visually pleasing to the audience
- scikit-learn: to import the **K-means algorithm** which will identify clusters to solve clustering business problems, **PCA** a statistical technique that we use to speed up machine learning algorithms when too many features, or dimensions, exist, and the **Standard Scaler** which will help normalize and scale data so that it is easily comparable. 


---

## Usage

To succesfully run this notebook, please be sure to import the required libraries and dependencies:

```
import pandas as pd
import hvplot.pandas
from path import Path
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
from sklearn.preprocessing import StandardScaler
```

---

## Contributors

Michael Husary was the main contributer along with fellow classmates and the educational staff. 

--- 

## License
*(Not sure if a license was required on this Challenge)*


MIT
