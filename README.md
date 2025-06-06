# My Portfolio

#### Hello! The following README will contain some of my notable projects and future projects I am working on.

## Contact:
* _Github: https://github.com/sumanthkolli03_
* _LinkedIn: https://www.linkedin.com/in/sumanth-kolli-558320235_
* _Email: sumanthkolli03@gmail.com_


###  Current Project: Mojo-based KNN  
  
  * **Repository:**
  https://github.com/sumanthkolli03/MOJOKNN, may be outdated, is still being updated frequently.
  * **Description:**  A mojo-only implementation of KNN, with the hopes to speed up the process compared to Python (and sk-learn). Written entirely in mojo. Created for a research lab under Dr. Henry Han.


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
  
  * **Link:**  https://github.com/sumanthkolli03/Mojave
  * **Description:**  An in-depth analysis on invasive species Bromus Rubens in the Mojave region from 2013 until present.
Data was collected from NOAA, USDAFS, and data.gov.
Poster was presented at the 2023 Baylor Data Science conference.

<br/><br/><br/><br/><br/><br/>


###  Mountain Pine Beetle and Dissolved Organic Carbon Analysis
  
  * **Repository:**  https://github.com/sumanthkolli03/doc-analysis/blob/main/finalreport.pdf
  * **Description:**  Exploration of https://doi.org/10.3390/w10040534 for DSC2300. Data was taken from the article, and all wrangling and visualization was done in R. 

<br/><br/>

###  Water Quality in the Niobrara River - Using Dimensionality Reduction as a WQI
  
<img align="right" height="370" width="450px" src="https://github.com/sumanthkolli03/WQI/blob/main/wqi.png" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Repository:**  https://github.com/sumanthkolli03/WQI
  * **Description:** An analysis on water quality measures recorded by the DOI and the NPS for rivers in North Dakota, creating an index for measuring water quality by using different dimensionality reduction techniques such as PCA and MDS. Presented as a part of DSC 4320.
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
&nbsp;&nbsp;&nbsp; 3B.  modify images before-hand to have more robust training to weird screenshots  
&nbsp;&nbsp;&nbsp; 3C.  Fix edge cases by allowing user input if low confidence detected  
5.  ~~Allow model to updatable by calling riot's champion icon api~~
6.  use outputted champion data along with text-based data to create a bson for mongodb  
----Quality of Life----
7.  make everything seamless - allow one input of an image (or two) to output directy to mongodb
8.  make the steps above work with any size of image
9.  make sure the output is amennable with riot's api response
10.  package the entirity above in a discord bot


