# Confounder Filtering Method

Example implementation of this paper:

H. Wang, Z. Wu and E. P. Xing, [Removing Confounding Factors Associated Weights in Deep Neural Networks Improves the Prediction Accuracy for Healthcare Applications](https://psb.stanford.edu/psb-online/proceedings/psb19/wang.pdf), Proceedings of 24th Pacific Symposium on Biocomputing (PSB 2019).

## Method Introduction

Confounder filetering (CF) method is an interesting method that helps to improve the generalization of neural networks by removing the weights that are associated with confounding factors. In contrast to many methods that work with the representation learned through the data, we directly work with the weights that will result in the representation. 


## File Structure:

* vanilla/ example files of the baseline vanilla CNN
* CF/ example files of CF method
* By comparing the differences between these two files, one should have a better idea about how to plugging CF method into an arbitrary model. 


## Contact
[Haohan Wang](http://www.cs.cmu.edu/~haohanw/)

[@HaohanWang](https://twitter.com/HaohanWang)
