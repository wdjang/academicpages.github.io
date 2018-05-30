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

# Semi-supervised Video Object Segmentation Using Multiple Random Walkers
![Alt Text](/files/2016_BMVC_WDJANG/SSVOS.png)
### Abstract
A semi-supervised video object segmentation algorithm using multiple random walkers (MRW) is proposed in this work. We develop an initial probability estimation scheme that minimizes an objective function to roughly separate the foreground from the background. Then, we simulate MRW by employing the foreground and background agents. During the MRW process, we update restart distributions using a hybrid of inference restart rule and interactive restart rule. By performing these processes from the second to the last frames, we obtain a segment track of the target object. Furthermore, we optionally refine the segment track by performing Markov random field optimization. Experimental results demonstrate that the proposed algorithm significantly outperforms the state-of-the-art conventional algorithms on the SegTrack v2 dataset.

### Publication
Won-Dong Jang and Chang-Su Kim, "Semi-supervised Video Object Segmentation Using Multiple Random Walkers," in Proc. British Machine Vision Conference (BMVC), York, UK, Sep. 2016. [pdf](/files/2016_BMVC_WDJANG.pdf) [supplementary video](/files/2016_BMVC_WDJANG/WDJANG_BMVC2016_Sup.avi)

### Code
[GitHub link](https://github.com/wdjang/SSVOS)

