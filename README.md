# Data Privacy Workshop

## Background
This workshop is designed to provide participants a basic overview and understanding of data privacy concepts and techniques, especially from a government agency context.

In the workshop, there will be case studies and hands on python coding to familiarize participants with the available tools and resources.

Participants are assumed to have some knowledge on basic python programming and have some experience working with data.


## Agenda

### Introduction (26 January 2022 2-3pm): Alan

**Context – why is privacy important?**

* What is data privacy? 
  * Common definitions and frameworks
  * Data privacy vs data security 

* Privacy landscape in Singapore 
  * PDPA 
  * PSDSRC – privacy-related measures 
  * IM8
  * Public sector Data Protection Review Committee, 

* PP-Tech Overview 
  * Data anon, FL, homomorphic, DP, SMPC, ZKP, synthetic data
  * Pros, Cons, sample use cases 
* Kahoot Quiz

### Hands-On (26 January 2022 3:30-5:30pm): Syahri & Ameera
* Workshop Background & Setting Up
* Hashing
* Tokenisation
* Field Level Encryption
* Generating Synthetic data
* K-anonymity 
* Conclusion

---

## Quickstart Guide
The workshop will be conducted using Jupyter Notebook, follow the instructions below and ensure that you have all the required libraries installed for a smooth-sailing workshop :)!

### (1) Installing Jupyter Notebook 
If you have Jupyter Notebook installed, you may skip this section.

1. Install python
* Go to https://www.python.org/downloads/
* Download installer for your OS and install

2. Install Jupyter with pip
If you use pip, you can install it with:
```
pip install jupyterlab
```

**OR**

1. Using Anaconda
* Go to https://docs.anaconda.com/anaconda/install/
* Download installer for your OS
* Install anaconda with Python

2. Install Jupyter with conda
If you use conda, you can install it with:

```
conda install -c conda-forge jupyterlab
```
--
### (2) Downloading workshop materials and data into local storage

#### Using git clone (**Note**: git must be already installed on your machine)
1. go to the directory path you want to download to
2. run command `git clone https://github.com/dsaidgovsg/data-privacy-workshop.git`

**OR**

#### Via github website
1. go to https://github.com/dsaidgovsg/data-privacy-workshop
2. click on `code` -> `download zip`
3. extract the downloaded zip into your desired directory path

--
### (3) Installing python dependencies
1. go to the directory which you have downloaded the files
2. open terminal/powershell at directory `<your download path>`
3. execute `pip install -r requirements.txt`

--
### (4) How to start jupyter notebook
1. open terminal/powershell at directory `<your download path>`/workshop/
2. execute `jupyter notebook`
3. on Jupyter web application, open the respective files required during the Workshop by clicking on it

---

## Contributors
Main: @dsaid-xj, @syah-ri, @ameeraadam, @tangalan
Support: DSAID - Data Engineering Team
