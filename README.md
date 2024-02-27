### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:

## Training Data Set -> Buying Table:

![img2a 1](https://github.com/ragulmani936/WDM_EXP2/assets/94881918/38ff2be6-506c-4dad-b9b4-7ac80efa883f)

## Training Data Set -> Banking Table:

![img2b 1](https://github.com/ragulmani936/WDM_EXP2/assets/94881918/ce948c7f-46c1-49c9-b9f3-903379d7efc2)

## Training Data Set -> Employee Table:

![img2c 1](https://github.com/ragulmani936/WDM_EXP2/assets/94881918/d37e7e8f-d1d8-4e40-b21e-c2f3715286ef)


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:

## Buying Table:

![img2a 2](https://github.com/ragulmani936/WDM_EXP2/assets/94881918/06de03c6-00b4-43c2-a739-69d118e29b1d)

## Banking Table:

![img2b 2](https://github.com/ragulmani936/WDM_EXP2/assets/94881918/6321c13d-e77b-4493-bdc7-ed3b58c4d089)

## Employee Table:

![img2c 2](https://github.com/ragulmani936/WDM_EXP2/assets/94881918/2f6ea8c9-fc81-4f35-ae47-10ed14c600ee)


### RESULT: 

Thus this program has been successfully executed.
