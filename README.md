# Handwriting Recognition

----

## K-Means clustering on the [`scikit-learn`](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_digits.html) digits dataset

----

#### Contains;

```angular2html
`handwriting.ipynb` - Main analyis in jupyter notebook

`test.html` - Renders a handwriting sample as 8x8 array

`JsCode.js` - Javascript code that produces your handwriting
```
----

### Original Source

[Optical Recognition of Handwritten Digits Data](https://archive.ics.uci.edu/ml/datasets/Optical+Recognition+of+Handwritten+Digits)

```angular2html
Data Set Information:

We used preprocessing programs made available by NIST to extract normalized bitmaps of handwritten digits. 
From a total of 43 people, 30 contributed to the training set and a different 13 to the test set. 

32x32 bitmaps are divided into nonoverlapping blocks of 4x4 and the number of on pixels are counted in each block. 

This generates an input matrix of 8x8 where each element is an integer in the range 0..16. 
This reduces dimensionality and gives invariance to small distortions. 
```