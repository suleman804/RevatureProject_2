The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment of different types of restaurant at different places in Bengaluru.Bengaluru being an IT capital of India. Most of the people here are dependent mainly on the restaurant food as they don't have time to cook for themselves. With such an overwhelming demand of restaurants it has therefore become important to study the demography of a location. What kind of a food is more popular in a locality.

Firstly we have downloaded the zomato restaurant dataset from Kaggle. You can download the dataset with the following link https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants

As this dataset set is hugh and it has a lot of messy data, we performed preprocess of data and removed few records, replaced null values with appropriate values and we also add few columns like discount, capacity, acceptable payment mode, catering etc to the existing data.

The preprocessing code is given in the preprocessing file.
## A Brief Descritpion about the data.

|Column_Name|Used_For|
|:---------------|:---------------|
|**url: string (nullable = true)**          |   *URL for the restaurant to check the facilities of the restaurant.*|
|**address: string (nullable = true)**      |  *Address of the restaurant.*|
|**name: string (nullable = true)**         |  *Name of the Restaurant.*|
|**online_order: string (nullable = true)** |  *Online order facility is available or not*|
|**book_table: string (nullable = true)**   |  *Online booking table facility is available or not*| 
|**rate: double (nullable = true)**         |  *Rating of the Restaurant.*|
|**votes: integer (nullable = true)**       |  *Number of votes got by a particular restaurant.*|
|**phone: string (nullable = true)**        |  *Contact Number to contact in restaurant.*|
|**location: string (nullable = true)**     |  *Location of the Restaurant.*|
|**rest_type: string (nullable = true)**    |  *Type of the Restaurants.*|
|**cuisines: string (nullable = true)**     |  *Cuisines Type.*|
|**approx_cost_for_two_people: integer (nullable = true)** |*Cost for two people.*|
|**reviews_list: string (nullable = true)**  | *Reviews Given by the customers.*|
|**menu_item: string (nullable = true)**     | *Type of items available in the menu.*|
|**listed_in_type: string (nullable = true)**| *Type of restaurants which thing they specially made for.*|
|**listed_in_city: string (nullable = true)**| *Cities in which restaurants are listed.*|
|**payMode: string (nullable = true)**       | *Payment Mode accepted by the restaurants.*|
|**Discount: integer (nullable = true)**     | *Available Discount at Restaurant.*|
|**Capacity: integer (nullable = true)**     | *how many persons can have food at restaurant at a time.*|
|**Catering: string (nullable = true)**      | *Catering facility is there or not.*|


## Technology Used :
- SparkSQL
- Hadoop 2.x (HDFS+YARN)
- Spark
- PySpark
- jupyter Notebook
- Python
- MySQL
- Sqoop
## Contributions :
- Eswar - Data Analytics
- Suleman - Data Collection and Preprocessing
- Neha - Quality Assurance
