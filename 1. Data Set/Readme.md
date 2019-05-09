# Change Proneneness Prediction Data Set

### General Information

Data Set Characteristics: Multivariate

Associated Tasks: Classification

Number of Instances: 4183

Number of Attributes: 8

Missing Values? No

Area: Software Engineering

### Source

Cristiano Sousa Melo

Matheus Mayron Lima da Cruz

Antônio Diogo Forte Martins

Tales Matos

José Maria da Silva Monteiro Filho

Javam de Castro Machado

### Data Set Information

* The data set of this work is generated from the backend source code of a WEB application started in 2013, and until 2018 were collected 8 releases to analyze change-prone classes
* The dependent variable "will change" has obtained according to [1]
* The dependent variable "will change" is imbalanced, containing 3871 "not change" (0) labels and 312 "will change" (1) label


### Attribute Information

Path: It is the ID of a class.

CBO: 

CC:

DIT:

LCOM:

LOC:

NOC:

RFC:

WMC:

class_frequency: It is the number of appearences that the class has through all the releases.

will_change: It is the dependent variable, the indicator of a class change prone.

number_of_changes: It is the number of changes that a class suffered through all the releases.

change_probability: It is the number of changes divided by the class frequency.


### References

[1] Lu, H., Zhou, Y., Xu, B., Leung, H., and Chen, L. (2012). The ability of object-oriented metrics to predict change-proneness: a meta-analysis. Empirical Software Engineering, 17(3)
