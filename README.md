## Resume-Analysis-using-spaCy
A Natural Language Processing project to analysis resumes using spaCy  library in Python jupyter notebook.
In this project we are goging to create an NLP model to analysis texts from resumes using spaCy model and also create a skills matcher to fetch required skills.

# Resume Dataset:
A collection of 2400+ Resumes in string as well as PDF format taken from livecareer.com for categorizing a given resume into any of the labels defined in the dataset: [Resume Dataset](https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset)
Inside the CSV:

ID: Unique identifier and file name for the respective pdf.

Resume_str : Contains the resume text only in string format.

Resume_html : Contains the resume data in html format as present while web scrapping.

Category : Category of the job the resume was used to apply.

Present categories are
HR, Designer, Information-Technology, Teacher, Advocate, Business-Development, Healthcare, Fitness, Agriculture, BPO, Sales, Consultant, Digital-Media, Automobile, Chef, Finance, Apparel, Engineering, Accountant, Construction, Public-Relations, Banking, Arts, Aviation
# Acknowledgements
Data was obtained by scrapping individual resume examples from www.livecareer.com website. Web Scrapping code present in my Github Repo.
## Jobzilla skill patterns
The [jobzilla skill](https://github.com/kingabzpro/jobzilla_ai/blob/main/jz_skill_patterns.jsonl) dataset is jsonl file containing different skills that can be used to create spaCy entity_ruler. The data set contains label and pattern-> diferent words used to descibe skills in various resume.
