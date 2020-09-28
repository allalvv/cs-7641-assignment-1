# CS-7641 Supervised Learning

URL for code
https://github.com/srpatel625/cs-7641-assignment-1

This project implements the following 5 different learning algorithms on two different datasets:
- Decision Tree Classifier
- Neural Networks
- k-nearest neighbors
- Boosting (ADABoost)
- SVM with a rbf kernel function
- SVM with an sigmoid kernel function

Code that was borrowed from stack overflow is cited in the comments. 

## Getting Started

### Installing dependencies and running experiments

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

## Built With

* Python 3.6
* Pandas
* Numpy
* Matplotlib
* sklearn
* yellowbrick

## Authors

* **Sarin Patel** 
