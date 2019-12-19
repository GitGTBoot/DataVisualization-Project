# DataVisualizations-Project

By George Oddoye & , Minu Khosla, Vidhya.J

Inspiration

There has been steady increase in  Gun Violence over the past decade and it continues to rapidly increase . Data scientists and statisticians can help analyze this dire situation by studying gun violence data and make informed predictions about future trends in order to build strategies that will eventually minimize , control gun violence and promote gun safety.

Goal 

To create a  web visualization dashboard :
1)	that has a landing page with  USA map visualization of the gun violence incidents
2)	 links to one or more visualization pages that will represent relationships between different variables in the form of pie charts, bar charts or scatter plots .

Data Source

Kaggle.com is the Data source for this project. We chose a dataset named  “Gun Violence Data” (https://www.kaggle.com/jameslko/gun-violence-data). This dataset contains more than 260k gun violence incidents, in the US between January 2013 and March 2018 , with detailed information about each incident, in CSV format.

Dataset owner James Kho built this dataset from gunviolencearchive.org. Since there is not much of easily – accessible data with detailed information on this subject , we are very grateful to James Kho for his endeavor . His work has helped us gain valuable data to study this matter and draw meaningful conclusions.

Extraction

Data was extracted from  a CSV file.

Transformation
1)	CSV file will be read into data frame and transformed .
2)	 Data in some columns have to be parsed , counted and stored in additional columns.
3)	Irrelevant columns  have to be dropped.  Renaming and rearrangement of columns have to be done along with changing of data types to maintain uniformity and to present meaningful data.
  Loading
Data frame  will be loaded into the relational database – Postgres.


Flask Application 
Flask application will be utilized and data from the Postgres database will derived to create endpoints that will contain json objects of necessary data from which maps and charts can be built.
Flask will also render the HTML template created to display all the features on the client web browser.

HTML pages
2 or more HTML pages will be created that will have access the JavaScript file in order to  display  the dashboard features on the browser . 

JavaScript file 
D3.js , Plotly and Leaflet libraries will provide the basic framework for building the USA gun violence information map and the different types of charts . 
Research will be done to add a plugin or a new JS library to enhance the features of the display elements. 


User-driven interaction  

1)	The web page / dashboard will be designed to contain a navigation bar with dropdown menu for the user to choose different views.
2)	The USA gun information map will contain different layer groups allowing the user to choose different visualizations





 link to the primary GitHub repository   

https://github.com/GitGTBoot/DataVisualizations-Project
