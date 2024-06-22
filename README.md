<h1>Writeing Geometries to Newly Created Featureclass Using CSV Coordinates</h1>

<h2>Description</h2>
For this project, I developed a Python script to process a CSV file containing lap coordinates. The script iterates over the CSV data, storing coordinates in a dictionary alongside their respective lap numbers. This data is then used to generate polyline geometry, which is written to a newly created feature class. Additionally, new fields are added to the feature class attribute tables to record the lap information accurately.
<br />

<h2>Languages and Environments Used</h2>

- <b>Python</b> 
- <b>ArcGIS Pro</b>
- <b>PyScripter</b>

<h2>walk-through:</h2>

<p align="center">
Review CSV for Relevant Header Names: <br/>
<img src="https://imgur.com/8VaOUWv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Setup Our Environment in Pyscripter: <br/>
<img src="https://imgur.com/t1k2W51.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Define a function that we will use to write our Polyline Geometry: <br/>
<img src="https://imgur.com/CKswO9J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Open CSV & Find the Index for Relevant Headers: <br/>
<img src="https://imgur.com/56gs3Ku.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Conduct a Check of Relevant Rows in CSV, Create Featureclasses, and Write Geometry using Insert Cursor: <br/>
<img src="https://imgur.com/8cwRjAx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<p align="center">
Observe Our Results: <br/>
<img src="https://imgur.com/8msKp8K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
