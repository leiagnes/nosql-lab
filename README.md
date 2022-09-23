<b>Introduction</b><br>
This project demonstrates the combination of Python and MongoDB for a full data analysis pipeline.<br><br>
<b>Data Pipeline</b><br><br>
`Extract`<br>
Data is fetched from the FoodData Central API, which provides REST access to FoodData Central (FDC) with two
endpoints: the Food Search endpoint, which returns foods that match desired search criteria, and the Food
Details endpoint, which returns details on a particular food.
<br>
`Load`<br>
The data is imported into a MongoDB cluster using Python.<br>
`Transformation`<br>
Modeling, transformation and cleansing of the data is done in MongoDB.<br>
`Data Analysis`<br>
An in-depth analysis in Python is done using various MongoDB Aggregation Pipelines
