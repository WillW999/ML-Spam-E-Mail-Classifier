<h1>Supervised ML Spam Email Classifier</h1>

<h2>Description</h2>
Using a dateset of spam and non spam emails I construct a supervised machine learning binary classifier that is able to detect spam emails at 93% accuracy. 
<br />


<h2>Environment and Packages Used</h2>

- <b>DataBricks</b>
- <b>Pandas</b> 
- <b>Pyspark</b>


<h2>Project walk-through:</h2>

<p align="center">
Creation of schema and first look at dataset: <br/>
<img src="https://i.imgur.com/lfmMXWV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Importing pyspark and data preperation:  <br/>
<img src="https://i.imgur.com/24fT9Ns.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Creating Logistic Regression Model and feature weights: <br/>
<img src="https://i.imgur.com/4CBUzOP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using training data to fit model for test data:  <br/>
<img src="https://i.imgur.com/jc79pom.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
