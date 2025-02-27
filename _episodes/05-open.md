---
title: "Version Control and Open Science Practices"
teaching: 10
exercises: 0
questions:
- "How is version control system relevant for biomedical research?"
- "How to maintain history of contributions and contributors?"
- "How to apply open science practices to work transparently and collaborate openly?"
objectives:
- "Describe the importance of version control systems"
- "Nudge the use of GitHub/GitLab for open collaboration"
- "Share open science practices for transparent and ethical research"
keypoints:
- "Version controlled repository help record different contributions and contributor information openly."
- "Open Science is an umbrella term that involve different practices for research in the context of different research objects."
- "Online Persistent Identifiers or Digital Object Identifiers are useful for releasing and citing different versions of research objects."
---

# Version Control, Open Science and Identifiers to Cite Research Objects

[Add a biological context or case study]

## Maintaining History through Version Control

![Contrast in project history management. On the left - choosing between ambiguosly named files. On the right - picking between successive versions (from V1 to V6).](https://zenodo.org/api/iiif/v2/0c0188d3-d03c-4830-a6e3-00405f5c22fa:df931888-09af-4eac-945f-0c208be0c26b:ProjectHistory.jpg/full/750,/0/default.jpg)

*Version control allows tracking of history and go back to different versions as needed. The Turing Way project illustration by Scriberia for The Turing Way Community Shared under CC-BY 4.0 License. Zenodo. http://doi.org/10.5281/zenodo.3332807*

Practices and recommendations described in this lesson are applicable to all areas of biological research. 
What can be considered slightly different in computational projects is that every object required to carry out the research exist in digital form. 
Starting from research workflow, data, software, analysis process, resulting outcomes as well as how researchers involved in the project communicate with each other. 
This means that research objects can be organised and maintained without losing the provenance or missing knowledge of how each of these objects is connected in the context of your project.

## Versioning Every Research Object

Management of changes or revisions to any type of information made in a file or project is called versioning. 
Version Control Systems are platform and technical tools that allow all changes made in a file or research object over time is recorded. 
Version Control Systems, or VCS, allows all collaborators to track history, review any changes, give appropriate credit to all contributors, track and fix errors when they appear and revert or go back to earlier versions. 

Different VCS can be used through a program with web browser-based applications (such as [Google Docs](https://docs.google.com/) for documents) and more dynamically for code and all kinds of data through command-line tools (such as [Git](https://en.wikipedia.org/wiki/Git)) and their integration into the graphical user interface ([Visual Studio Code](https://code.visualstudio.com/) editor, [Git-gui](https://git-scm.com/downloads/guis) and [gitkraken](https://www.gitkraken.com/)).
The practice of versioning is particularly important to allow non-linear or branched development of different parts of the project, testing a new feature, debugging and error or reusing code from one project to different data by different contributors.

[GitLab](https://about.gitlab.com/), [GitHub](https://github.com/), or [BitBucket](https://bitbucket.org) are online platforms that allow version-controlled projects online and allow multiple collaborators to participate. Different members can download a copy of the online repository (most recent version), make changes by adding their contributions locally on their computer and push the changes to GitLab/GitHub/BitBucket (a new version!) allowing others to build on the new development.

Read [All you need to know about Git, GitHub & GitLab](https://towardsdatascience.com/all-you-need-to-know-about-git-github-gitlab-24a853422ff3) on Towards Data Science and [version control](https://the-turing-way.netlify.app/reproducible-research/vcs.html) in *The Turing way* for more details on workflow, technical details of using git and versioning large datasets.

## Apply Open Science Best Practices

Open Science invites all researchers to share their work, data and research components openly so that others can read, reuse, reproduce, build upon and share them. 
Particularly in computational research and software development projects, open source practices are widely promoted. 
Unfortunately, making research components open doesn’t always mean that they can be easily discovered by everyone, can be reproduced and built upon by others or everyone will know how to use them.
Applying open and inclusive principles to open science and reproducible research requires time, intention, resources and collaboration, which can be overwhelming for many (see [Ten arguments against Open Science that you can win](https://www.software.ac.uk/blog/2020-12-17-ten-arguments-against-open-science-you-can-win)).
However, by normalising the use of research best practices on a day-to-day basis, you can ensure that everyone has a chance to build habits around opening their work for others in the team, asking for regular feedback, getting attributed for their work and enjoying the process of collaboration.

Open doesn't mean sharing everything, but making it 'as open as possible and as closed as necessary'.
Your research can still be reproducible without all parts necessarily being open.
Research projects that use sensitive data should be more careful and follow research data management plans closely (discussed in the next chapter).

### Important Reasons for Practicing Openness

> ## Open Science in Research
>
> * **Maintains transparency**
> * **Allows others to attribute your work fairly**
> * **Stops others from reinventing the wheel**
> * **Invites collaborators from all around the world**
> * **Makes your work easy to release to be cited by others**
{: .callout}

![Image shows a person having internal debate about open vesus closed research. Open means new opportunities and inclusivity but closed maybe required to ensure data sensitivity or wrongly assumed for funding for novel work.](https://zenodo.org/api/iiif/v2/5c8c70c9-4119-4917-91d1-bc955943f586:b7d2f709-d5f6-4091-bd12-27455cd9e239:open-vs-close-research-with-text.jpg/full/750,/0/default.jpg)

*Open versus Closed Research. The Turing Way project illustration by Scriberia for The Turing Way Community Shared under CC-BY 4.0 License. Zenodo. http://doi.org/10.5281/zenodo.3332807*

* When a project is designed in an open repository, it **allows all stakeholders to track the progress, raise errors and collaborate** to improve the project.
* When developed openly, such as on GitLab or through the registered report, it is easy to point to the timeline when an idea or experiment was proposed and **exhibit how the project developed, who contributed and how others can attribute the work**.
* Having your research open from the start can **help others working in similar subjects or starting research**. It allows them to conduct their review work effectively and build on the existing work, rather than starting from scratch, or 'reinventing the wheel'.
* With open repositories and descriptions for where you need help or how others can collaborate, you can **get people in your area with complementing skills and new ideas interested in your work**, even when you don't know them.

### Research Objects can be Released with Digital Object Identifiers (DOI)

DOIs are alphanumerical unique and persistent identifiers with a permanent web address for different research objects that can be cited by you and other researchers. 
Each pre-print and publication is published with a DOI, but independent of the paper, different research objects can be published online on servers that offer DOIs at any stage of your research. 
Some of these servers are [Zenodo](https://zenodo.org/), [FigShare](https://figshare.com/), [Data Dryad](https://datadryad.org/stash) (for data), [Open Grants](https://www.ogrants.org/) (for grant proposals) and [Open Science Framework](https://osf.io/) (OSF) (for different components of an open research project).
It allows you to show connections between different parts of research as well as cite different objects from your work independently.

When working on GitHub for instance, you can [connect the project repository with Zenodo](https://docs.github.com/en/repositories/archiving-a-github-repository/referencing-and-citing-content) to get a DOI for your repository.
The [Citation File Format](https://citation-file-format.github.io/), then lets you provide citation metadata, for software or datasets, in plaintext files that are easy to read by both humans and machines.
Read the [Making Research Objects Citable](https://the-turing-way.netlify.app/communication/citable.html) chapter in *The Turing Way* Guide to Communication.

### Every Little Step Counts towards Openness

Open Science can mean different things in different contexts: open data, open source code, open access publication, open scholarship, open hardware, open education, open notebook, citizen science and inclusive research.
Expert open science practitioners might consider applying a combination of open science practices and make decisions in their work to maintain different kinds of openness.
However, for the new starters in your team, open science can be as simple as ensuring that:
* everyone has added an appropriate license to their project repository,
* recorded their work and shared their project's roadmap on a README/landing page,
* provided some basic manual for how to use their work and how to contribute,
* given credit to previous work upon which they build, and
* regularly communicate about their research.

![Image shows a woman slowly gaining trust and confidence in opening up her research project and benefitting from open collaboration](https://zenodo.org/api/iiif/v2/514d0fdf-b1b3-4e94-842d-85b09f344668:1016fa41-7b71-425b-8aa9-436f42008339:EvolutionOpenResearch.jpg/full/750,/0/default.jpg)

*Small steps towards open science. The Turing Way project illustration by Scriberia for The Turing Way Community Shared under CC-BY 4.0 License. Zenodo. http://doi.org/10.5281/zenodo.3332807*

Encourage taking small steps towards openness as a responsibility towards research integrity in your team.
There are many community-driven resources, guidance and opportunities in open science that provided structured support to learn about open science.
For instance, *The Turing Way* [chapter on Open Research](https://the-turing-way.netlify.app/reproducible-research/open.html) and [FOSTER Open Science](https://www.fosteropenscience.eu/learning/what-is-open-science/#/id/5ab8ea32dd1827131b90e3ac) provides an introduction to help researchers understand what open science is and why it is something you should care about. 
Another hands-on opportunity is provided by [Open Life Science](https://openlifesci.org), which is a 16-week long training and mentoring for anyone in research interested in going through the programme to apply open science practices systematically in their research projects.

## Conclusion

[What gaps have we filled in this section - add biological context]

## Resources and References for Technical Details

- *The Turing Way*. *The Turing Way Community. (2021). The Turing Way: A handbook for reproducible, ethical and collaborative research (1.0.1). Zenodo. [DOI: 10.5281/zenodo.5671094](https://doi.org/10.5281/zenodo.5671094)*
  - [Version control](https://the-turing-way.netlify.app/reproducible-research/vcs.html) 
  - [Getting Started With GitHub](https://the-turing-way.netlify.app/collaboration/github-novice.html)
  - [Open Science](https://the-turing-way.netlify.app/reproducible-research/open.html)
  - [Managing a New Community and Team](https://the-turing-way.netlify.app/collaboration/new-community.html)
  - [Making Research Objects Citable](https://the-turing-way.netlify.app/communication/citable.html)
- [What is a Registered Report?](https://support.jmir.org/hc/en-us/articles/360003450852-What-is-a-Registered-Report-) by JMIR, referencing to [Registered Reports by Center for Open Science](https://www.cos.io/initiatives/registered-reports).
- [Open Life Science training and Mentoring Programme](https://openlifesci.org). *Batut, Bérénice, Yehudi, Yo, Sharan, Malvika, Tsang, Emmy, & Open Life Science Community. (2021). Open Life Science - Training and Mentoring programme - Website release 2019-2021 (1.0.0). Zenodo. [DOI: 10.5281/zenodo.5636584](https://doi.org/10.5281/zenodo.5636584)*

{% include links.md %}

