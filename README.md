# Naive Bayes Classifier

This program is an animal classifier following the Naive Bayes' theorem. Bayes’ Theorem provides a way that we can calculate the probability of a piece of data belonging to a given class, given our prior knowledge.

In the training data, we have the height and length for 10 dogs, 10 horses and 10 elephants corresponding to our three classes: `Dog`, `Horse` and `Elephant`. By suplying the height and length of an animal that we would like to classify, we can predict if an animal is a dog or horse or an elephant. 

## Technologies

* Python 2.7 and above

## Setup

* Run `git clone` this repository and `cd` into the project root.
* Run `python naive_bayes_classifier.py HEIGHT LENGTH` on command prompt. `HEIGHT` and `LENGTH` are the height and length of the animal that we would like to classify. They are of float data type. Example of `dog` height and length is `0.58` `1.29`

------

```
Average height of a dog: 0.5 - 0.67 ft

Average length of a dog: 1.17 - 1.5 ft

Average height of a horse: 4.7 - 6 ft

Average length of a horse: 7 - 9 ft

Average height of an elephant: 10 - 12 ft

Average length of an elephant: 18 - 21 ft
```

