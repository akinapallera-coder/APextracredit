---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! My name is Akina Pallera and I am from Minot, ND. I am currently a Freshman stuying Mechanical and Aerospace Engineering with a minor in Criminal Justice at The George Washington University. I plan to use my degree to pursue a path in the automotive or motorsport industry. Alongside school I am also a flyer on the GW Cheer team and play the violin in the GW Orchestra.

Technical Skills
======
Computer Skills: AutoCAD, SolidWorks, Microsoft Office Suite, Google Suites

Programming Language Proficiency: Python, MATLAB

Experience
======
TARGET, Team Member, November, 2023 - Present
Provided customer support in a department averaging $10,000 in daily sales, trained 5 new employees in department knowledge, balanced and maintained part-time schedule with full-time academics.
Supported operations across several departments by adapting quickly to shifting priorities and using Target’s PDA device to fulfill guest requests efficiently, utilized inventory and workflow systems to manage product locations and backroom tasks, and collaborated with team members to ensure store efficiency.

WARD COUNTY STATE’S ATTORNEY OFFICE, Intern, October 2024 - December 2024
Reviewed and filed 5+ affidavits per week, supported attorneys in 10 trials, observed 30+ criminal court proceedings.
Organized documents containing case files and managed confidential information, performed database searches to support attorneys with trial preparation, utilized Microsoft Word to create documents presented in court, and managed departmental financial spending through Microsoft Excel.

OISHII RAMEN, Hostess, October 2021 - July 2023
Greeted an average of 100 guests per day, communicated amongst a team of 5 servers to maintain a positive work environment, developed and maintained relationships with recurring customers.
Operated a digital reservation system to optimize seating efficiency, managed phone systems to communicate with customers, maintained accurate records of guest seating, and processed payments using POS and order-entry systems.



Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one Markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a Markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each Markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual Markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the Markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and Markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a Markdown file for a talk
![Editing a Markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
