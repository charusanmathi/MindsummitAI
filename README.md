# MindsummitAI

Mindsummit is an AI-powered application that integrates Google's Gemini Pro to provide an all-in-one solution for: 

1. Answering questions with advanced Q&amp;
2. A capabilities Generating image descriptions and insights 
3. Summarizing lengthy PDF documents 
4. Delivering analytics insights via a dynamic dashboard

## 🔑 Features

1. Q&A
Input any question, and Mindsummit leverages Google's Gemini Pro to deliver fast and accurate answers.

2. Image Generation
Upload an image with or without a custom prompt to receive AI-generated descriptions or details.

3. PDF Summarization
Upload a PDF document, and Mindsummit extracts and summarizes the content to save time.

4. Analytics Dashboard
Visualize app interactions, question categories, and usage patterns through an interactive dashboard.

## Technologies Used

* Python
* Streamlit
* Google Generative AI (Gemini Pro)
* PyPDF2 for PDF handling
* Pillow for image processing
* Matplotlib for data visualization

## 🔧 Installation

### Clone the repository:
````
git clone https://github.com/YourUsername/Mindsummit.git
````
### Install dependencies:
````
pip install -r requirements.txt
````
### Add your Google API Key to a .env file:
````
GOOGLE_API_KEY=your_api_key_here
````
### Run the application:
````
streamlit run app.py
````

