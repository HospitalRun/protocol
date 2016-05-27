# HospitalRun protocol
A repository of SOAP notes based on accepted medical coding standards to provide clinical decision support to diagnosis and treatment.

# Assumptions
This README assumes that you have a basic understanding of how to work with GitHub, including branching repositories and [submitting Pull Requests](https://help.github.com/articles/using-pull-requests/). If that's not the case, [read this guide](https://guides.github.com/activities/contributing-to-open-source/), talk to a friend or Google it.

# Getting started
This repository is meant to capture the SOAP notes for various ICD-10 diagnostic codes. The structure of the repository is as follows:
```
+-- 2016_ICD-10-CM
  +-- J45.20.md
  +-- ANOTHER_CODE.md
  +-- LANGUAGE_BUNDLE_DIRECTORY
    +-- J45.20.md
    +-- ANOTHER_CODE.md
+-- ANOTHER_CODING_STANDARD
  +-- CODE.md
  +-- ANOTHER_CODE.md
  +-- LANGUAGE_BUNDLE_DIRECTORY
    +-- CODE.md
    +-- ANOTHER_CODE.md
```

For starters, we're focused on the core codes in English for 2016 ICD-10. The files are meant to be built following the [example file](2016_ICD-10-CM/2016_ICD-10-CM.example.md). 

# Authoring Files
There are two ways to go about authoring content for this repository.

1. Writing the files in pure on a text editor [markdown](https://daringfireball.net/projects/markdown/syntax). Markdown is a simple syntax for that can be translated by markdown processors into HTML. The idea is that it is declarative like HTML but less complex for those not interested in building files in HTML.
2. Using an online markdown editor. We recommend using the following [editor from dillinger.io](http://dillinger.io/). There you can see the results of your markdown in real-time and then Export the file to a markdown file that will be downloaded to your local computer. The result of that file can be added to the repository, following the naming and directory convention above.

# Questions
If you have questions regarding how to get involved in this project, including how your work can be referenced and credited as a clinician or medical student, email <mailto:protocol@hospitalrun.io>.
