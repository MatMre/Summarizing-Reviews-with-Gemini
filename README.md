# **Summarizing Yelp Reviews with Google Gemini AI**

## **Team MATTA**  
**Contributors**: Matteo Meier, Adrian Sanchez, Timothy Phan, Ty Hershberger, Aaron Tu  

---

## **Project Overview**
This project focuses on **summarizing Yelp reviews** efficiently using Google Gemini AI. By utilizing robust data wrangling techniques, we transform raw Yelp datasets into clean, structured tables to generate meaningful and concise review summaries. The goal is to streamline the process of choosing restaurants by summarizing key pros and cons from user reviews, saving time and enhancing the user experience.

---

## **Project Goals**
1. **Wrangling Notebook**: Transform and clean raw Yelp data into organized tables through structured data wrangling and analysis.
2. **Summarization Notebook**: Leverage Google Gemini AI to generate clear and digestible summaries of Yelp reviews for end-users.

---

## **Files and Notebooks**
### 1. **Final Wrangling Notebook**  
- **Purpose**:  
   Wrangle and organize Yelp data, including restaurant categories, user reviews, and metro-area information.  
- **Key Features**:  
   - Data cleaning, merging, and organizing to form foundational datasets.  
   - Manual structuring and validation of raw data.  
   - Preparation of tables for AI-powered summarization.  

### 2. **Final Summarization Notebook**  
- **Purpose**:  
   Summarize large quantities of Yelp reviews into concise insights using Google Gemini AI.  
- **Key Features**:  
   - Implementation of the Google Gemini API.  
   - Summarization tailored to highlight pros and cons from Yelp user reviews.  
   - Creation of engaging and digestible summaries.  

---

## **Technologies and Libraries Used**
- **Databricks**: For notebook-based development and cloud processing.  
- **Python**: Data wrangling, transformation, and API integration. 
- **Google Gemini AI**: Summarization of processed Yelp review data.

### **Final Summarization Notebook**
- `IPython`  
- `os`  
- `json`  
- `pprint`  
- `pydantic`  
- `typing`  
- `langchain_core`  
- `langchain_google_genai`  

### **Final Wrangling Notebook**
- `pyspark`

---

## **Initializing Databricks Environment Variables**
To use the Google Gemini API and LangChain integration in Databricks, set the following environment variables when starting a cluster:

```bash
GOOGLE_API_KEY=YOUR_GOOGLE_API_KEY_HERE
LANGCHAIN_TRACING_V2=true
LANGCHAIN_ENDPOINT="https://api.smith.langchain.com"
LANGCHAIN_API_KEY=YOUR_LANGCHAIN_API_KEY_HERE
