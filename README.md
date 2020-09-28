# CS-7641 Supervised Learning

This project implements the following 5 different learning algorithms on two different datasets:
- Decision Tree Classifier
- Neural Networks
- k-nearest neighbors
- Boosting (ADABoost)
- SVM with a rbf kernel function
- SVM with an sigmoid kernel function

Packages used include pandas, numpy, matplotlib, sklearn, and yellowbrick.

Code that was borrowed from stack overflow is cited in the comments. 

## Getting Started

### Prerequisites

Use python 3.6
Run the following commands to install requirements in a virtual or conda environment and run the experiments. 

```
pip install -r requirements.txt

python main.py --all
```

You can also individually run the experiments as shown below

```
python main.py -e dt
python main.py -e nn
python main.py -e knn
python main.py -e ada
python main.py -e svm
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Authors

* **Sarin Patel** 