# AI-powered-Resume-Shortlister
**Description:**  
ResumeMatcher is a machine learning project designed to streamline process of matching resumes to job descriptions with improved accuracy and efficiency. This tool leverages advanced natural language processing (NLP) techniques to analyze and pair resumes with relevant job descriptions based on their content and relevance. By using clustering, cosine similarity, and classification algorithms, ResumeMatcher provides a robust and scalable solution for talent acquisition and recruitment processes.  

### **Key Features:**  
1. **Resume and Job Description Processing:**  
   - Extracts and cleans text data from resumes and job descriptions.  
   - Converts textual data into embeddings using techniques like TF-IDF and clustering for dimensionality reduction.  

2. **Job Description Clustering:**  
   - Groups similar job descriptions into clusters to reduce redundancy and improve processing efficiency.  
   - Ensures each job description cluster captures distinct job roles.  

3. **Intelligent Pairing:**  
   - Pairs resumes with job descriptions based on their content similarity using cosine similarity.  
   - Automatically labels the pairs based on their relevance (selected/not selected).  

4. **Classification Model:**  
   - Trains a machine learning model to classify the pairs into "selected" or "not selected."  
   - Provides high accuracy and interpretable results for decision-making.  

5. **Output Dataset:**  
   - Generates a final dataset containing `resume_name`, `job_name`, and a `selection` label for further analysis.  
   - Easily exportable for HR teams or further application-specific usage.  

### **Use Cases:**  
- Recruitment automation: Streamlining the process of shortlisting candidates for open job positions.  
- Skill-matching: Matching resumes to job descriptions based on skills and experience.  
- Talent acquisition: Building pipelines for identifying and categorizing potential hires.  

### **How It Works:**  
1. **Input Data:** A folder containing resumes and a dataset of job descriptions.  
2. **Preprocessing:** Cleans and vectorizes the text data to make it machine-readable.  
3. **Clustering:** Groups job descriptions into meaningful clusters.  
4. **Fusion and Labeling:** Pairs resumes with clustered job descriptions and assigns relevance labels based on similarity metrics.  
5. **Classification Model:** Trains and evaluates a machine learning model to predict the relevance of pairs.  
6. **Output:** A refined dataset that can be used for job matching or further analysis.  

**This project demonstrates the practical use of machine learning for HR analytics and recruitment optimization.**  
