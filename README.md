# Hindi-English-OCR-with-Keyword-Search

This project demonstrates a Hindi-English OCR (Optical Character Recognition) model using Tesseract OCR and a web interface built with Gradio. The model extracts text from images containing Hindi and English text and allows users to search and highlight keywords in the extracted text.
Features

    Hindi & English OCR: Extracts text from images containing both Hindi and English.
    Keyword Search: Allows searching for specific keywords within the extracted text and highlights them.
    User-Friendly Interface: A simple web-based interface for uploading images and performing OCR, built using Gradio.

Dependencies

To run this project, you need the following:

    Python 3.x
    Tesseract OCR
    pytesseract
    OpenCV
    PIL (Pillow)
    Matplotlib
    Gradio
    Regex (re)

Install the dependencies using:

bash

!sudo apt install tesseract-ocr
!pip install pytesseract gradio opencv-python Pillow matplotlib
!sudo apt-get install tesseract-ocr-hin
!sudo apt-get install tesseract-ocr-eng

How It Works

    Perform OCR: The pytesseract library is used to extract text from an uploaded image.
    Keyword Search: Users can optionally enter a keyword, which will be searched for in the extracted text, and the occurrences will be highlighted.
    Gradio Interface: The project uses Gradio to create a simple web interface where users can upload images and input search keywords.

Running the Project

To run this project locally, follow these steps:

    Install the required dependencies using the commands listed above.
    Clone this repository:

    bash

git clone https://github.com/your-username/hindi-english-ocr.git
cd hindi-english-ocr

Launch the Gradio app:

bash

    python app.py

    Once the app starts, open the URL in your browser and upload an image to extract text or search for keywords.

Example

Here’s how the interface looks:

    Upload Image: The user uploads an image containing Hindi or English text.
    Extract Text: The extracted text is displayed in the web interface.
    Search: Users can search for specific keywords within the extracted text and see the highlighted results.

Usage

    OCR and Keyword Search: This tool can be used for Hindi-English translation tasks, image-to-text extraction, and basic text analysis from images.

Future Enhancements

    Improved Accuracy: Fine-tuning OCR for better accuracy with complex scripts and fonts.
    Support for More Languages: Adding support for more Indian and international languages.
    Translation: Integrating text translation features to convert Hindi text to English and vice versa.

License

This project is licensed under the MIT License.
