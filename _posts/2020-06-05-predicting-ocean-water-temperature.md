---
title: "Predicting ocean water temperature with machine learning"
author: "Bilgenur Baloglu"
layout: post
categories: blog
tags: [machine learning, ocean, biodiversity]
image: GOPR1495.jpg
display_img: True
link_url: True
url: https://towardsdatascience.com/tackling-climate-crisis-with-machine-learning-d9426fe1f5a9
---

<hr style="margin-left: auto; margin-right: auto; width: 60%; color: #f2f2f2">

After finishing up my 2 courses on Data Science [Udemy](https://www.udemy.com/) and Machine Learning also on Udemy, I am currently taking Deep Learning with PyTorch: Zero to GANs with [Jovian.ml and freeCodeCamp](https://jovian.ml/forum/c/pytorch-zero-to-gans/18) and it was finally the time I tried my hands at building an ML model over the last two weeks.

I used 60 years of oceanographic data, hosted on [Kaggle](https://www.kaggle.com/sohier/calcofi) to predict ocean water temperature. This project turned out to be very timely, as this is the National Ocean Month and Trump happened to sign an executive order lifting protections from the US coastal line.

For the water temperature algorithm, I built a linear regression model with a batch size of 32, calculated average losses, used gradient descent to improve the model. The temperature prediction is very close to the actual values :) I can't wait to fine-tune my model!

Take a look at my [Medium article](https://towardsdatascience.com/tackling-climate-crisis-with-machine-learning-d9426fe1f5a9) that got published under Towards Data Science
and my model at [Jovian.ml](https://jovian.ml/bbaloglu/water-temp-predictor-2).  
