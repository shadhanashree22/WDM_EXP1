### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 20.4.2026
### AIM: 
  To Create Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform preprocessing
### PROCEDURE: 
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Employee Table.

```
--------------
Employee Data
---------------
@relation employee
@attribute name {x,y,z,a,b}
@attribute id numeric
@attribute salary {low,medium,high}
@attribute exp numeric
@attribute gender {male,female}
@attribute phone numeric
@data
x,101,low,2,male,250311
y,102,high,3,female,251665
z,103,medium,1,male,240238
a,104,low,5,female,200200
b,105,high,2,male,240240

--------------
Weather Data
---------------
@relation weather
@attribute outlook {sunny,rainy,overcast}
@attribute temparature numeric
@attribute humidity numeric
@attribute windy {true,false}
@attribute play {yes,no}
@data
sunny,85.0,85.0,false,no
overcast,80.0,90.0,true,no
sunny,83.0,86.0,false,yes
rainy,70.0,86.0,false,yes
rainy,68.0,80.0,false,yes
rainy,65.0,70.0,true,no
overcast,64.0,65.0,false,yes
sunny,72.0,95.0,true,no
sunny,69.0,70.0,false,yes
rainy,75.0,80.0,false,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows employee table on weka.

### OUTPUT:
# EMPLOYEE DATA

<img width="1277" height="955" alt="Screenshot 2026-04-18 142007" src="https://github.com/user-attachments/assets/d9ecafbb-459c-4b6a-abda-ddcdb562c6cf" />



# WEATHER DATA

<img width="1271" height="962" alt="Screenshot 2026-04-18 141525" src="https://github.com/user-attachments/assets/edb0928c-fb27-4982-b2b3-3746a00ca6b3" />



### PREPROCESSING
### Procedure:
#### 1) Add -> Pre-Processing Technique:
1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Add.
9) A new window is opened.
10) In that we enter attribute index, type, data format, nominal label values for Climate.
11) Click on OK.
12) Press the Apply button, then a new attribute is added to the Weather Table.
13) Save the file.
14) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
# EMPLOYEE DATA

<img width="1265" height="948" alt="Screenshot 2026-04-18 142109" src="https://github.com/user-attachments/assets/006fc489-3105-4b38-a78d-702a7d90cf40" />

# WEATHER DATA

<img width="1306" height="983" alt="Screenshot 2026-04-18 141635" src="https://github.com/user-attachments/assets/e748fe8a-b0be-424f-82ab-c06e3233bc13" />



### 2) Remove -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Remove.
9) Select the attributes windy, play to Remove.
10) Click Remove button and then Save.
11) Click on the Edit button, it shows a new Weather Table on Weka.

### OUTPUT:
# EMPLOYEE DATA

<img width="1266" height="952" alt="Screenshot 2026-04-18 142150" src="https://github.com/user-attachments/assets/c6415356-b265-467c-a8f1-027c571a7cf1" />



# WEATHER DATA

<img width="1264" height="957" alt="image" src="https://github.com/user-attachments/assets/74373b30-9863-430a-87d2-66c64219cf57" />


### Normalize -> Pre-Processing Technique:

1) Start -> Programs -> Weka-3-4 -> Weka-3-4
2) Click on explorer.
3) Click on open file.
4) Select Weather.arff file and click on open.
5) Click on Choose button and select the Filters option.
6) In Filters, we have Supervised and Unsupervised data.
7) Click on Unsupervised data.
8) Select the attribute Normalize.
9) Select the attributes temparature, humidity to Normalize.
10) Click on Apply button and then Save.
11) Click on the Edit button, it shows a new Weather Table with normalized values on Weka.

### OUTPUT:
### EMPLOYEE DATA

<img width="1920" height="1080" alt="Screenshot 2026-04-18 142255" src="https://github.com/user-attachments/assets/46903a91-28a3-4ce2-9741-38c77094831e" />


### WEATHER DATA

<img width="1264" height="949" alt="Screenshot 2026-04-18 141915" src="https://github.com/user-attachments/assets/56cfc228-68ae-4b69-8a23-337c23443c5a" />


### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
