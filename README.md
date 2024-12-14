# MCQ-Generator-using-AI-Flask-Web-Application-
This project demonstrates the potential of integrating AI with web applications to automate tasks like generating multiple-choice questions from existing content.

# Project Overview

This project is a web application designed to automate the generation of multiple-choice questions (MCQs) from text documents using Google Generative AI. The application supports multiple file formats such as PDF, DOCX, and TXT, and enables users to generate MCQs efficiently from educational content.

The tool is particularly useful for educators, students, and developers who need a quick and effective way to create assessment materials based on existing content. The application is implemented using Python and Flask, with integration of Google Generative AI for question generation.

# Key Features

**Automatic MCQ Generation:** Generate multiple-choice questions directly from uploaded documents (PDF, DOCX, TXT).

**Supports Multiple File Formats:** Upload files in various formats like PDF, DOCX, or TXT for easy document processing.

**User-Friendly Interface:** Simple web interface for uploading documents, specifying the number of questions to generate, and viewing results.

**Text Extraction:** Robust text extraction from PDFs, DOCX, and TXT files for accurate MCQ generation.

**Downloadable Results:** MCQs can be downloaded in both text and PDF formats.

**AI Integration:** Uses Google Generative AI for high-quality, structured MCQs.

# Technologies Used

**Python:** Backend development using Python 3.

**Flask:** Web framework used to build the web application.

**Google Generative AI:** API used to generate MCQs from extracted text.

**pdfplumber:** Used for text extraction from PDF files.

**python-docx:** Used for extracting text from DOCX files.

**HTML/CSS:** Frontend development for a simple user interface.

**JavaScript:** For client-side interactions in the web application.

## How It Works

# Upload a Document:
Users can upload a document in PDF, DOCX, or TXT format through the web interface.

**Specify Number of MCQs:**
The user specifies the number of multiple-choice questions (MCQs) they want to generate.

**Text Extraction:**
The application extracts text from the uploaded document based on its format (PDF, DOCX, or TXT).

**MCQ Generation:**
The extracted text is passed to Google Generative AI, which generates multiple-choice questions from the content.

**Display MCQs:**
The generated MCQs are displayed on the results page with answer options and the correct answer indicated.

**Download Results:**
Users can download the generated MCQs in both text and PDF formats.
Getting Started

**1. Clone the Repository**
git clone https://github.com/username/mcq-generator.git
cd mcq-generator

**2. Install Dependencies**
Install the required Python packages:
pip install -r requirements.txt

**3. Get the Google API Key**
To use Google Generative AI,

obtain an API key by following the steps in the API Key section of the documentation.

Add your API key to the app.py file in the following line:

API_KEY = "your_google_api_key"

**4. Run the Application**
Start the Flask server:

python app.py
Visit the application in your browser at http://localhost:5000/.


Project Structure

/mcq-generator
    /templates
        index.html       # The main page where users upload files and specify MCQ count
        results.html     # Displays generated MCQs and download options
    /static
        /css
            styles.css    # Styles for the application
    app.py                # Flask backend logic for handling requests and interactions
    requirements.txt      # List of Python dependencies
How to Use the Web Application

**Homepage (index.html):**

Upload a document in PDF, DOCX, or TXT format.

Enter the number of MCQs to generate.

Submit the form to generate the questions.

**Results Page (results.html):**
View the generated MCQs with multiple-choice options.

Download the MCQs in either text or PDF format.

**API Key Setup**

# To use the Google Generative AI API, follow these steps:

**Create a Google Cloud Project:**
Go to the Google Cloud Console, select or create a new project.

**Enable the Generative Language API:**
Navigate to "APIs & Services" > "Library" and enable the Generative Language API.

**Create API Credentials:**
Under "APIs & Services" > "Credentials", create a new API Key.

**Add API Key:**
Add your API key in the app.py file to access the Google Generative AI API.

# Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

# License
This project is licensed under the MIT License.


