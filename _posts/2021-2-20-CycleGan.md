---
layout: post
title: On the Brink of Collapse: Exploring the Limitations of Cycle-Gan
---

Supervised learning has shown incredible results in image classification,
natural language processing/understanding, and other domains. This type of
learning is inherently limited by the quality of labeled data. It is both
expensive and time consuming to label a dataset, especially large ones with
potentially millions of samples. This is why alternatives to supervised
learning are so appealing. 

Cycle-Gan is a generative model for image-to-image translation. Image-to-image
translation is, like many things in machine learning, both a problem and a
solution. This problem of image-to-image translation is concerned with
capturing the characteristics, or essence, of a particular domain of images and
modifying another domain of images to exhibit those characteristics. One famous
sub-domain of image-to-image translation is style-transfer. In style-transfer,
the style of a single image is superimposed over another.  The image whose
style is applied to another image is known as a style image. The image that has
some external style applied to it is known as the content image. Frankly, when
defining "style" in the context of style-transfer, I've always struggled with
what "style" objectively means. It seems to be something best understood
visually. Below are a few samples that show this concept:

Image 1			 | Image 2
:---------------:|:---------------:
![]({{ site.baseurl }}/images/madvillain.jpg) | ![]()

