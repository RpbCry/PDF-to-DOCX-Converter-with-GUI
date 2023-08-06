# PDF to DOCX Converter with GUI
This Python script provides a simple graphical user interface (GUI) to convert PDF files into DOCX files. The script allows you to select a PDF file and choose an export directory for the converted DOCX file. The conversion process is handled by the pdf2docx library, making it easy to convert PDF documents to editable DOCX format effortlessly.

## Requirements
Python 3.x
PySimpleGUI library
pdf2docx library
Ensure that you have Python installed on your system and install the required libraries by running the following command:

````
pip install PySimpleGUI pdf2docx
````

## How to Use
Clone or download the repository to your local machine.

Open a terminal or command prompt and navigate to the directory where the script is located.

Run the script using the following command:

````
python pdf_to_docx_converter.py
````

The GUI window will open, prompting you to select a PDF file and an export directory for the generated DOCX file.

Click the "Convert" button to start the conversion process. Upon successful conversion, a pop-up will display the location of the newly created DOCX file.

You can exit the application by clicking the "Exit" button or closing the window.

## How it Works
The script utilizes the PySimpleGUI library to create a user-friendly GUI. When you click the "Convert" button, the convert_pdf_to_docx function is called, which performs the actual conversion using the pdf2docx library.

The conversion process involves parsing the selected PDF file and creating a corresponding DOCX file with the same name in the specified export directory. Any errors encountered during the conversion process will be displayed in a pop-up window.

## Contributions
Contributions are welcome! If you have any ideas, bug fixes, or improvements, feel free to submit a pull request or create an issue.

## License
This project is licensed under the MIT License.

## Disclaimer
This script is provided as-is and without any warranties. The author is not responsible for any damages or issues caused by the use of this script.
