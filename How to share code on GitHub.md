# How to share analysis code on GitHub

> Felix Molter  
> 20 November 2016

### Background

GitHub is an online service that allows users to share, maintain and develop programming code of all sorts and actively collaborate on programming projects. The main features are

1. **Private and public hosting of repositories**
2. **Version control**
    + commented history, roll back to previous versions
    + *branches*: Parallel versions, e.g., for development of experimental features
3. **Collaboration**
    + Pull & Merge requests, i.e., contribute to other people's code
    + Conflict management
    + Issue tracking

This short tutorial will mainly focus on ***1.*** however, illustrating how (analysis) code can be shared easily on GitHub. Resources on how to use more advanced features like Version Control and Collaborative tools are supplied at the end of the tutorial.

### 1. Create a GitHub account

A free GitHub account is required. Paid plans offering a more extensive set of features are available but not necessary for the use cases illustrated here. 

> Some advanced features (mainly private repositories) can be used for free for academic purposes, if one requests an education discount. These can be useful for the storage of non-final projects. To request the discount, visit https://education.github.com/discount_requests/ and follow the process there, after you completed the basic sign up.

1.1. Go to www.github.com/join
1.2. Complete the sign up process (choose the free plan), verify your email address, sign into github.com using your account credentials

## 2. Create a repository

Code on GitHub is shared in the form of repositories. You can have an unlimited number of repositories, so it is recommended to create one repository for every individual project (e.g., publication) you want to share code from. Each repository has its own ***README*** (a text file that is immediately visible to others, outlining main details of the project, *see below*) and ***LICENSE*** (clarifying use, reuse of code and data shared, *see below*).

2.1. To create your first repository, on the main page click the Plus sign "New repository".
2.2. Fill out the required fields:
	2.2.1. Name of the repository (this will also be the URL)
	2.2.2. Short description (optional)
2.3. Add a **LICENSE**
	2.3.1. You can choose a license from the drop down menu, or later add a file called LICENSE to the repository manually *(see below)*
	> To help you choose a license, visit http://choosealicense.com/
	> **Note that you still own the copyright to your work, even if no license is specified!**
2.4. Add a **README**
	You can have GitHub automatically create a README file when you create the repository.
	2.4.1. The **README** should contain basic information about the project.
	2.4.2. You can edit the **README** file online, or upload a file called *"README"* to the repository *(see below)*

## 3. Add files

- You have successfully created a repository, to which you can now add files
	- either by uploading files from your computer
	- or creating them in the browser
- To upload a file, click "Upload files"

- ...Browser ...

## 3. Best practices for sharing analysis code

- self contained
- clear statement of system requirements (include package versions, since features can become deprecated over development)
- include (sample data)
    - ideally in raw (i.e., not preprocessed or aggregated in any way) format
    - include data preprocessing
- include codebook
    + describe variables
    + describe variable levels
    + describe missingness of data
    + include information on sampling procedure / experiment

## 3. Make the repository citable (get a DOI)

-

## X. Integration with other services

1. Open Science Framework (OSF)

GitHub repositories can be integrated to existing OSF projects.


# Additional information, advanced features

While the ability to publicly share analysis code, examples, figures, etc. is great, github offers much more functionality. Most of this is especially useful for active and possibly collaborative code development and maintenance. These features include:

- version control
- pull & merge requests
- branches
- use of the command line interface to manage repositories

An introductory interactive tutorial can be found at github.com/tutorial. More advanced tutorials:
- ...


- https://guides.github.com/activities/hello-world/