# Project Title

This program is made using python code, and explores 4 methods in solving the problem of lexical normalisation in the context of twitter data. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

Make sure you have Python 3 installed on your system, and the jellyfish library installed. 
```
pip install jellyfish
```

### Running The Program

Make sure you run the python file in the same directory as the data files (correct.txt, misspell.txt, dict.txt). In this example "Project1" is the folder. 

```
C:/Users/Danial/Anaconda3/python.exe c:/Users/Danial/OneDrive/KnowledgeTechnologies/Project1/Project1.py
```

Running the above will get this message, requiring user input (based on method you want)

```
Which Algorithm method would you like to use? (0 for                             Levenshtein Only, 1 for Levenstein + Soundex, 2                            for Soundex + Levenstein, 3 for Soundex Only):
```
After inputting your method, the programme will be processed and the output will be created in the same folder. The output will be a csv file with associated number of the method as its name. For example:

```
#Output for Levenshtein: 
'0_method.csv'
#Output for Levenstein + Soundex:
'1_method.csv'  
#...etc...
```


