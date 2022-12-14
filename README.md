<h1>Supervised ML Spam Email Classifier</h1>

<h2>Description</h2>
Using a dateset of spam and non spam emails I construct a supervised machine learning binary classifier that is able to detect spam emails at 97% accuracy. 
<br />


<h2>Environment and Packages Used</h2>

- <b>DataBricks</b>
- <b>Pandas</b> 
- <b>Pyspark</b>


<h2>Project walk-through:</h2>

<p align="center">
Importing of packages and dataset: <br/>
<img src="https://i.imgur.com/lfmMXWV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Splitting dataset into test and train:  <br/>
<img src="https://i.imgur.com/24fT9Ns.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Converting dataset to RDD Array: <br/>
<img src="https://i.imgur.com/4CBUzOP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Elbow method to find optimal amount of clusters:  <br/>
<img src="https://i.imgur.com/yzsKWfF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Cluster the datapoints:  <br/>
<img src="https://i.imgur.com/Kjfzwpg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Showing cluster assingment by point as well as cluster centers:  <br/>
<img src="https://i.imgur.com/CqCTL5y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Actual cluster locations in Chicago:  <br/>
<img src="https://i.imgur.com/486ye9G.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
