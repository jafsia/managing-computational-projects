---
title: "Research Data Management"
teaching: 20
exercises: 0
questions:
- "What is considered research data?"
- "How to start building a research data management plan?"
- "What is FAIR principles for data management?"
- "Why care about documentation and metadata standards?"
objectives:
- "Describe research data management (RDM)"
- "Explain FAIR principles and practices for RDM"
- "Introduce data storage and organisation plan"
- "Discuss documentation and metadata practices"
keypoints:
- "Good research data management practices esures findability of your research data."
- "Storing, regular backing-up and archiving prevents data loss."
- "Sharing all types of research data transparently makes them easier to understand and reuse by others."
- "Gives fair recognition to people generating, handling and using data, and further stimulates collaboration with others."
---

# Research Data Management

## Main Challenges and Concerns

> ## Need to consider standard file formats for future use of data!
>
> *Electron Microscope Facility in our institute has produced around 5 petabytes (5,000,000 GB) of data since the institute opening. 
> These files are stored safely and privately, and have not been standardised. 
> As a result they are in danger of being lost forever, stored but never used. 
> With metadata, this could form a transformative training data set for machine learning tools and possibly lead to new discoveries and insights. 
> Creating Alpha Fold and other machine learning/AI tools you need large data sets. 
> Meta data allows data to be future proofed for further research and even innovative research not currently possible.*
> 
{: .testimonial}

## Overview of Research Data Management

Research Data Management (RDM) covers how research data can be stored, described and reused. Data here is used as a generic term to encompass all digital objects. RDM is a vital part of enabling reproducible research. 
RDM ensures efficiency in research workflows, and also greater reach and impact, as data become FAIR (Findable, Accessible, Interoperable and Reusable). 
Data should be stored in multiple locations and backed up regularly to prevent loss or data corruption.

> ## Why This is Useful
>
> Managing your data allows you to always find your data and ensure the quality of scientific practice or research.
> Storing your data properly and backing up regularly prevents data loss.
> It can help with recognition for all research outputs.
> It stimulates collaboration with others, who will find it easier to understand and reuse your data.
> RDM is cost/time efficient, as you will always be able to find and use your data.
{: .callout}

Clearly describing data using documentation and metadata ensures that others know how to access, use and reuse your data, and also enable conditions for sharing and publishing data to be outlined.

## Documentation and Metadata

Having data available is of no use if it cannot be understood. Therefore research data should always include consistent documents and metadata.

Data documentation provides contexts and full description about the data.
It allows your collaborators, colleagues and future you to understand what has been done and why.
Ideally written in clear and plain language, documentation describes data with sufficient information such as source, strengths, weaknesses, and analytical limitations of the data allowing users to make informed decisions when using it.

Without metadata to provide provenance and context, the data can’t be used effectively.
Metadata is information about the data, descriptors that facilitate cataloguing data and data discovery. 
Often, metadata are intended for machine reading. 
When data is submitted to a trusted data repository, the machine-readable metadata is generated by the repository. 
If the data is not in a repository a text file with machine-readable metadata can be added as part of the documentation.

