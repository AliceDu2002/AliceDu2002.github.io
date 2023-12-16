---
layout: page
title: Object detection and counting in video with FPGA
description: My project of the course Digital Circuit Lab.
img: assets/img/dclab/dclab_1.jpg
importance: 2
category: courses
related_publications: 
---

Taking the course Electrical Engineering Lab (Digital Circuit), we undertook diverse projects, including speech processing and RSA256 using FPGA. <br>
My final project focused on object counting in videos, where we implemented multiple techniques. First, the pixels had to be binarized in order to be recognized more easily. The most challenging part is to deal with the streaming pixels, where we could not random access the picture for object detection. Thus, we developed the Blob algorithm for streaming pixels' detection. Last, we used the number of pixels of an object to filter out noise and differentiate various objects. <br>
Below is our presentation slides and demo video.
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSSr0EJEFKffRD1vNUF_eGatrgVcX2inOmkI6o66Dh87tXovd-7qNiWdC8oZhPl5g/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
