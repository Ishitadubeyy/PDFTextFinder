PDF Text Highlighter

This Python script allows you to upload a PDF file in a Google Colab environment, search for a text string (case-insensitive) inside the PDF, highlight all occurrences of the search text, and download the highlighted PDF back to your local machine.



FEATURES:
1.Upload PDF files interactively in Google Colab.

2.Search for any string in the PDF text (case-insensitive).

3.Highlight all found instances in the PDF.

4.Download the modified PDF with highlights.

5.Shows the number of instances found and pages where the text appears.

6.Handles errors like invalid file format or empty search strings gracefully.




REQUIREMENTS:
1.Google Colab environment (to use the file upload/download features).

2.Python 3.

3.PyMuPDF library (fitz) for PDF processing.




USAGE:
1.Upload PDF: The script will prompt you to upload a PDF file from your local machine.

2.Enter Search String: After uploading, you will be asked to enter the string you want to search and highlight inside the PDF. The search is case-insensitive.

3.Highlighting: The script processes the PDF, highlights all found instances, and creates a new output file with _highlighted appended to the original filename.

4.Download: The modified PDF is automatically offered for download. If it doesn’t start, check your browser’s download permissions or the Colab file browser.




SAMPLE DEMO:
View on Google Drive](https://drive.google.com/file/d/1mDvIrYVBGRoaw9HeQfzwPI96o3XXOdAT/view?usp=sharing)
