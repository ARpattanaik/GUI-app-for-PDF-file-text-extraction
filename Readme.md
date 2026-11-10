# PDF Text

A graphical application for extracting text from PDF documents.

## Screenshot

Add a screenshot named `screenshot.png` beside this README to show it here.

![PDF Text application screenshot](./screenshot.png)

## Getting started

1. Install Python 3.
2. Open a terminal in the project folder.
3. If the project contains `requirements.txt`, install its dependencies:

	```bash
	python -m pip install -r requirements.txt
	```

4. Run the application's entry-point script (for example, `python main.py`). Use the actual script name in the project if it differs.

## Using the application

1. Launch the application.
2. Select a PDF using the file picker.
3. View the extracted text and use any copy or save options provided by the application.

## About the code

The application combines a graphical interface for selecting a PDF with PDF-processing code that reads text from the document and presents the result. The specific GUI toolkit, PDF library, and available actions depend on the implementation in the source files. Scanned pages may require OCR; basic PDF text extraction may not detect text that exists only as an image.
