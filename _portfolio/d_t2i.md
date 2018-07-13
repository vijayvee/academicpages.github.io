---
title: "Generative adversarial text to image synthesis"
excerpt: "I implemented a conditional GAN that generates images of flowers that plausibly match the input textual descriptions of the flowers.
<br/><br/><img src='/files/t2i_1.png'>"
collection: portfolio
---

* Based on [Reed et al.](https://arxiv.org/abs/1605.05396), I developed a conditional Generative Adversarial Network that takes as input, a natural language description of flowers and generates an image matching the input description.
* With a few architectural tweaks including using [skip-thought](https://arxiv.org/abs/1506.06726) vectors for sentence representations, I successfully trained this model on the [Oxford-102](https://drive.google.com/open?id=0B0ywwgffWnLLcms2WWJQRFNSWXM) dataset with sentence descriptions.
* I have opensourced my TensorFlow implementation of this project on my GitHub profile in this repository: [Code link](https://github.com/vijayvee/text-to-image-synthesis)
* I have attached a sample set of results from my model below.

![Alt text](/files/t2i_2.png)
