# Quantifying Facial Age by Posterior of Age Comparisons
Yunxuan Zhang, Li Liu, Cheng Li, Chen Change Loy

# Abstract

We introduce a novel approach for annotating large quantity of in-the-wild facial images with high-quality posterior age distribution as labels. Each posterior provides a probability distribution of estimated ages for a face. Our approach is motivated by observations that it is easier to distinguish who is the older of two people than to determine the person’s actual age. Given a reference database with samples of known ages and a dataset to label, we can transfer reliable annotations from the former to the latter via human-in-the-loop comparisons. We show an effective way to transform such comparisons to posterior via fully-connected and SoftMax layers, so as to permit end-to-end training in a deep network. Thanks to the efficient and effective annotation approach, we collect a new large-scale facial age dataset, dubbed ‘MegaAge’, which consists of 41, 941 images. With the dataset, we train a network that jointly performs ordinal hyperplane classification and posterior distribution learning. Our approach achieves state-of-the-art results on popular benchmarks such as MORPH2, Adience, and the newly proposed MegaAge.

# Dataset

MegaAge dataset link: https://www.dropbox.com/s/mnk4p75hqk6jtbw/megaage.zip?dl=0

MegaAge asian dataset link: https://www.dropbox.com/s/x0gyfp12tozivjh/megaage_asian.zip?dl=0


# Code
Coming soon

# Ref
@inproceedings{huang2016unsupervised,
 author = {Yunxuan Zhang and Li Liu and Cheng Li and Chen Change Loy},
 title = {Quantifying Facial Age by Posterior of Age Comparisons},
 booktitle = {British Machine Vision Conference (BMVC)},
 year = {2017}}
