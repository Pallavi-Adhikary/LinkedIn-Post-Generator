# **GenAI-LinkedIn-Post-Generator** 

**Check it out here**
https://pallavi-adhikary-linkedin-post-generator-main-dj4p5x.streamlit.app/


## **Project Overview**

A simple tool that uses **generative AI** to help LinkedIn users especially( LinkedIn Influencers) draft new posts based on the **tone, topic**, and **structure** of their older posts. Built using **Python**, **Streamlit**, and the **Groq API**.

## **Why I Built This**

* To understand how **Large Language Models (LLMs)** can be applied to real-world content creation
* To practice **prompt design**, **few-shot learning**, and **API integration**
* To build a **functional** and **user-friendly tool** using Python and Streamlit

## **Problem Statement**

LinkedIn creators often face:

* **Time constraints** while writing frequent posts
* Difficulty maintaining **consistency in tone and structure**
* Limited tools to **automate content creation** using their own writing style

This tool helps address those problems by:

* Analyzing previous LinkedIn posts to **extract writing patterns**
* Letting users choose **topic**, **tone**, and **length**
* Generating new posts using **few-shot learning** with their old content

## **How It Works**

1. Users provide a set of their **past LinkedIn posts**
2. The tool extracts basic metadata like **topic**, **tone**, and **length**
3. Based on selected inputs, it uses a **Groq-powered LLM** to generate a new post that resembles the original writing style

## **Tech Stack**

* **Python**
* **Streamlit**
* **Groq API** (LLM integration)
* **dotenv** for secure key management

## **Challenges Faced**

* Making the output feel **natural** and aligned with user tone
* Handling **prompt and token size** limitations for the LLM
* Selecting the **right past examples** to guide generation
* Keeping the interface **simple and usable** without frontend complexity

## **Key Learnings**

* Used **few-shot learning** techniques to guide LLM outputs
* Extracted **useful structure** from unstructured text
* Worked with **environment variables** and **API key handling**
* Improved understanding of **prompt tuning** and **output control**
* Gained practical experience in building **end-to-end Streamlit apps**

## **How to Run**

### **1. Create Groq API Key**

* Visit: [https://console.groq.com/keys](https://console.groq.com/keys)
* Add it to a `.env` file as:

GROQ_API_KEY="your_key_here"

### **2. Install Dependencies**

pip install -r requirements.txt


### **3. Run the App**

streamlit run main.py

## **Future Improvements**

* Allow **uploading of posts in bulk** (CSV or LinkedIn API integration)
* Add **tone selection** (e.g., formal, casual, educational)
* Enable **export** of generated posts
