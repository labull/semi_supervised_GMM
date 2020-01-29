# Semi-supervised Gaussian Mixture Model [MATLAB]

* Semi-supervised Gaussian Mixture Model, for density estimation and classification, implemented in MATLAB.
* The code reproduces the example from this [MSSP paper](link).

If you find any bugs/errors, get in contact via the issues tab.

*Dependencies*: [Mo Chen's](https://github.com/sth4nth) log-Pdf code; the required functions are in their own folder (MoChen_logPdf) within this repo, I do not claim ownership of these functions.

## Demo Script
The script illustrates the potential increase in classification performance through semi-supervised model updates. Outputs of the script are shown below (3% of the training data are labelled).

### Conventional supervised learning

(blue ellipse indicates the prior)

![](images/supervised.png?raw=true)

Leads to classification accuracy: 88%

### Semi-supervised learning

(blue ellipse indicates the prior)

![](images/semisupervised.png?raw=true)

Leads to classification accuracy: 94%

(accuracy increase: 6.36%)
