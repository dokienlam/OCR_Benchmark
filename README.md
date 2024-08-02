<H1 align="center">OCR_Benchmark</H1>

<H3 align="left">Processing Steps</H3>
Tool: Tesseract OCR, one of the most popular open-source OCR tools.
Input: A PDF with 55 pages, each page converted to an 800 DPI image.
Process:
Convert each PDF page to an image.
Use Tesseract OCR to extract text from each image.
Combine the extracted text from each page into a final output file.

<H3 align="left">About dataset</H3>
Dataset Description
Number of Pages: 55 pages.
Format: PDF.
Content: Processed by Tesseract OCR to extract text from images.
Resolution: 800 DPI (Dots Per Inch). High resolution increases OCR accuracy but also requires more time and resources.
Dataset: https://www.kaggle.com/datasets/lamdo2k3/pdf-dataset-ocr 

<H3 align="left">Processing Time</H3>
Total Time: 8 minutes to complete the OCR process for the entire 55-page PDF at 800 DPI.
Average Time: Approximately 8.7 seconds per page.

<H3 align="left">Factors Affecting Processing Time</H3>
Resolution: 800 DPI is a very high resolution, which increases accuracy but also processing time.
System Configuration: Performance of the CPU, RAM, and multi-threading capabilities (if used).
Image Quality: Noisy or low-quality images require more resources to process.
Tesseract Configurations: Specific Tesseract settings (e.g., language, analysis mode).

<H3 align="left">Benefits and Challenges</H3>
Benefits: High resolution improves the accuracy of text recognition, especially for complex documents.
Challenges: Requires more system resources and longer processing times compared to lower resolutions.
