### EX1 Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE: 31/10/2026
### NAME: Sanjeev A
### REG NO: 212224230246
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
<img width="1920" height="1080" alt="1" src="https://github.com/user-attachments/assets/200d4c2c-822a-48a8-a4a7-bfc96068e557" />
<img width="1237" height="735" alt="2" src="https://github.com/user-attachments/assets/158379d3-4f4f-43f3-b83d-46c6aa442f3d" />


### PREPROCESSING
### Procedure:
<img width="1600" height="900" alt="WhatsApp Image 2026-10-31 at 2 10 05 PM" src="https://github.com/user-attachments/assets/1e51b333-f949-4b4f-9759-1aa594848226" />
<img width="1228" height="737" alt="WhatsApp Image 2026-10-31 at 2 10 15 PM" src="https://github.com/user-attachments/assets/04fe5c93-012f-4656-9831-0777b1915449" />

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
<img width="1600" height="900" alt="WhatsApp Image 2026-10-31 at 2 10 49 PM" src="https://github.com/user-attachments/assets/771ffd61-7f48-4ebc-b109-0eb9f1168c39" />
<img width="1232" height="738" alt="WhatsApp Image 2026-10-31 at 2 10 58 PM" src="https://github.com/user-attachments/assets/70150ccb-0725-4ee6-aa22-ec23a90b3efb" />

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
<img width="1600" height="900" alt="WhatsApp Image 2026-10-31 at 2 11 20 PM" src="https://github.com/user-attachments/assets/94f1f120-36ab-4444-adfa-10c37fd13876" />
<img width="1225" height="733" alt="WhatsApp Image 2026-10-31 at 2 11 34 PM" src="https://github.com/user-attachments/assets/f8415507-e685-4be5-b334-da044aae9085" />

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
### RESULT: 
  Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
