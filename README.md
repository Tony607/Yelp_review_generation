# [How to generate realistic yelp restaurant reviews with Keras](https://www.dlology.com/blog/how-to-generate-realistic-yelp-restaurant-reviews-with-keras/)

TL; DR

You will be able to build a model to generate 5-star Yelp reviews like those.

_Samples of generated review text (unmodified)_
```
<SOR>I had the steak, mussels with a side of chicken parmesan. All were very good. We will be back.<EOR>
<SOR>The food, service, atmosphere, and service are excellent. I would recommend it to all my friends<EOR>
<SOR>Good atmosphere, amazing food and great service.Service is also pretty good. Give them a try!<EOR>
```
## How to Run
Require [Python 3.5+](https://www.python.org/ftp/python/3.6.4/python-3.6.4.exe) and [Jupyter notebook](https://jupyter.readthedocs.io/en/latest/install.html) installed
### Clone or download this repo
```
git clone https://github.com/Tony607/Yelp_review_generation
```
### Install required libraries
`pip3 install -r requirements.txt`

If you are only interested in playing with the trained model to generation reviews.
Download the trained model weight from the releases, [pre-trained.hdf5](https://github.com/Tony607/Yelp_review_generation/releases/download/V0.1/pre-trained.hdf5).
Put it to the root of the project directory.

### Start to generate reviews
In the project start a command line run
```
jupyter notebook
```
In the opened browser window open
```
notebooks/3_Generate_Review.ipynb
```

Optionally if you want to learn about data preparation and model training. Continue on with my [write up](https://www.dlology.com/blog/how-to-generate-realistic-yelp-restaurant-reviews-with-keras/).


Happy coding! Leave a comment if you have any question.