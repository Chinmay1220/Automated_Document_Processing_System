# Scalable, Automated Text Extraction OpenAI based Interactive Query System 

**Project Overview :**
The project focuses on automating the extraction of text from PDFs in the GAIA dataset and developing a client-facing application that enables users to securely interact with the extracted data. In the first part, Airflow pipelines will automate the data acquisition and processing of PDF files, using both an open-source tool like Pymupdf and an enterprise-level service such as Google document ai api for efficient text extraction. This extracted information will be stored in a repository like S3 for easy retrieval. In the second part, the backend will be implemented using FastAPI, featuring secure user registration and login with JWT authentication. Only authenticated users will access the protected endpoints, and the backend will manage all business logic, including querying the preprocessed PDF data. A user-friendly frontend built in Streamlit will allow users to register, log in, and query the data, offering the choice between open-source and API-based PDF extracts. The entire solution will be containerized and deployed on a public cloud using Docker Compose, ensuring seamless, secure access for users.

**Key Technologies :**

Google Cloud Platform, Streamlit, OpenAI, VS code, CodeLabs, Git, Python, Docker, Airflow, FastAPI, JWT

**Desired Outcome or Solution :**

Automate text extraction from GAIA dataset PDFs using Airflow pipelines for efficient data acquisition.

Integrate both open-source(pymupdf) and enterprise (Google Documnet API) options for text extraction.

Ensure extracted data is accurately stored in a data repository (CGP) for easy retrieval.

Develop a client-facing application with FastAPI and Streamlit for user registration, login, and interaction with extracted PDF content.

Secure the application using JWT authentication, protecting all API endpoints except registration and login.

Provide users with a question-answering interface to query specific PDF extracts.

Containerize the FastAPI and Streamlit applications using Docker Compose and deploy them on a public cloud for seamless, scalable access.

**Architecture diagram :**

![image](https://github.com/user-attachments/assets/24c97ffd-f317-44a7-86f9-5198200f8807)



**Contribution :**

WE ATTEST THAT WE HAVEN’T USED ANY OTHER STUDENTS’ WORK IN OUR 
ASSIGNMENT AND ABIDE BY THE POLICIES LISTED IN THE STUDENT HANDBOOK


**Documentation files Team_9** 

**Code labs** - https://codelabs-preview.appspot.com/?file_id=1bWeRfD-PZkUzgzmZkl6oEnWgsRIx5cKflwPPp1grAXk#7

**Google Doc** - https://docs.google.com/document/d/1bWeRfD-PZkUzgzmZkl6oEnWgsRIx5cKflwPPp1grAXk/edit?tab=t.0#heading=h.gjdgxs

**Video** - https://drive.google.com/drive/folders/1u76RGgwkakKqHV_WSMLZuZ8VOHN1u0Xl?usp=drive_link

**Web Link** - http://34.168.71.13:8501
