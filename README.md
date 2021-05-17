# MDE Artifacts: Quality Guidelines for Research Artifacts in Model-Driven Engineering (Research Artifact)

## What?
### What is it all about?
This is the **MDE Artifacts** project, a research artifact for the article 
_Quality Guidelines for Research Artifacts in Model-Driven Engineering_.
This article has been submitted to the Foundations Track of the 
MODELS'21 conference as a Technical paper[^1].

###  What does it have?
In this research artifact, you will find:
1. Text document files (in _.docx_ format) with research practices.
2. Mind maps (in _.mm_ format) with research practices categorized 
   according to the 5W2H framework.
3. Our guidelines containing factual questions and best practices
   specifically tailored to MDE research projects.
4. Survey data and source code for analysis of results of our questionnaire.
   
### What concepts and technologies underpin the artifact?
This paper has been developed based on project quality management principles, 
the 5W2H framework, MDE literature in tooling issues and
and modelling artifact repositories.

## Why?
### Why it was created?
This research artifact has been made available to foster the 
reproducibility and reusability of our study.

## Where?
### Where is it hosted?
This research artifact is currently hosted on Google Drive.
However, once accepted, 
it will be moved to a GitHub pages and 
archived for long-term availability on Zenodo. 

### Where shall I cite?
As it is under double-blind review, 
there is still no specific citation format for this project.

### Where to find related work?
The list of related work is available in the last page of the article.
A pre-print of the manuscript will be included in this package.
To the interested reader, we recommend the following references:
- N. R. Tague, The quality toolbox, 2nd ed. Milwaukee, Wis: ASQ Quality Press, 2005.
> Particularly, we recommend looking at: 
>  - **Section 5.30) 5W2H**, which provides a description of the
     > method we used to categorize research practices.
>  - **Section 5.43) Mind Map**, which provides a description of the
     > method we used to organize and label our research practices.
- Project Management Institute, Ed., A guide to the project management body of knowledge 
  / Project Management Institute, Sixth edition. Newtown Square, PA: 
  Project Management Institute, 2017.
> Particularly, we recommend looking at:
>  - **Section 8.1) Plan Quality Management**, which describes some of the 
     > concepts that guided our methodology.

## Who?
### Who could use it?
As the main audience, we believe that MDE researchers 
(particularly 
**artifact authors**, 
**artifact evaluation organizers** 
and **artifact re-viewers**) 
may find these guidelines useful in the 
creationg, sharing, maintenance and evaluation of research artifacts 
in MDE research projects.
However, other research communities may find these ideas also useful in their domain,
as it can be easily adapted to other contexts.
The complete artifact is hosted on GitHub as an open source project.

### Who are the authors?
The paper associated with this research artifact is under double-blind review.
Thus, the artifact authors name are omitted.

### Who funded this project?

The paper associated with this research artifact is under double-blind review.
Thus, the supporting agency/university name is omitted.

## When?
### When did changes happen?
These files were generated between April and May 2021.
The artifact is versioned using Git.

### When do future changes shall happen?
As this artifact is available as an open-source project,
we invite MDE researchers and practitioners to join efforts on 
establishing quality standards for MDE research.
Researchers from other fields are also welcome to collaborate.

## How?
### How is it organized?
This artifact is organized as follows:
1. In folder **./data/01_practices_extracted/**,
   you find the text document files (in _.docx_ format) with
   more than 280 research practices we extracted from 
   eight general-purpose guidelines for artifact sharing.
2. In folder **./data/02_practices_labelling/**,
   you find the mind maps (in _.mm_ format)  we designed to 
   categorize the extracted research practices according to the
   seven perspectives the 5W2H framework.   
3. In folder **./data/03_guidelines_design/**,
   you find our proposed guidelines.
   These include a set of 19 factual questions and 
   84 best practices specifically tailored to MDE research projects.
   These questions were designed to help researchers to systematically
   think about concerns in MDE artifact sharing and
   provide  directions  to  additional  improvement  questions.
   In this folder, you also find the survey results in CSV format.
   The header of these files shall indicate the meaning of each column.
4. In folder **./analysis/**,
   you find the source code for analysis of results of our questionnaire.
   The source code is available as R Markdown notebooks in the **.Rmd** format.
   Generated images are available in folder **./analysis/img/** 

### How to set up a running environment?

To setup a running environment, you will need the R Statistical package v4.0.5.
More details about our environment are indicated in 
question _How many resources does it need?_

### How to get started?

To get started, please check folder **./analysis/**.
There you will find various R Markdown files with the code for drawing our plots and tables.
An auxiliary file with imports and data dictionaries is available at  **./analysis/utils.R**.

### How to run the analysis of results?

To re-run our statistical analysis, 
please check our files **./analysis/analysis_0[1-4]*.Rmd**.
These files shall repeat our analysis and 
automatically generate most of the data we used to answers RQs 1 to 4.

### How could it be repurposed?

Currently, we find three ways this artifact could be repurposed:

1. This artifact can be adapted to particular types of MDE artifacts.
2. This artifact can be improved by incorporating different stakeholder's viewpoints
3. This artifact can be used to support researchers in designing domain-specific guidelines to their particular research fields.

## How much/many?
### How many resources does it need?

For the survey, we used the Google Forms platform.

> **Google Forms**: https://www.google.com/forms/about/

For the statistical analysis, we used the
following following version of the R Statistical Package:
> **platform**:       x86_64-w64-mingw32          

> **arch**:           x86_64                      

> **os**:             mingw32                     
          
> **version.string**: R version 4.0.5 (2021-03-31)

The R statistical package was run using the following version of the RStudio IDE:
> **RStudio**: Version 1.4.1106

The hardware settings were:

> **OS Name**:	Microsoft Windows 10 Pro

> **Version**:	10.0.19042 Build 19042

> **System Type**:	x64-based PC

> **Processor**:	Intel(R) Core(TM) i7-10510U CPU @ 1.80GHz, 2304 Mhz, 4 Core(s), 8 Logical Processor(s)




[^1]: https://conf.researchr.org/track/models-2021/models-2021-technical-papers#Foundations-Track
