---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io). -->
I am a third-year Ph.D. student at University of Wisconsin-Madison. It has been a great pleasure to be advised by [Prof. Umit Y. Ogras](https://scholar.google.com/citations?user=pVo_-KEAAAAJ). Prior to joining UW, I received my B.S. from University of Electronic Science and Technology of China (UESTC). Currently, I am doing my summer internship at [Ambarella](https://www.ambarella.com/), working on computer vision.

My current research interests include machine learning, more specifically, human activity recognition (HAR), 3D human pose estimation (HPE), transfer learning for user-specific applications, algorithm design for smart healthcare.

I am enthusiastic in learning new technology including but not limited to ML/CV/NLP. Welcome to my website and free feel to contact me at sizhe.an@wisc.edu

News
------
- July 2021: [Paper accepted for publication in EMBEDDED SYSTEMS WEEK 2021](https://github.com/SizheAn/MARS) 
- June 2021: Joining [Ambarella](https://www.ambarella.com/) as a computer vision intern
- November 2020: Passed my qual exam!
- June 2020: Transferred to UW-Madison from Ariona State
- October 2019: Best paper award at EMBEDDED SYSTEMS WEEK 2019! (1/243)

Research Highlights
------
![MARS](/images/MARS.gif)
**MARS: mmWave-based Assistive Rehabilitation System for Smart Healthcare**

**Sizhe An** and Umit Ogras

[Accepted in ESWEEK 2021, oral presentation](https://github.com/SizheAn/MARS)
======
![MGait](/images/exp_setup.png)

**MGait: Model-Based Gait Analysis Using Wearable Bend and Inertial Sensors**

**S An**, Y Tuncel, T Basaklar, GK Krishnakumar, G Bhat, U Ogras

[arxiv](https://arxiv.org/pdf/2102.11895.png)
======
**Transfer Learning for Human Activity Recognition using Representational Analysis of Neural Networks**

**S An**, G Bhat, S Gumussoy, U Ogras

[arxiv](https://arxiv.org/abs/2012.04479)
======
![Trends](/images/application_percentagev3.PNG)

**Trends in Technology Usage for Parkinson's Disease Assessment: A Systematic Review**

R Deb, G Bhat, **S An**, U Ogras, H Shill [[medRxiv](https://www.medrxiv.org/content/10.1101/2021.02.01.21250939v1.full)]

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
