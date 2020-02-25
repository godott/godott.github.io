---
layout: post
title: "Feature map, reproducing kernel Hilbert space and quantum machine learning"
author: "Yunong Shi"
comments: true
---

I just discovered two recent papers on doing machine learning in quantum space. This blog is basically my read on the simple but elegant idea presented in these two papers. In these two work, the authors essentially associated kernel space for ML tasks with quantum Hilbert space. This is an idea that is so straightforward that makes you wonder why it was not the first thought when people combines machine learning with quantum computing. After all, they both are called "Hilbert
space".

Okay, let's get down to the details. The goal is to classify (or make predication on) data in a data set with some of the known data points labelled. A simple example will be a set of points on a plane painted green and red. The easist way to paint unknown points would be using a straight line to separate known red points from knwon green points and guess that all the unknown red points will stay on the red side and same for green. However, it is not always possible to separate the known data points with a
straight line. For this to work, a natural thing is to map them onto a higher-dimensional space then we could probably use a hyper-plane to separate them (or at least calculate the distance between points).
