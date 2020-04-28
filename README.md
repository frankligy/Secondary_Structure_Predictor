# Secondary_Structure_Predictor
A KNN model to predict protein secondary structure using its primary sequence

# What is it used for?
This is initially designed for Intro to Bioinformatics Course homework to use KNN model to predict protein secondary structure. Given a protein amino acid sequence, it is able to predict its secondary structure with the accuracy around 50%. Again, KNN itself is just a very primitive model. 

# How to use?
### Dependencies
* python3
* numpy
* scikit-learn
* scipy
* matplotlib

### Change we need to make
Just change the input file path (training data) accordingly, the input file is underneath `if __name__ = '__main__'` statement, it is easy to spot.

### Run code in your terminal
```
python3 protein_secondary_structure_predictor.py -l 5 -k 3 -m kdTree -v distance
```

### Obtain help Information
```
python3 protein_secondary_structure_predictor.py -h
```

### All parameters
```
-l –length : length of sliding window, you could pick 5,7,9,11
-k –k      : K nearest neighbors, increasing k will result in longer runtime 
-m –mode   : bruteForce or kdTree, it is discouraged to use bruteForce 
-v –vote   : distance or uniform
-h –help   : check help information
```


# More information
Refer to /docs/secondaryStructure.pdf for more information

# Contact
<li2g2@mail.uc.edu>
Guangyuan(Frank) Li, PhD student, Biomedical Informatics Program, Cincinnati Children's Hospital Medical Center


