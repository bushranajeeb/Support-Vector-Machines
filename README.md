# Support-Vector-Machines

In the first half of this exercise, you will be using support vector machines (SVMs) with various example 2D datasets. Experimenting with these datasets will help you gain an intuition of how SVMs work and how to use a Gaussian kernel with SVMs. In the next half of the exercise, you will be using support vector machines to build a spam classifier.
The provided script, ex6.m, will help you step through the first half of the exercise.

Throughout the rest of this exercise, you will be using the the script ex6 spam.m. The dataset included for this exercise is based on a a subset of the SpamAssassin Public Corpus.Many email services today provide spam filters that are able to classify emails into spam and non-spam email with high accuracy. In this part of the exercise, you will use SVMs to build your own spam filter. You will be training a classifier to classify whether a given email, x, is spam (y = 1) or non-spam (y = 0). In particular, you need to convert each email into a feature vector x 2 Rn. The following parts of the exercise will walk you through how such a feature vector can be constructed from an email.
