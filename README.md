# Chat with PDF using Gemini-
This project allows users to upload PDF files and ask questions about their contents. Using Google Generative AI and LangChain, the application processes the PDFs and provides accurate answers based on the text extracted from the documents. The interface is built using Streamlit.

**Features**
1. Upload multiple PDF files.
2. Extract and process text from the PDFs.
3. Use Google Generative AI to answer questions about the PDF contents.
4. Save and load vector stores using FAISS for efficient document similarity searches.

**Installation**

**1. Prerequisites**

Before you begin, ensure you have met the following requirements:
->Python 3.8 or higher
->An API key for Google Generative AI

**Steps**

STEP 1: Install Required Packages

**COMMAND**: pip install -r requirements.txt

STEP 2: Set Up Environment Variables: Create a '.env' file in the root directory and add your Google API key

**COMMAND**:GOOGLE_API_KEY="your_google_api_key_here"

STEP 3: Run the Application

**COMMAND**: streamlit run app.py

**OUTPUT**

**1.SCREEN AFTER RUNNING**

![image](https://github.com/samridha04/PDF-LLM-/assets/141304603/fe745270-cf0a-411c-ac8c-85bafaa10b68)

**2.AFTER UPLOADING**

![image](https://github.com/samridha04/PDF-LLM-/assets/141304603/7cd9fcec-0db8-4de7-a5a0-ccb62d0e52ac)

**3.AFTER GETTING RESPONSE**

![image](https://github.com/samridha04/PDF-LLM-/assets/141304603/e08d4562-6f39-4c3f-9c29-539c8ff6bb5d)








