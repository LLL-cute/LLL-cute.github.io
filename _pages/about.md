---
permalink: /
title: "Shuai Yu"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

2022年6月获得复旦大学计算机应用技术专业博士学位。同年12月起，在东华大学计算机科学与技术学院担任讲师，从事人工智能方面的科研工作。目前已在国际顶级会议期刊发表论文10余篇。参与国家自然科学基金项目和科技部重大科研项目各1项。担任IEEE Transactions on Affective Computing、IEEE-ACM Transactions on Audio, Speech and Language Processing、Neurocomputing、ICASSP、ICME等期刊和会议审稿人。

主要研究论文
======
1. Shuai Yu.“MCSSME: Multi-task Contrastive Learning for Semi-Supervised Singing Melody Extraction from Polyphonic Music”, Proceedings of the AAAI Conference on Artificial Intelligence (AAAI, Full paper, CCF-A) 2024.

2. Shuai Yu,Jun Liu（指导的硕士生）, Yi Yu, Wei Li. “A Scalable Sparse Transformer for Singing Melody Extraction”, International Conference on Acoustics, Speech and Signal Processing (ICASSP, CCF-B), 2024.

3. Shuai Yu, Yi Yu, Wei Li, “A Neural Harmonic-aware Network with Gated Attentive Fusion for Singing Melody Extraction”, Neurocomputing (中科院SCI二区Top，IF=6.0), Vol.521, pp. 160-171, 2023.

4. Shuai Yu, Xi Chen, Wei Li, “Hierarchical Graph-based Neural Network for Singing Melody Extraction”, International Conference on Acoustics, Speech and Signal Processing (ICASSP, CCF-B), pp. 626-630, 2022.

5. Shuai Yu, Yiwei Ding, Kun Qian, Bin Hu, Wei Li, Björn Schuller, “A Glance-and-gaze Network for Respiratory Sound Classification”, International Conference on Acoustics, Speech and Signal Processing (ICASSP, CCF-B), pp. 9007-9011, 2022.

6. Ke Chen, Shuai Yu, Cheng-i Wang, Wei Li, Taylor Berg-Kirkpatrick, Shlomo Dubnov, “TONet: Tone-Octave Network for Singing Melody Extraction from Polyphonic Music”, International Conference on Acoustics, Speech and Signal Processing (ICASSP, CCF-B), pp. 621-625, 2022.

7. Shuai Yu, Yi Yu, Xi Chen and Wei Li, “HANME: Hierarchical Attention Network for Singing Melody Extraction”, IEEE Signal Processing Letters (SCI 二区, IF=3.109), vol. 28, pp. 1006-1010, 2021.

8. Shuai Yu, Xiaoheng Sun, Yi Yu, Wei Li, “Frequency-temporal Attention Network for Singing Melody Extraction”, International Conference on Acoustics, Speech and Signal Processing (ICASSP, CCF-B), pp. 251-255, 2021.

9. Shuai Yu, Chenxing Li, Feng Deng, Xiaorui Wang, “Rethinking Singing Voice Separation with Spectral-Temporal Transformer”, Asia-Pacific Signal and Information Processing Associate, (APSIPA ASC, EI), pp. 884-889, 2021.

10. Shuai Yu, Yongbo Wang, Min Yang, Baocheng Li, Jialie Shen, “NAIRS: A Neural Attentive Interpretable Recommendation System”, ACM International Conference on Web Search and Data Mining (WSDM, CCF-B, Demo Paper), pp. 790-793, 2019.

11. Shuai Yu, Min Yang, Qiang Qu, Ying Shen, “Contextual-Boosted Deep Neural Collaborative Filtering Model for Interpretable Recommendation”, Expert Systems with Applications (中科院SCI 一区Top, IF=8.665), vol.136, pp. 365-375, 2019.

12. Sixuan Chen, Shuai Yu *, “WAIS: Word Attention for Joint Intent Detection and Slot Filling”, Proceedings of the AAAI Conference on Artificial Intelligence (AAAI, CCF-A, Abstract), pp. 9927-9928, 2019.

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
