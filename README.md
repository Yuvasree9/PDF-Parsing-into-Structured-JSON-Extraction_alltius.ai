# PDF-Parsing-into-Structured-JSON-Extraction_alltius.ai


This project provides a Python-based tool that parses a PDF file and extracts its contents into a well-structured **JSON format**.  
The extracted JSON preserves the **hierarchical organization** of the document (sections, sub-sections, and content blocks) while clearly identifying different data types such as **paragraphs, tables, and charts**.

---

##  Dependencies & Features

Before running the project, install Python **3.8+** and the following libraries:

- **pdfplumber**  
  *Feature:* Extracts text, characters, and tables from PDFs.

- **fitz (PyMuPDF)**  
  *Feature:* Detects images/charts embedded in PDFs.

- **json**  
  *Feature:* Saves extracted content into structured JSON format.

- **tkinter**  
  *Feature:* Provides GUI dialogs for file selection and saving output.

### Installation Command:
```bash
pip install pdfplumber PyMuPDF
```

##  How to Run

1. Install **Python 3.8+** from the official [Python website](https://www.python.org/).  
2. Install the dependencies listed above.  
3. Save the script file as `pdf_to_json.py`.  
4. Run the script:
   ```bash
   python pdf_to_json.py
   ```
5. A GUI dialog will open:

- Select the PDF file you want to parse.  
- Select the location to save the extracted JSON file.  
- Once processed, you will see a success message, and the JSON file will be saved.  

---

##  Key Components

- **Section & Sub-Section Detection** → Identifies headings by analyzing font size and bold text.  
- **Paragraph Extraction** → Groups text under respective sections/sub-sections.  
- **Table Extraction** → Uses `pdfplumber` to extract and clean tables.  
- **Chart/Image Detection** → Uses `PyMuPDF` to detect images and charts inside the PDF.  
- **GUI Workflow** → Easy-to-use interface for selecting files and saving JSON.  
- **Structured JSON Output** → Organizes PDF content by page with clear data types.  

---

##  Author  

Developed by **Yuvasree Thupalli**   
Recent CS Graduate in Artificial Intelligence, Sri Venkateswara University, Tirupati.  
Passionate about **AI, Machine Learning, Machine Cognition and loves Data**.  
If you have any queries and for feedback, drop a message here - [MailME](mailto:yuvasree.t9@gmail.com)

