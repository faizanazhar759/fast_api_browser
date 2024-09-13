# FastAPI Image Uploader and FAQ App

## Overview
This is a beginner-friendly project built using **FastAPI**. It demonstrates how to create a simple web application with:
1. Image Upload: Select an image from your computer and upload it to convert the image to black and white.
2. FAQ Section: Answer frequently asked questions like your name and age.

### Features:
- **FastAPI** for building the backend.
- **HTML & CSS** for the frontend.
- **Pillow** to process the images (convert to black and white).
- Basic FAQ for user interaction.

## Installation & Running the Project
### Prerequisites:
- Python 3.7+
- FastAPI
- Uvicorn
- Pillow
- Requests

### Instructions:
1. Clone the repository:
   ```bash
   git clone https://github.com/faizanazhar759/fast_api_browser.git
   cd fast_api_browser
    Install dependencies:

#### bash

pip install fastapi uvicorn pillow python-multipart

Run the server:

#### bash

    uvicorn main:app --reload

    Open your browser and go to http://127.0.0.1:8000.

 ### Open another terminal
 #### bash
      python3 app.py (for linux )
      open new tab on your browser and go to the http://127.0.0.1.5000.
Demo:

    Browse an image, upload it, and see it converted to black and white.
    Ask simple questions like "What is your name?" in the FAQ section.

   ### NOTE:
This is just frequently ask question made with simple if else statement. If you want to add more answer you have to change it .
