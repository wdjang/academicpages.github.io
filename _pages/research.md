---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<!--{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->



------------------------------------------------------------------------------
### Online Video Object Segmentation via Convolutional Trident Network
![CTN](/files/abstract_figures/CTN_overview.png)

##### Abstract
A semi-supervised online video object segmentation algorithm, which accepts user annotations about a target object at the first frame, is proposed in this work. We propagate the segmentation labels at the previous frame to the current frame using optical flow vectors. However, the propagation is error-prone. Therefore, we develop the convolutional trident network (CTN), which has three decoding branches: separative, definite foreground, and definite background decoders. Then, we perform Markov random field optimization based on outputs of the three decoders. We sequentially carry out these processes from the second to the last frames to extract a segment track of the target object. Experimental results demonstrate that the proposed algorithm significantly outperforms the state-of-the-art conventional algorithms on the DAVIS benchmark dataset.

##### Publication
Won-Dong Jang and Chang-Su Kim, "Online Video Object Segmentation via Convolutional Trident Network," in Proc. IEEE International Conference on Computer Vision and Pattern Recognition (CVPR), Honolulu, HI, USA, pp. 5849-5858, Jul. 2017. [[pdf]](http://openaccess.thecvf.com/content_cvpr_2017/papers/Jang_Online_Video_Object_CVPR_2017_paper.pdf) [[supplementary video]](https://youtu.be/anBeoXcGoXg)

##### 
[[GitHub link]](https://github.com/wdjang/CTN)

------------------------------------------------------------------------------


------------------------------------------------------------------------------
### Semi-supervised Video Object Segmentation Using Multiple Random Walkers
![SSVOS](/files/abstract_figures/SSVOS.png)

##### Abstract
A semi-supervised video object segmentation algorithm using multiple random walkers (MRW) is proposed in this work. We develop an initial probability estimation scheme that minimizes an objective function to roughly separate the foreground from the background. Then, we simulate MRW by employing the foreground and background agents. During the MRW process, we update restart distributions using a hybrid of inference restart rule and interactive restart rule. By performing these processes from the second to the last frames, we obtain a segment track of the target object. Furthermore, we optionally refine the segment track by performing Markov random field optimization. Experimental results demonstrate that the proposed algorithm significantly outperforms the state-of-the-art conventional algorithms on the SegTrack v2 dataset.

##### Publication
Won-Dong Jang and Chang-Su Kim, "Semi-supervised Video Object Segmentation Using Multiple Random Walkers," in Proc. British Machine Vision Conference (BMVC), York, UK, Sep. 2016. [[pdf]](/files/2016_BMVC_WDJANG.pdf)

##### Code
[[GitHub link]](https://github.com/wdjang/SSVOS)

------------------------------------------------------------------------------
