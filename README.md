# IDS 703 Final Project: Assessing the Effectiveness of Linkedin Company Description in Classifying Industry
*By Ya-Yun Huang, Emma Wang, Heather Qiu*

## Project Description

The primary objective of the project is to evaluate whether company descriptions on LinkedIn are sufficient to identify the type of business. As a prototype, we gathered organizational information from LinkedIn, including company names, profiles, and industries. The current study focuses on three predominant industries: Financial Services, Hospitals & Health Care, and IT Services & IT Consulting. However, our analysis can be scaled to incorporate additional business sectors for broader use cases. For instance, the language models employed in the research provide a good foundation for data applications that seek to generate sample company overviews and/or evaluate the quality of the generated company descriptions. The graph below visualizes popular keywords of LinkedIn organization profiles. The larger the size of the word, the more frequently it appears in the dataset.

![output](https://user-images.githubusercontent.com/105904149/210687903-040ad67a-8c92-4df7-99fd-106d90ad151d.png)

## Project Files
* **linkedin_company_data.csv**: dataset used.
* **LinkedInCompanyClassification.ipynb**: python code for data cleaning, preprocessing, modeling, and text synthesis.  
* **requirements.txt**: list of all dependencies required to run **LinkedInCompanyClassification.ipynb**.  
* **IDS 703 Final Report.pdf**: project write-up, including details of applied language models. 

## Installation Requirements
Please execute the following commands to install packages necessary to run **LinkedInCompanyClassification.ipynb**: 
```pip install --upgrade pip && pip install -r requirements.txt```
