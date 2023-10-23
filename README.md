# sales-predictions
Good Day reader, this github project is here to showcase my current skills in Data Science which include visualizations and Machine Learning models. Included in this README will be some explanations of the 
graphs or visualizations I made for sales predictions and Machine Learning models to predict future sales.


## Visualization Explanations

The visualizations or grpahs present in the code you will see:

* **Barchart for Number of items sold per type**
* **Histogram for Item Outlet Sales**
* **Boxplot of Item Outlet Sales**
* **Boxplot for Outlet type and Item Outlet Sales**
* **Heatmap**
* **Seaborn lmplot**
* **Chart for Item Weight and Average Item MRP**

  ## Explanations

1. Barchart for Number of items sold per type - This Barchart highlights the different types of items sold in total, wherein Fruits and Vegtables are the most prominent type of item sold with Snack foods coming in at second. This Barchart provides an overview of what items are popular with consumers and which are not, therefore the business can see which products can be worked on for sales strategies

2. Histogram for Item Outlet Sales- This histogram highlights the Item Outlet Sales and its various frequencies, to which it shows a downward type of trend. Wherein as the sales increases, its frequencies are seen to be lower. Though it doesn't fully indicate any comprehensive trend, it can be a good basis to see how the sales are doing which can be used for further analysis.

3. Boxplot of Item Outlet Sales- The Boxplot of the Item Outlet Sales indicate that there are many outliers and that the distribution of data is positvely skewed. Wherein the median Item Outlet Sales is around the 2000, however majority of the data is above the median.

4. Boxplot for Outlet type and Item Outlet Sales- The Boxplots in this visualization highlight the different types of store types and the distribution of Item Outlet Sales per store type. Wherein Supermarket Types 1 and 2 are similar in the spread of their data and medians albeit that Supermarket Type 1 has more outliers. Supermarket Type 3 on the otherhand has a higher median with data points in the upper percentile, which indicate its performing well in terms of sales. Lastly, the Grocery store is the most underperforming type of store as its maximum limit is not even close to the medians of the other stores.

5. Heatmap- The heatmap shows possible correlation of values to which the only meaningful correlation is between Item MRP and Item Outlet Sales with a moderate correlation of 0.57.

6. Seaborn lmplot- The Seaborn lmplot shows the variables of Item Outlet Sales and Item Weight with the hue of Item Fat Content, with a linear regression line that indicates that the variables have no relationship as seen by the horizontal linear regression line.

7. Chart for Item Weight and Average Item MRP - The graphs that show the Item Weight and Average Item MRP by year and how it changes, wherein for the Item Weights it peaked at 1987 at around 13.00 while seen its lowest at 2002 at 12.65. Further more as years progress the Item Weights have yet to reach its previous highest peak but shows signs of higher growth. As for the Item MRP, it peaked at 2004 but right after experienced a significant drop going to 2007 which is also its lowest then had an upward trend oncemore highlighting an erratic trend.

## MACHINE LEARNING MODELS
1.Linear Regression- As seen by the different metrics such as R^2 scores and RMSE, the Linear Regression model is not suitable in prediciting future sales due to the testing data having a negative R^2 score and it being extremely low to the point wherein it looks unreasonable given the values.

2. Decision Tree Regressor Model- This model showed much better results compared to the Linear Regression model, but was still unsuitable given training R^2 score of 1.00 which is perfect but the testing R^2 score is 0.22 which it means it performs poorly on testing data suggesting high bias. With that, adjustments were made with the max depth so the new R^2 scores of the training and testing data is 0.60 or extremely close together suggesting a somewhat balanced model but still with significant variance.
