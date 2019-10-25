---
layout: post
title: "Part 1 (Analogy): What is Modeling?"
author: al
---
So you might be wondering how prediction is done in Data Science, right? On tasks such as predicting the price of a commodity, the next-best product to recommend, etc. Or if you use Facebook, then likely you've been notified to tag that lovely face of your friend in your photo. If you use Youtube, then maybe you have tried using *auto-generated subtitle/caption*. Oh, so you are using iPhone, then maybe you are using Face ID to unlock your phone. All these, work by doing prediction --- predicting the next caption, predicting the face in the image, etc. 

Again the question is, how does it work? Well, all of these are based on **Modeling**, and to understand this, we will use an analogy. You should be a fan of *Kapamilya* shows to relate to the following example. Specifically, the **Your Face Sounds Familiar** segment. Consider the following illustration:
<!-- more -->

<img src="{{ site.baseurl }}/assets/img/img1.png">
We have here Adam Lavine and Michael Pangilinan and our goal is to predict how Adam sings; how he walks; how he dances, maybe a Bahay Kubo or Gangnam Style; how he eat Tahoh, etc. Bottomline, we want to have Adam's characteristics, but we don't want to hire him just for that purpose because we don't have money for that, rather we want someone to represent him. We will call this someone as our *model*, and we need to <span style="color:red;"><b>identify</b></span> it. In this case, because Adam is male, so we need a male model, and that would be Michael. From the illustration, we will refer to Adam as our main *target*, and we want to <span style="color:red;"><b>train</b></span> our *model* to have the characteristics of our target, so that we can make <span style="color:red;"><b>prediction</b></span> (i.e. dancing Bahay Kubo) out of it.

To acheive Adam's persona, we need to adjust the <span style="color:red;"><b>parameters</b></span> we have in Michael's form, our model. That is, we need to adjust *the tattoos, the hair, the skin tone, the posture, and even the mannerism*. Once we have that, we can then make prediction. After training, we should at least achieve the following:

<img src="{{ site.baseurl }}/assets/img/img2.png">
In this case, we have a minimal error already since we've captured some of the parameters, including the tattos, hair, etc. as opposed to the untrained *model* in the first figure.
## Prediction and End Note
At this point, we can now make prediction. We'll just let the *trained*-Michael to dance, sing, etc. and what we get out of it is the best prediction we can have for Adam's persona. That's it! Stay-tuned, in the next article we'll relate this concept to doing Data Science. Specifically, we'll focus on the texts highlighted in red above, namely: **identify**, **train**, **prediction**, and **parameters**.

## Disclaimer
The photos used are neither owned by the author and his employer, rather these were taken from Google Image Search and are credited to the owners.