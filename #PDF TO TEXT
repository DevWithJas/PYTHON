#imorting python modules 
import PyPDF2 

pdf_file = open("D:\\PYTHON BASIC PROJECTS\\NS_316.pdf", "rb")
PDF_Reader = PyPDF2.PdfFileReader(pdf_file)
Text = PDF_Reader.getPage(0).extract_text()
print(Text)
