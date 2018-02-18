# PDFparser

This is a PDF parser built by github.com/drewsb, myself, and github.com/XueruiFa.

Utilizing open source Apache modules, this application provides an efficient solution to parsing select healthcare PDFs, providing a user interface to select PDF type and how the user would like data to be presented (e.g. CSV, excel)

To Run -> Download project and import to Eclipse or other Java IDE, import provided jars, and run main

* components -> holds models for PDF pages (dental, medical, and vision) and also contains logic for delegating tasks within the application to smaller and more specific classes
* state folders -> contain logic for each specific state available at the time of development along with the PDF handling for each company within that state
