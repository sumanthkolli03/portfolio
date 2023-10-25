# My Portfolio

#### Hello! The following README will contain some of my notable projects and future projects I am working on.

## Contact:
* _Github: https://github.com/sumanthkolli03_
* _LinkedIn: https://www.linkedin.com/in/sumanth-kolli-558320235_
* _Email: sumanthkolli03@gmail.com_


###  SQL web viewer/editor
  
<img align="right" height="270" width="450px" src="https://github.com/sumanthkolli03/portfolio/assets/108901380/9c64f695-1a55-4ea3-9e6d-e42a60f6fbea" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Repository:**  https://github.com/sumanthkolli03/sqlviewer
  * **Description:**  A simple browser-based SQL database viewer.
Can edit, drop, and create databases, tables, and will accept uploaded .sql data/query files.
Created using flask and sqlconnector.



<br/><br/><br/><br/><br/><br/>

###  S & P 500 Stock Prediction Neural Net
  
  * **Repository:**  *coming soon, 11/7/2023*
  * **Description:**  A neural net trained on data from the S&P 500 that is used to predict the price of individual stocks and the entire index fund.
Created as part of a project for DSC 3344, in which a fellow student offers a project idea, and we complete it for them.
Created using python, sk-learn, and data from yfinance (yahoo stocks).

<br/><br/><br/><br/><br/><br/>

###  New York Test Score Analysis
  
<img align="right" height="270" width="350px" src="https://files.catbox.moe/ycbpnf.png" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Link:**  https://nytests.netlify.app/
  * **Description:**  An in-depth analysis on 2012 test scores in New York, including AP tests, SATs, and other state tests/metrics.
Data was collected from data.gov and from 2012 test websites. 
Analysis was performed in python, mostly using matplotlib and pandas.

<br/><br/><br/><br/><br/><br/>

### Mojave Region Invasive Grass Time Series Analysis
  
<img align="right" height="270" width="400px" src="https://files.catbox.moe/36hrjh.png" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Link:**  https://drive.google.com/file/d/16XS7o0pXqhBd8DIxHXZM4lQA3pAHK3Dh/view?usp=sharing
  * **Description:**  An in-depth analysis on invasive species Bromus Rubens in the Mojave region from 2013 until present.
Data was collected from NOAA, USDAFS, and data.gov.
Poster was presented at the 2023 Baylor Data Science conference.

<br/><br/><br/><br/><br/><br/>


###  Mountain Pine Beetle and Dissolved Organic Carbon Analysis
  
  * **Repository:**  https://github.com/sumanthkolli03/doc-analysis/blob/main/finalreport.pdf
  * **Description:**  Exploration of https://doi.org/10.3390/w10040534 for DSC2300. Data was taken from the article, and all wrangling and visualization was done in R. 

<br/><br/>

###  Mudae-Kivy Manager
  
<img align="right" height="370" width="450px" src="https://files.catbox.moe/etqc25.gif" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Repository:**  https://github.com/sumanthkolli03/mudaeKivy
  * **Description:** Created a UI to interact with an existing discord bot to manipulate the user's inventory.
Created in python, runs using the Kivy Package.
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>


### --WIP-- Customs Database Bot for League of Legends Customs Games
  
  
  * **Repository:**
  *coming soon* (on colab for now)
  * **Description:**  A discord bot and standalone application that takes screenshots of league of legends customs games and outputs formatted, api-readable data to a database. Created to make up for Riot's lack of custom game histories and api calls. Should end up in the same format as an api response from riot, as to allow seamless integration with existing programs


Tasklist:  
1.  ~~Use Tesseract OCR to read in all the text-based data from the stats screen.~~
2.  ~~Separate and prepare text-based data in python.~~
3.  ~~Use tensorflow/keras to create a neural net to recognize specifically small champion icons in the stats page~~  
&nbsp;&nbsp;&nbsp; 3A.  **get > 98% accuracy**
5.  ~~Allow model to updatable by calling riot's champion icon api~~
6.  use outputted champion data along with text-based data to create a bson for mongodb  
----Quality of Life----
7.  make everything seamless - allow one input of an image (or two) to output directy to mongodb
8.  make the steps above work with any size of image
9.  make sure the output is amennable with riot's api response
10.  package the entirity above in a discord bot


