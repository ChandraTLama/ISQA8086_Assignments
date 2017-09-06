# Amazon Web review on Android apps product

This data set consists  of reviews from amazon on Apps for android. As per the information on data set from [https://snap.stanford.edu/data/web-Amazon.html](https://snap.stanford.edu/data/web-Amazon.html)
data span a period of 18 years, including reviews upto March 2013. Reviews have information about product, helpful ratings, review text, overall rating and summary.
This data is downloaded from [http://jmcauley.ucsd.edu/data/amazon/](http://jmcauley.ucsd.edu/data/amazon/) and it is only the small subset of data for the class project.


## About Data

* Size: 329,483 KB KB
* Format: JSON Files with 752,937 reviews.
* Sample Column Header :
	*reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B
	*asin - ID of the product, e.g. 0000013714
	*reviewerName - name of the reviewer
	*helpful - helpfulness rating of the review, e.g. 2/3
	*reviewText - text of the review
	*overall - rating of the product
	*summary - summary of the review
	*unixReviewTime - time of the review (unix time)
	*reviewTime - time of the review (raw)	


### File to Download
Since the data is larger than 100 MB that github allow to upload, data on food event can be downloaded from [http://jmcauley.ucsd.edu/data/amazon/](http://jmcauley.ucsd.edu/data/amazon/) and under "Small" subsets for experimentation we can choose Apps for Android. 

## License
SNAP is distributed under the BSD license. This means that it is free for both academic and commercial use. Note however that some third party components in SNAP require that you reference certain works in scientific publications.

You are free build your code on top of SNAP. If do so, please reference (cite) SNAP and this website. We appreciate bug fixes and would be happy to include new modules in SNAP.

Refer the license details on [https://snap.stanford.edu/snap/license.html](https://snap.stanford.edu/snap/license.html)

## Potential User and Decision Maker

Potential data user can be public, App developers, marketing personnels, product designer etc.  Decision Maker can be the project/product manager, Research and design department of any product/application development company, business or concumer analyst.

## Questions that might be answered

* Correlation of product and customer ratings.
* Determine what kind of reviews are helpful for other customers
* What kind of product can have good ratings and how it can be used to predict for future reviews.

## Citation

R. He, J. McAuley, Ups and downs: Modeling the visual evolution of fashion trends with one-class, WWW, 2016
J. McAuley, C. Targett, J. Shi, A. van den Hengel, Image-based recommendations on styles and substitutes, SIGIR, 2015
J.Leskovec, A. Krevl, SNAP Datasets, Standford Large Network Dataset Collection, Jun 2014, Retrieved from [http://snap.stanford.edu/data](http://snap.stanford.edu/data)
