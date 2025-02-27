## EX1: Creation of Employee, Weather dataset in WEKA Data Mining and Analysis Tool and perform Preprocessing
### DATE:

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


### Employee Data:
![{B83088A0-878B-422A-A150-70769A277A7A}](https://github.com/user-attachments/assets/934c463b-5f3a-4f44-8b5d-d389f4bebbf2)



### Weather Data:
![{E5D0A9F9-6FA9-43B8-8DC7-B03B30532B31}](https://github.com/user-attachments/assets/047fbcbd-3e60-43e8-9e34-5fb6c18c2bb3)



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

### Employee Data:
![{9D82F615-E796-493F-A7F3-F12D99542018}](https://github.com/user-attachments/assets/7fe1e7d8-b18c-40f8-bd7a-a0fe5b0d672e)



### Weather Data:
![{2E1F3212-580B-4F90-9B61-46BE208CEB28}](https://github.com/user-attachments/assets/f86df930-ce7e-4934-bfbb-43323df9bb5c)




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

### Employee Data:
![{139657ED-5495-4B5E-9E4D-DE28A75212E6}](https://github.com/user-attachments/assets/8f8c51fc-a3a4-4e21-b537-32a17b12107a)



### Weather Data:
![{FC473B50-1AC0-4956-8D07-F5B92EF89C32}](https://github.com/user-attachments/assets/1c4464a3-9805-47a1-99c3-76ec7eddc48e)




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

### Employee Data:
![{76A99BCC-555D-445B-A663-7333CBD49DB0}](https://github.com/user-attachments/assets/0ed919a9-3a88-454e-b6d7-5278add3adec)



### Weather Data:
![{9631DA9C-54FF-4994-A588-F91C7FBC00D1}](https://github.com/user-attachments/assets/03593074-5e3a-40b2-be3f-df2c5bf1b262)





### RESULT: 
Thus the program for generating employee and weather datasets has been developed, and preprocessing has been accomplished successfully.
