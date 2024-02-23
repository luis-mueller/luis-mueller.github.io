---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<img style="border: 1px solid black; border-radius: 50%; width: 30%" align="right" src="images/me.png"/>

Hi 👋, I'm Luis, a second year PhD student at RWTH Aachen University under the supervision of [Christopher Morris](https://chrsmrrs.github.io/).

I'm interested in studying the capabilities and limitations of general-purpose machine learning architectures in the context of graph learning. My current research focus is on deriving a principled understanding of graph transformers and their potential benefits over GNNs.
Email:<a style="margin: 7px; " class="u-email" href="mailto:{{ site.email }}">{{ site.email }}.</a>

<a style="margin: 7px; " href="https://www.twitter.com/{{ site.twitter_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#twitter' | relative_url }}"></use></svg> <span class="username">Twitter</span></a>
<a style="margin: 7px" href="https://github.com/{{ site.github_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#github' | relative_url }}"></use></svg> <span class="username">GitHub</span></a>
<a style="margin: 7px" href="https://www.linkedin.com/in/{{ site.linkedin_username| cgi_escape | escape }}"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#linkedin' | relative_url }}"></use></svg> <span class="username">LinkedIn</span></a>

<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/jpswalsh/academicons@1/css/academicons.min.css">

<h2 class="post-list-heading">{{ page.list_title | default: "Preprints" }}</h2>

**Towards Principled Graph Transformers**
*Luis Müller, Daniel Kusuma, Christopher Morris*    
We show that the Edge Transformer, a model originally proposed for improved systematic generalization over standard transformers, has provable 3-WL expressivity. We then demonstrate through a range of experiments on expressivity, molecular prediction and neural algorithmic reasoning benchmarks that the Edge Transformer matches or improves over SOTA graph learning models in terms of predictive performance.    
<i class="ai ai-arxiv ai-1x"></i> [Preprint](https://arxiv.org/abs/2401.10119)
[Code](https://github.com/luis-mueller/towards-principled-gts)

<h2 class="post-list-heading">{{ page.list_title | default: "Publications" }}</h2>

**Attending to Graph Transformers**
*Luis Müller, Michael Galkin, Christopher Morris, Ladislav Rampasek*    
We propose a taxonomy of graph transformers, overview their theoretical properties and investigate experimentally how well graph transformers can recover graph structure and mitigate issues with over-smoothing and over-squashing. *Accepted at TMLR.*   
<i class="ai ai-arxiv ai-1x"></i> [Arxiv](https://arxiv.org/abs/2302.04181)
<a style="margin-left: 5px" href="https://youtu.be/BuNXQIzLBWc"><svg class="svg-icon"><use xlink:href="{{ '/assets/minima-social-icons.svg#youtube' | relative_url }}"></use></svg>Talk</a>

**Representation Change in Model-Agnostic Meta-Learning**
*Thomas Goerttler, Luis Müller*    
Blog post, published at [ICLR 2022 Blog Track](https://iclr-blog-track.github.io/).   
[Website](https://iclr-blog-track.github.io/2022/03/25/representation-change-in-model-agnostic-meta-learning/)

**An Interactive Introduction to Model-Agnostic Meta-Learning**
*Luis Müller, Max Ploner, Thomas Goerttler, Klaus Obermayer*    
Interactive explainer, published at [VISxAI 2021](https://visxai.io/2021.html).  
[Website](https://interactive-maml.github.io/) [Code](https://github.com/luis-mueller/maml-tf2)

**Reachable Assignments on Cycles**
*Luis Müller, Matthias Bentert*    
Paper, published at ADT 2021 in Toulouse.  
<i class="ai ai-arxiv ai-1x"></i> [Preprint](https://arxiv.org/abs/2005.02218)
<i style="margin-left: 5px" class="ai ai-springer ai-1x"></i> [Conference Publication](https://link.springer.com/chapter/10.1007/978-3-030-87756-9_18)