-   The type of research and the nature of the data also influence what kind of documentation is necessary. It is best practice to use recognised community metadata standards to make it easier for datasets to be combined.
-   The level of documentation and metadata will vary according to the project type and the range of stakeholders, including the future users.
-   Examples of documentation may include items like [data dictionaries](https://help.osf.io/hc/en-us/articles/360019739054-How-to-Make-a-Data-Dictionary) or codebooks, protocols, logbooks or lab journals, README files, research logs, analysis syntax, algorithms and code comments.
-   Variables should be defined and explained using data dictionaries or codebooks.
-   Data should be stored in logical and hierarchical folder structures, with a README file used to describe the structure.

## Defining Data

Data are objects that you use and produce during your research life cycle, encompassing data
sets, software, code, workflow, models, figures, tables, images and videos, interviews, articles. Data are your research asset. 
A good way of thinking about what might be classed as data that needs to be managed is to ask yourself the questions: 
- What is the information that I need to use and write about in my paper or book?
- What information would I need to back up my conclusions?
- What information is needed by others to understand and possibly replicate the research that I have done?
This information is your data.

## The Research Data Lifecycle - A Model for Data Management

Research data often follows a ‘lifecycle’ that follows the research project as it evolves.
This model provides a sound basis on which to plan for research data management, from data creation at the start of a research project, through to publishing and sharing research at the end of the project, and archiving any research data for the long-term and future re-use once the project has ended.

The research data lifecycle involves data creation, data use, data publication and sharing, data archiving, and data re-use or destruction. 
However, data have a longer lifespan than the research project that creates them. In a Data Management Plan, you can structure how you will manage and share your research data.

## Data Management Plan

A Data Management Plan (DMP), or Output Management Plan, is a document that describes how your research outputs will be generated, stored, used and shared within your project. 
A DMP is a living document, which can be updated throughout the research project as needed.

A Data Management Plan is a roadmap for you to manage your data efficiently and securely. This can prevent data loss or breaches. 
Planning ahead on how to manage your data consistently can save you time later on!

### A Data Management Plan should provide information on five main topics

1.  **Roles and Responsibilities** for the management of the data and code to help prevent confusion/miscommunication later in the project. 
Please check the DMP recommendations and requirements library research support team of your institute and the website of your funder. 
You can check if your funder or institute has a DMP template using [DMPonline](https://dmponline.dcc.ac.uk/).
2.  **A list of types, standards and formats** for data, documentation and metadata (discussed later) should allow team members to understand to comply with the recommendations from the start of the project.
-   A distinction can be described in the plan separately for different data types such as raw (primary), processed and ready to use (finalised to publish) datasets.
-   All types of data will have to be described to be placed into context by using metadata and adequate documentation which will allow anyone in your team to interpret the data in the future.
3.  **Data storage and backup procedures** should be assessed for each project and established depending on the institutional requirements, associated costs and recommended format from your field. We will diuscuss this in detail later in this lesson.
4.  **Preservation of the research outputs** can be managed differently based on if they can be made publicly available or not. Personal data or research outputs needed to apply for patents cannot be publicly shared but they still have to be preserved for several years, depending on the policies of your country, institute and funder. Learn more about this in detail in [Sharing and Archiving Data](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-sharing.html#rr-rdm-sharing) chapter in _The Turing Way_.
5.  **Reuse of your research outputs** should be ensured by selecting licenses for different components of your research when you make your output available on a repository (see the Licensing subchapters on [data](https://the-turing-way.netlify.app/reproducible-research/licensing/licensing-data.html#rr-licensing-data) and [software](https://the-turing-way.netlify.app/reproducible-research/licensing/licensing-software.html#rr-licensing-software) for more information). A dedicated document (such as a README file) is recommended for describing research outputs into context. UK Data Service has provided a [Data Management Checklist](https://ukdataservice.ac.uk/learning-hub/research-data-management/plan-to-share/checklist/) to help cover different aspects of the DMP.


## The FAIR Principles

The FAIR guiding principles for scientific data management and stewardship are guidelines to improve the **F**indability, **A**ccessibility, **I**nteroperability and **R**eusability of digital assets; all of which support research reproducibility. 
The FAIR principles facilitate the availability of research data so that others can reuse data.

> ## FAIR data should be:
>
> - **Findable**: The first step in (re)using data is to find them! Descriptive metadata (information about the data such as keywords) are essential.
> - **Accessible**: Once the user finds the data and software they need to know how to access it. Data could be openly available but it is also possible that authentication and authorisation procedures are necessary.
> - **Interoperable**: Data needs to be integrated with other data and interoperate with applications or workflows.
> - **Reusable**: Data should be well-described so that they can be used, combined, and extended in different settings.
{: .callout}

Making data ‘FAIR’ is not the same as making it ‘open’. 
Accessible means that there is a procedure in place to access the data. Data should be as open as possible, and as closed as necessary.
It is also important to say that the FAIR principles are aspirational: they do not strictly define how to achieve a state of FAIRness, but rather describe a continuum of features, attributes, and behaviours that will move a digital resource closer to that goal.
Even though the FAIR principles have been defined to allow machines to find and use digital objects automatically, they improve the reusability of data by humans as well. 
The capacity of computational systems to find, access, interoperate, and reuse data, with minimal human intervention, is essential in today’s data-driven era.

You can find a more detailed [overview of the FAIR principles by GO FAIR](https://www.go-fair.org/fair-principles) of what the FAIR principles recommend.

## A Note on Personal or Sensitive Data

Personal data is information about **living people** who can be identified using the data that you are processing, either directly or indirectly.
A person’s name, address or Social Security number, as well as, racial/ethnic identity, political opinions, religious/philosophical beliefs, trade union membership, genetic and biometric data, physical or mental health, and sexual orientation are some examples of personal data. 
Indirect identifiers include health, economic, cultural or social characteristics. 
Especially when a certain combination of these identifiers can be used to identify a person, care must be taken to manage the data properly.

There are various policies in place in different countries to protect the rights of individuals over their personal data. 
For instance, in the European Union and the UK the **GDPR** (General Data Protection Regulation) applies to the processing of personal data and may require researchers to carry out a Data Protection Impact Assessment ([DPIA](https://youtu.be/YRiCb3unz3g?t=988)). 
Processing means doing anything with a person’s information, including collection, storage, analysis, sharing, deletion and destruction. 
Please review the national/institutional policies that apply to your research to ensure that you are up to date with the requirements of managing sensitive data.
Please read [Personal data management](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-personal.html), [informed consent](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-personal.html#informed-consent), [Research Ethics Committees Processes](https://the-turing-way.netlify.app/ethical-research/ethics-committees.html) and [Open Data](https://the-turing-way.netlify.app/reproducible-research/open/open-data.html) sections in *The Turing Way* for further details.

## Data Storage, Organisation and Backup Procedures

Data loss can be catastrophic for your research project and can happen often. You can prevent data loss by picking suitable storage solutions and backing your data up frequently.
- Most institutions will provide a network drive that you can use to store data.
- Portable storage media such as memory sticks (USB sticks) are more risky and vulnerable to loss and damage.
- Cloud storage provides a convenient way to store, backup and retrieve data. You should check terms of use before using them for your research data.

Especially if you are handling personal or sensitive data, you need to ensure the cloud option is compliant with any data protection rules the data is bound by. 
To add an extra layer of security, you should encrypt devices and files where needed.
Your institution might provide local storage solutions and policies or guidelines restricting what you can use. 
Thus, we recommend you familiarise yourself with your local policies and recommendations.

> ## Note
>
> -   Some concepts discussed in the previous chapter such as setting up project repository, version controlling, pre-registration, and licensing apply to this point.
> -   Also consider FAIR practices, data organisation and handling sensitive data practices, as well as metadata and documentation that are discussed below.
{: .callout}

Spreadsheets, such as Microsoft Excel files, google sheets, and their Open Source alternative [(for instance) LibreOffice](https://www.libreoffice.org), are commonly used by wet-lab experimentalists to collect, store, manipulate, analyse, and share research data. 
Spreadsheets are convenient and easy-to-use tools for organising information into an easy to write and easy to read forms for humans. 
However, one should use them with caution, as the use of an inappropriate spreadsheet is a major cause of mistakes in the data analysis workflow.

Please refer to the [Data Carpentry Ecology Lesson](https://datacarpentry.org/spreadsheet-ecology-lesson/) and *The Turing Way* chapter for [managing data in spreadsheet](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-spreadsheets.html) for best practices.

### Backups

To avoid losing your data, you should follow good backup practices.
- You should have 2 or 3 copies of your files, stored on
- at least 2 different storage media,
- in different locations.

The more important the data and the more often the datasets change, the more frequently you should back them up. 
If your files take up a large amount of space and backing up all of them proves to be challenging or expensive, you may want to create a set of criteria for when you back up the data. This can be part of your data management plan (DMP).

When you are ready to release the data to the wider community, you can also search for the appropriate databases and repositories in [FAIRsharing](https://fairsharing.org/databases), according to your data type, and type of access to the data. 
Learn more about this in *The Turing Way* chapter on [sharing and archiving Data](https://the-turing-way.netlify.app/reproducible-research/rdm/rdm-sharing.html#rr-rdm-sharing).

[Add Metadata Standards as recommended by the Crick]

## Conclusion
- [Add biological context for what gaps have we filled in this section]

## Resources and References for Technical Details

In addition to the referenced linked under different sections in this lesson, please see the following references:
- [Add recommendations from 1:1 interviews, open communities such as Open Life Science and The Turing Way.]

## Acknowledgement

- This episode is a reuse of *The Turing Way* chapter on [Research Data Management](https://the-turing-way.netlify.app/reproducible-research/rdm.html).
- Among many authors, reviewers and contributors, we thanks Esther Plomp (Data Steward at TU Delft) for maintaining this chapter in The Turing Way Guide for Research Data Management.
- Please cite *The Turing Way* as: The Turing Way Community. (2021). The Turing Way: A handbook for reproducible, ethical and collaborative research (1.0.1). Zenodo. https://doi.org/10.5281/zenodo.5671094

{% include links.md %}

