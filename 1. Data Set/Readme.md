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

**Path:** It is the ID of a class.

**CBO (Coupling Between Object) [2]:** A class is coupled to another one if it used its member functions and/or instance variables. CBO provides the number of classes to which a given class is coupled. Range: 0 - 162

**CC (Cyclomatic Complexity) [3]:** It is a software metric used to indicate the complexity of a program. It is a quantitative measure of the number of linearly independent paths through a program's source code. Range: 0 - 488.0

**DIT (Depth of Inheritance Tree) [2]:** It is defined as the maximum depth of the inheritance graph of each class. Range: 0 - 7

**LCOM (Lack of Cohesion on Methods) [2]:** This is the number of pairs of member functions without shared instance variables, minus the number of pairs of members functions with shared instance variables. Range: 0 - 1

**LOC:** Number of lines of codes. Imports and comments are not included. Range: 0 - 1369

**NOC (Number Of Children) [2]:** It is the number of direct descendants for each class. Range: 0 - 189

**RFC (Response For a Class) [2]:** This is the number of methods that can potentially be executed in response to a message received by an object of that class. Range: 0 - 413

**WMC (Weighted Methods per Class) [2]:** It is the number of methods of a class.Range: 0 - 56

**class_frequency:** It is the number of appearences that the class has through all the releases. Range: 0 - 8

**will_change:** It is the dependent variable, the indicator of a class change prone.

**number_of_changes:** It is the number of changes that a class suffered through all the releases. Range: 0 - 7

**change_probability:** It is the number of changes divided by the class frequency. Range: 0 - 1


### References

[1] Lu, H., Zhou, Y., Xu, B., Leung, H., and Chen, L. (2012). The ability of object-oriented metrics to predict change-proneness: a meta-analysis. Empirical Software Engineering, 17(3)

[2] S. R. Chidamber and C. F. Kemerer, "A metrics suite for object oriented design," in IEEE Transactions on Software Engineering, vol. 20, no. 6, pp. 476-493, June 1994.

[3] T. J. McCabe, "A Complexity Measure," in IEEE Transactions on Software Engineering, vol. SE-2, no. 4, pp. 308-320, Dec. 1976.
