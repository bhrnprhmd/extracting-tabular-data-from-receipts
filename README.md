# extracting-tabular-data-from-receipts
This code uses pytesseract to convert images to text data, and then extracts the useful information.

image to csv.ipynb contains a function called img_to_csv, that takes the image file name as an input (e.g. 'Image.PNG') and returns a dataframe called 'output'. 
It also saves 'output' as 'output.csv' on your desktop.

This function uses pytesseract as the OCR tool in order to convert images to textual data. 
In order to run the function, you need to have tesseract-OCR and pytesseract installed on your device. 
When the installation is done, you need to point pytesseract at the tesseract installation path. 
(Example: pytesseract.pytesseract.tesseract_cmd = r'C:\Users\Peter\Anaconda3\envs\tesseract\Library\bin\tesseract.exe') 
The pointing command is already provided on the script, you just have to copy the path from your computer and paste it to the script.


Please visit the following link if you faced any issues while installing pytesseract:
https://pythonforundergradengineers.com/how-to-install-pytesseract.html
