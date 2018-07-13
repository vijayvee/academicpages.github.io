---
title: "Automated Continuous Behavioral Monitoring using Inception3D"
excerpt: "I worked with Dr. Justin Fallon on an automated behavioral monitoring system to complement research in diagnosing neuromotor diseases through video analysis using deep learning.
<br/><br/><img src='/files/acbm.png'>"
collection: portfolio
---

* Developed this system capable of automating tons of manual work, right from synchronously recording days of video data of a couple dozen mice, transferring the data efficiently to a compute cluster, and calculating several behavioral statistics using a mix of computer vision and deep learning techniques.
* Finetuned Inception3D, a state-of-the-art action recognition model pretrained on the Kinetics dataset, on the task of behavior recognition for mice.
* Obtained a behavior recognition accuracy of 89%, which is a significant boost from the previous model's accuracy of 79% on a large in-house mouse behavior recognition dataset with 144 hours of video content.
* I have opensourced my TensorFlow implementation of this project on my GitHub profile in this repository: [Code link](https://github.com/vijayvee/behavior-recognition)

<video width="640" height="480" controls autoplay loop>
  <source src="/files/output_behav.mp4" type="video/mp4">
Your browser does not support the video tag.
</video>
