# WDM-Ex.NO-1C-WEATHER-TABLE-PREPROCESSING-IN-WEKA
## Name: Gowtham S
## Reg.no: 2305002008
## Aim:
To apply Pre-Processing techniques to the training data set of Weather Table.
## Description:
Real world databases are highly influenced to noise, missing and inconsistency due to their queue size so the data can be pre-processed to improve the quality of data and missing results and it also improves the efficiency.
There are 3 pre-processing techniques they are:
1)	Add
2)	Remove
3)	Normalization
## Procedure:
1)	Open Start → Programs → Accessories → Notepad
2)	Type the following training data set with the help of Notepad for Weather Table.

```@relation weather
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
3)	After that the file is saved with .arff file format.
4)	Minimize the arff file and then open Start → Programs → weka-3-4.
5)	Click on weka-3-4, then Weka dialog box is displayed on the screen.
6)	In that dialog box there are four modes, click on explorer.
7)	Explorer shows many options. In that click on ‘open file’ and select the arff file
8)	Click on edit button which shows weather table on weka.
 
Training Data Set  Employee Table
<img width="735" height="786" alt="image" src="https://github.com/user-attachments/assets/9c0dd364-f03c-4215-959c-7ca5b3589abf" />

## Add Pre-Processing Technique:
Procedure:
1)	Start  Programs  Weka-3-4  Weka-3-4
2)	Click on explorer.
3)	Click on open file.
4)	Select Weather.arff file and click on open.
5)	Click on Choose button and select the Filters option.
6)	In Filters, we have Supervised and Unsupervised data.
7)	Click on Unsupervised data.
8)	Select the attribute Add.
9)	A new window is opened.
10)	In that we enter attribute index, type, data format, nominal label values for Climate.
11)	Click on OK.
12)	Press the Apply button, then a new attribute is added to the Weather Table.
13)	Save the file.
14)	Click on the Edit button, it shows a new Weather Table on Weka.
 
## Weather Table after adding new attribute CLIMATE:
<img width="997" height="603" alt="image" src="https://github.com/user-attachments/assets/c6e10136-bce7-4296-8ee9-7682eb70cb92" />
## Remove Pre-Processing Technique:
Procedure:
1)	Start  Programs  Weka-3-4  Weka-3-4
2)	Click on explorer.
3)	Click on open file.
4)	Select Weather.arff file and click on open.
5)	Click on Choose button and select the Filters option.
6)	In Filters, we have Supervised and Unsupervised data.
7)	Click on Unsupervised data.
8)	Select the attribute Remove.
9)	Select the attributes windy, play to Remove.
10)	Click Remove button and then Save.
11)	Click on the Edit button, it shows a new Weather Table on Weka.
 
## Weather Table after removing attributes WINDY, PLAY:
<img width="1046" height="510" alt="image" src="https://github.com/user-attachments/assets/1d80041b-8dbf-408d-b538-5abb9968294e" />

## Normalize Pre-Processing Technique:
Procedure:
1)	Start → Programs  →  Weka-3-4 → Weka-3-4
2)	Click on explorer.
3)	Click on open file.
4)	Select Weather.arff file and click on open.
5)	Click on Choose button and select the Filters option.
6)	In Filters, we have Supervised and Unsupervised data.
7)	Click on Unsupervised data.
8)	Select the attribute Normalize.
9)	Select the attributes temparature, humidity to Normalize.
10)	Click on Apply button and then Save.
11)	Click on the Edit button, it shows a new Weather Table with normalized values on Weka.
 
## Weather Table after Normalizing TEMPARATURE, HUMIDITY:
<img width="1047" height="375" alt="image" src="https://github.com/user-attachments/assets/72a7f3ae-cadd-4154-80e2-4d120f659af4" />

 ## Result:
Thus this program has been successfully executed.


