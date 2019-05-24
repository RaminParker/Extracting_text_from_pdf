# Extracting_text_from_pdf
- Extracting Text from pdf-files. 
- Reading the Table data from pdf
- Merging pdf-files


# Common Python Libraries
Please take a look at this great article from Umer Farooq: https://towardsdatascience.com/python-for-pdf-ef0fac2808b0

### Here is the list of some Python Libraries could be used to handle PDF files

PDFMiner is a tool for extracting information from PDF documents. Unlike other PDF-related tools, it focuses entirely on getting and analyzing text data.

PyPDF2 is a pure-python PDF library capable of splitting, merging together, cropping, and transforming the pages of PDF files. It can also add custom data, viewing options, and passwords to PDF files. It can retrieve text and metadata from PDFs as well as merge entire files together.

Tabula-py is a simple Python wrapper of tabula-java, which can read the table of PDF. You can read tables from PDF and convert into pandas’ DataFrame. tabula-py also enables you to convert a PDF file into CSV/TSV/JSON file.

Slate is wrapper Implementation of PDFMiner

PDFQuery is a light wrapper around pdfminer, lxml and pyquery. It’s designed to reliably extract data from sets of PDFs with as little code as possible.

xpdf Python wrapper for xpdf (currently just the “pdftotext” utility)
