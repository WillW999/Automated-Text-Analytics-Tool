<h1>Automated Word Cloud and Sentiment Analysis Tool</h1>

<h2>Description</h2>
Created an automated word cloud generator and sentiment analysis tool, that is used to sort through open ended survey question data. This tool was created to help sort through large amounts of open ended text data to show what the most common words and phrases were throughout a particular survey question.  It also shows the overall positive or negative sentiment a particular question has generated.  This tool was automated so that those with no python experience would be able to utilize it.
<br />


<h2>Environment and Packages Used</h2>

- <b>Google Colaboratory</b>
- <b>Pandas</b> 
- <b>Natural Language Toolkit (NLTK)</b>
- <b>Gensim</b>

<h2>Project walk-through:</h2>

<p align="center">
importing proper libraries: <br/>
<img src="https://i.imgur.com/8vVVelX.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
<br />
<br />
Uploading of data csv and word cloud image:  <br/>
<img src="https://i.imgur.com/YQfhBfe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Cleaning the data: <br/>
<img src="https://i.imgur.com/nVxw2Ly.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Splitting the data by each individual open ended question:  <br/>
<img src="https://i.imgur.com/fRFw2h9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
5-fold crossvalidator on test data:  <br/>
<img src="https://i.imgur.com/Kjfzwpg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creation of decision tree:  <br/>
<img src="https://i.imgur.com/CqCTL5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Accuracy metrics:  <br/>
<img src="https://i.imgur.com/uOlG0Ae.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
