# My Portfolio

#### Hello! The following README will contain some of my notable projects and future projects I am working on.

## Contact:
* _Github: https://github.com/sumanthkolli03_
* _LinkedIn: https://www.linkedin.com/in/sumanth-kolli-558320235_
* _Email: sumanthkolli03@gmail.com_


###  SQL web viewer/editor
  <!--* **View Project:**  http://www.insertpage.com-->
  
<img align="right" height="270" width="450px" src="https://github.com/sumanthkolli03/portfolio/assets/108901380/9c64f695-1a55-4ea3-9e6d-e42a60f6fbea" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Repository:**  https://github.com/sumanthkolli03/sqlviewer
  * **Description:**  A simple browser-based SQL database viewer.
Can edit, drop, and create databases, tables, and will accept uploaded .sql data/query files.
Created using flask and sqlconnector.



<br/><br/><br/><br/><br/><br/>


###  New York Test Score Analysis
  <!--* **View Project:**  http://www.insertpage.com-->
  
<img align="right" height="270" width="350px" src="https://files.catbox.moe/ycbpnf.png" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Link:**  https://nytests.netlify.app/
  * **Description:**  An in-depth analysis on 2012 test scores in New York, including AP tests, SATs, and other state tests/metrics.
Data was collected from data.gov and from 2012 test websites. 
Analysis was performed in python, mostly using matplotlib and pandas.

<br/><br/><br/><br/><br/><br/>

###  Google Translator API
  <!--* **View Project:**  http://www.insertpage.com-->
  
  * **Repository:**  https://github.com/sumanthkolli03/translator
  * **Description:**  A command-line based python program that reads from a file, auto-detects language, translates and writes to a file.
Uses Google's cloud API to translate the source text (needs a working API key).
Created in python, runs using google-cloud-translate Package.

<br/><br/>

###  Mudae-Kivy Manager
  <!--* **View Project:**  http://www.insertpage.com-->
  
<img align="right" height="370" width="450px" src="https://files.catbox.moe/etqc25.gif" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Repository:**  https://github.com/sumanthkolli03/mudaeKivy
  * **Description:** Created a UI to interact with an existing discord bot to manipulate the user's inventory.
Created in python, runs using the Kivy Package.
<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>
### Mojave Region Invasive Grass Time Series Analysis
  <!--* **View Project:**  http://www.insertpage.com-->
  
<img align="right" height="270" width="400px" src="https://files.catbox.moe/36hrjh.png" alt="html" style="vertical-align:top; margin:4px">  
  
  * **Link:**  https://drive.google.com/file/d/16XS7o0pXqhBd8DIxHXZM4lQA3pAHK3Dh/view?usp=sharing
  * **Description:**  An in-depth analysis on invasive species Bromus Rubens in the Mojave region from 2013 until present.
Data was collected from NOAA, USDAFS, and data.gov.
Poster was presented at the 2023 Baylor Data Science conference.


### --WIP-- Customs Database Bot for League of Legends Customs Games
  <!--* **View Project:**  http://www.insertpage.com-->
  
  
  * **Repository:**
  *coming soon*
  * **Description:**  A discord bot and standalone application that takes screenshots of league of legends customs games and outputs formatted, api-readable data to a database. Created to make up for Riot's lack of custom game histories and api calls. Should end up in the same format as an api response from riot, as to allow seamless integration with existing programs


Tasklist:  
1) ~~Use Tesseract OCR to read in all the text-based data from the stats screen.~~
2) ~~Separate and prepare text-based data in python.~~
3) **Use tensorflow/keras to create a neural net to recognize specifically small champion icons in the stats page**  
     3.1) Test Model and get > 98% accuracy
4) Allow model to updatable by calling riot's champion icon api
5) use outputted champion data along with text-based data to create a bson for mongodb  
----Quality of Life----
6) make everything seamless - allow one input of an image (or two) to output directy to mongodb
7) make the steps above work with any size of image
8) make sure the output is amennable with riot's api response
9) package the entirity above in a discord bot


