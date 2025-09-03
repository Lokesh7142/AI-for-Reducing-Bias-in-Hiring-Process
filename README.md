# AI-for-Reducing-Bias-in-Hiring-Process

Short Description :
An NLP-based system to identify and mitigate biases in job descriptions and resumes. Features include detection of gender, ethnicity, age, personality, and education-related biased language, resume anonymization to protect candidate identity, and skill-based candidate-job matching using semantic similarity algorithms.

FEATURES :
  >>Bias Detection
  >>Resume Anonymization
  >>Skill-Based Candidate Matching
  >>PDF Processing
  >>Interactive Interfaces
  >>Suggestion Generation
  >>Extensible NLP Pipeline

TECHNOLOGIES USED :
  >>Python
  >>Natural Language Toolkit (NLTK)
  >>Regular Expressions (re)
  >>scikit-learn
  >>PyPDF2
  >>Flask
  >>Tkinter
  >>Collections (defaultdict)
  >>ReportLab

*How to Run :
  >>Install dependencies:pip install -r requirements.txt
  >>Download NLTK data:import nltk
                       nltk.download('punkt')
                       nltk.download('stopwords')
  >>Run the command-line interface (CLI):python main.py
  >>Run the web interface:python app.py

*SAMPLE OUTPUT :
1. Bias Detection in Job Description:

Detected Gender Bias (male_biased): ['salesman', 'he']  
Suggested Replacements: ['salesperson', 'they']  

Detected Age Bias: ['energetic']  
Suggested Replacements: ['motivated']  

No Ethnicity or Education Bias Found.

2. Resume Anonymization:
Original Resume Snippet:

John Doe  
Email: john.doe@gmail.com  
Phone: 123-456-7890  
Bachelor of Technology from University of XYZ  

Anonymized Resume Snippet:
[CANDIDATE NAME]  
Email: [EMAIL]  
Phone: [PHONE]  
Bachelor of Technology from [UNIVERSITY]  

3. Skill-Based Candidate Matching:

Semantic Similarity Score: 0.87
Skill Match Percentage: 75%
Extracted Skills from Resume: Python, Machine Learning, SQL, Flask
Matching Skills with Job Description: Python, Machine Learning, SQL

4. Batch Processing:
Processed 5 resumes in directory: resumes/
Results saved to evaluation_report.csv

*Future Improvements
 >>Expand Bias Detection Vocabulary
 >>Advanced Machine Learning Models
 >>Enhanced Resume Parsing
 >>Web Interface Enhancements
 >>Privacy and Security





