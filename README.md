# ITADATAhack 2023 Project: Classification of European Union Laws into Chapters and Subchapters

The code produced by my team and myself allowed us to reach second place in the final classification of the ITADATAhack 2023, organised by Open Data Playground.

The event will be open to teams of students from Italian Universities and will be focussed on a multi-label classification and data storytelling task. 
The goal is to engage students in a competition that allows them to showcase their skills in data analysis and modelling, by playing with real datasets.
By participating in ITADATAhack 2023 as a player, you will be able to analyse unique data about the Italian STEM market, and work innovatively with your team members.
By sponsoring ITADATAhack 2023 competition, you will be able to increase the visibility of your brand within the Italian STEM community.

# Day 1

## About the problem 

The problem will ask you to create a classification of legal documents representing laws in force in the European Union (EU) with respect to the directory they belong to.
The "Directory of legal acts", i.e. the hierarchy of rules in force in the EU, includes 20 main chapters:
Each chapter is divided into sub-chapters at various levels. The chapters have been coded with integers from 1 to 20 and represent the target of the classification, which must process the text of the law and/or the normative references and predict the chapter to which it belongs.

## Solution: Classification of Laws in 20 Chapters

- On the first day of the challenge, we tackled the classification of laws into 20 main chapters.
- We used textual analysis techniques, natural language processing (NLP) and a machine learning algorithm to assign each law to the corresponding chapter.
- The content of the work can be found in the file PA.ipynb.
- The predictions produced are in the file PA.csv.

# Day 2
## About the problem 
The problem will ask you to create a classification of legal documents representing laws in force in the European Union (EU) with respect to the directory they belong to.
The "Directory of legal acts", i.e. the hierarchy of rules in force in the EU, includes 20 main chapters, divided into various sub-chapters:
The sub-chapters at depth 2 have been coded with strings separated by a hyphen (for example '01-07', '02-10') which represent the target of the classification, the purpose of which is to process the text of the law and/or the regulatory references and predict the sub-chapter it belongs to.

## Solution: Classification of Laws into Chapters and Sub-Chapters

- On the second day, we took our project to the next level. In addition to the classification of the main chapters, we implemented the division of laws into sub-chapters. Each law was assigned to a main chapter and a specific sub-chapter.
- The content of the work can be found in the MLP.ipynb file.
- The predictions produced are in the MLP.csv file.

# Day 3:
## About the problem: 
The problem will ask you to create a classification of legal documents representing laws in force in the European Union (EU) with respect to the subdirectories to which they belong.
The "Directory of legal acts", i.e. the hierarchy of rules in force in the EU, includes 20 main chapters, divided into various sub-chapters.
The sub-chapters at depth 2 have been coded with strings separated by a hyphen (for example '01-07', '02-10') which represent the target of the classification, whose purpose is to process the law text and predict the sub-chapters of membership. In this case, we are dealing with a multilabel classification problem, given that each law can be included in several sub-chapters and the belonging of a law to a sub-chapter is not exclusive.

## Solution: Classification of Laws into Multiple Subchapters

- On the third day, we further improved the classification system. Now each law can belong to more than one sub-chapter, allowing for a more detailed and flexible categorisation of laws.
- The content of the work can be found in the file CS.ipynb.
- The forecasts produced are in the CS.csv file.
  
## Tools Used

- Python
- NLP libraries 
- Machine Learning Algorithms
- Jupyter Notebook for data analysis and visualisation

## How to Execute the Code

- Clone this repository on your computer.
- Make sure you have all dependencies and libraries installed.
- Run Jupyter Notebooks to perform analysis and classification.

## Contributions

We are open for contributions and suggestions to improve this project. If you have ideas or improvements to share, feel free to open an "issue" or send a "pull request".

## Acknowledgements

A big thank you to my colleagues, Rosaria Leone and Raffaele Ferriero, for their support and collaboration in this project.

Good work and good coding!
