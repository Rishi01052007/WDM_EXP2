### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 19.11.26
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
@relation MarketBasket

@attribute Bread {t,f}
@attribute Butter {t,f}
@attribute Milk {t,f}

@data
t,t,t
t,t,f
t,f,t
t,t,t
t,f,t
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:

<img width="281" height="192" alt="Screenshot 2026-11-19 122418" src="https://github.com/user-attachments/assets/a3784b53-1ddc-4f0f-810e-3187fdf862e9" />


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:

<img width="1917" height="1197" alt="Screenshot 2026-11-18 155532" src="https://github.com/user-attachments/assets/0f7a8e65-383f-4dfa-97a5-5aebc31721e8" />


### RESULT: 

Hence , Generating Association Rules for Employee dataset using Apriori Algorithm has been done successfully
