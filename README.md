# NYC_Trees

Urban trees provide a multitude of benefits to city residents. In addition to the environmental benefits trees offer
such as lowering the temperature in urban areas and reducing flooding, urban trees also contribute to physical and
economic health by creating walk appeal and increasing property value. Street trees are unique in that they are
overseen by public municipal authorities, but they are difficult to manage because they are dispersed within the city
in close proximity to private properties. Additionally, recent studies have shown significant associations between
socioeconomic factors and street trees in urban neighborhoods. This report will attempt to reveal the associations
between tree characteristics and geospatial properties, socioeconomic characteristics of the regions the trees are
located in, and also motivate efforts to maintain healthy trees within NYC.

We aim to answer the following questions using the NYC street tree census dataset:
- What tree features are related to tree health? Do different demographic groups show different tree statistics? [Inference](https://github.com/chens28/NYC_Trees/blob/main/code/2_Inference_P2_Hypothesis_Tests.ipynb)
- Can we use different demographic characteristics to predict tree density in the respective Neighborhood
Tabulation Areas (NTAs)? [Regression](https://github.com/chens28/NYC_Trees/blob/main/code/3_Prediction.ipynb)
- For the 10 species that have the most data points, can we predict the health status of a tree based on the
features included in this dataset? Is one feature more important/more useful in predicting the health status
for one species than the other? [Classification Prep](https://github.com/chens28/NYC_Trees/blob/main/code/4_Classification_P2_Lasso_FAMD.ipynb) and [Models](https://github.com/chens28/NYC_Trees/blob/main/code/4_Classification_P3_Models.ipynb)

Refer to the full report [here](https://github.com/chens28/NYC_Trees/blob/main/Project%20Report/Team%20Lorax_%20Project%20Report.pdf).
## Data
Our main dataset is the NYC street tree census from 2015 which can be accessed [here](https://data.cityofnewyork.us/Environment/2015-Street-Tree-Census-Tree-Data/pi5s-9p35) thorugh NYC OpenData Depository. Your can refer to desciptions of the data in this [file](https://www.google.com/url?q=https://data.cityofnewyork.us/api/views/pi5s-9p35/files/2e1e0292-20b4-4678-bea5-6936180074b3?download%3Dtrue%26filename%3DStreetTreeCensus2015TreesDataDictionary20161102.pdf&sa=D&source=docs&ust=1672680238434895&usg=AOvVaw3dF0kM8iOoFJQuCbM5lN0p).

## Sample Visualizations
![IMAGE3!](https://github.com/chens28/NYC_Trees/blob/main/Project%20Report/inference.png)

![IMAGE2!](https://github.com/chens28/NYC_Trees/blob/main/Project%20Report/ROC.png)

![IMAGE1!](https://github.com/chens28/NYC_Trees/blob/main/Project%20Report/FAMD.png)

