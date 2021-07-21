---
permalink: /
title: "About Me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<p align="justify">
Dr. Sohan Lal is a postdoctoral researcher at the Technical University of Berlin [(TU Berlin)](https://www.tu.berlin/en/), working on a DFG funded research project on advanced modeling and runtime support for large-scale HPC clusters [(Celerity)](https://celerity.github.io/). He graduated with a Ph.D. in Computer Science from TU Berlin in August 2019. His dissertation was titled “Power Modeling and Architectural Techniques for Energy-Efficient GPUs” and was supervised by Prof. Ben Juurlink. At TU Berlin, he worked on two EU funded research projects on low power parallel computing on GPUs [(LPGPU)](http://lpgpu.org/), where he led several tasks, collaborated with consortium members to deliver joint deliverables and contributed significantly to their success. His Ph.D. dissertation work was also conducted in the context of LPGPU projects. For his dissertation, he investigated bottlenecks that cause low performance and low energy efficiency in GPUs and proposed architectural techniques to improve performance and energy efficiency. The results of the dissertation were published in several reputed conferences such as IPDPS, DATE, ISPASS. He won several grants such as HiPEAC travel grants, a HiPEAC collaboration grant to visit Prof. Henk Coporaal (TU/e) that led to a joint publication at DATE. He was a semifinalist at ACM SRC held at MICRO'18. He is interested in computer architecture in general and graphics processing unit (GPU) architecture in particular and his broad research interests include power and performance modeling, parallel systems, memory systems, heterogeneous computing, approximate computing, applied machine learning, and GPU security.
</p>


<p align="justify">
Before Ph.D., he received his masters from the Indian Institute of Technology, Delhi [(IITD)](https://home.iitd.ac.in/) in 2011. Before that, he worked as a Lecturer at Shri Mata Vaishno Devi University [(SMVDU)](https://www.smvdu.ac.in/), which was the first teaching stint that made him deeply passionate and excited about teaching and mentorship. He also worked as an IT specialist in the Government of India. He received his bachelor in Computer Science and Engineering from Government College of Engineering and Technology [(GCET)](http://gcetjammu.org.in/), Jammu, India in 2003.
</p>
  
A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

