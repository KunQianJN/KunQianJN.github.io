---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Kun Qian earned his B.S. degree in Electronic Science and Technology from Xidian University, Xi'an, China in 2012, and his Ph.D. degree in the same field from Xidian University in 2019. In addition, he spent a year at Griffith University in Australia. He is now a lecturer at the School of Artificial Intelligence and Computer Science at Jiangnan University, Wuxi, China. His research focuses on machine learning, computer vision, and the tracking of hyperspectral/infrared video. 

相关成果
======
一、红外弱小目标跟踪
------

红外弱小目标

数据集：[UAV410](https://github.com/HwangBo94/Anti-UAV410) 、[2](https://www.scidb.cn/en/detail?dataSetId=808025946870251520)、[3](https://www.scidb.cn/en/detail?dataSetId=720626420933459968)...

[1] **Qian Kun**, Shen J, Wang S, et al. SiamUF: SiamCar based small UAV tracker using dense U-shape deep features in near infrared videos[J]. Optics and Lasers in Engineering, 2025, 186: 108825. (SCI中科院2区，Q1) [Website](https://www.sciencedirect.com/science/article/abs/pii/S0143816625000120)

[2] **Qian Kun**, Zhu D, Wu Y, et al. TransIST: Transformer based infrared small target tracking using multi-scale feature and exponential moving average learning[J]. Infrared Physics & Technology, 2024: 105674. (SCI中科院3区，Q2) [Website](https://www.sciencedirect.com/science/article/abs/pii/S1350449524005589)

[3] **Qian Kun**, Wang J S, Zhang S J. STRCFD: Small maneuvering object tracking via improved STRCF and redetection in near infrared videos[J]. IEEE Access, 2024. (SCI中科院3区，Q1) [Website](https://ieeexplore.ieee.org/abstract/document/10379631)

[4] **Qian Kun**, Zhang S, Ma H, et al. SiamIST: Infrared small target tracking based on an improved SiamRPN[J]. Infrared Physics & Technology, 2023, 134: 104920. (SCI中科院3区，Q2) [Website](https://www.sciencedirect.com/science/article/abs/pii/S135044952300378X) 

[5] **Qian Kun**, Rong S H, Cheng K H. Anti-interference small target tracking from infrared dual waveband imagery[J]. Infrared Physics & Technology, 2021, 118: 103882. (SCI中科院3区，Q2) [Website](https://www.sciencedirect.com/science/article/abs/pii/S1350449521002541) 

[6] **Qian Kun**, Zhou H, Wang B, et al. Infrared dim moving target tracking via sparsity-based discriminative classifier and convolutional network[J]. Infrared physics & technology, 2017, 86: 103-115. (SCI中科院3区，Q2) [Website](https://www.sciencedirect.com/science/article/abs/pii/S1350449516304522) 

[7] **Qian Kun**, Zhou H, Qin H, et al. Guided filter and convolutional network based tracking for infrared dim moving target[J]. Infrared Physics & Technology, 2017, 85: 431-442. (SCI中科院3区，Q2) [Website](https://www.sciencedirect.com/science/article/abs/pii/S1350449517301652) 

[8] **Qian Kun**, Zhou H, Rong S, et al. Infrared dim-small target tracking via singular value decomposition and improved Kernelized correlation filter[J]. Infrared Physics & Technology, 2017, 82: 18-27. (SCI中科院3区，Q2) [Website](https://www.sciencedirect.com/science/article/abs/pii/S1350449516304832) 



Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this template](https://github.com/academicpages/academicpages.github.io) by clicking the "Use this template" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
