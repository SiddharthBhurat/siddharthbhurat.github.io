---
title: "Meta Learning Model: Model that learns about Models"
excerpt: "Pytorch, MNIST, CNN<br/><img src='/images/meta_learning_model.png'>"
collection: portfolio
---

<!-- <video width="560" height="315" controls>
  <source src="/images/drone_vid.mp4" type="video/mp4">
</video> -->
<!-- <center>
  <video width="560" height="315" controls>
    <source src="/images/drone_vid.mp4" type="video/mp4">
  </video>
</center> -->
<img src="/images/meta_learning_model.png" alt="" style="display: block; margin: 0 auto;">

* In this project we attempt to uncover patterns within the black box of neural networks by training a meta-classifier. 
* A solid understanding of these inner workings could lead to vast improvements in performance, and increase our confidence that a given model is behaving as we expect. 
* Our approach consists of first training many binary classifiers on the MNIST dataset, then using this collection of models as a dataset for a meta-model. This meta-model takes weights of an MNIST classifier as input, and classifies them according to which number they were trained to identify. 
* After much experimentation, we were unable to achieve satisfactory results from the meta-model, but came away with many insights on how to approach the problem in the future.
