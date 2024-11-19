# JD_based_Cold_Email_Generator

![image](https://github.com/user-attachments/assets/d38b226b-2606-426e-a28d-3faf268e64bb)

Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions.

Imagine a scenario:
- A company XYZ needs a Software Engineer and is spending time and resources in the hiring process, on boarding, training etc
- ABC is Software Development company can provide a dedicated software development engineer to XYZ. So, the business development executive from ABC is going to reach out to XYZ via a cold email.


## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run main.py
   ```
