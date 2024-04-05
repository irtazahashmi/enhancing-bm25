# Setup and Introduction

## Create a virtual environment

Create a virtual enviroment to make sure the dependencies of each project is kept seperate. To create a virtual environment _venv_, run the following command:

```console
$ python3 -m venv venv
```

Activate the vitual environment _venv_ using the following command:

```console
$ source ./venv/bin/activate
```

## Install requirements

To download the project requirements, run the following command:

```console
$ python3 -m pip install -r requirements.txt
```

## How to play with the code
You can train a Word2Vec model with `word2vec.ipynb` and achieve better performance with our proposed and
implemented learning-to-rank method with `ltr.ipynb`. 

We also tried cross validation for hyperparameter tuning for different
threshold values. Since cross-validation
didn't yield satisfactory results, we didn't include this part into our main functions and files but
added it into a separate notebook `word2vec_crossval.ipynb`.


## Contact
Feel free to contact us at:
- Kanish Dwivedi - [K.Dwivedi-1@student.tudelft.nl](mailto:K.Dwivedi-1@student.tudelft.nl)
- Dylan Durand - [D.R.Durand@student.tudelft.nl](mailto:D.R.Durand@student.tudelft.nl)
- Irtaza Hashmi - [I.Hashmi@student.tudelft.nl](mailto:I.Hashmi@student.tudelft.nl)
- Pengzhi Yang - [P.Yang-4@student.tudelft.nl](mailto:P.Yang-4@student.tudelft.nl)
