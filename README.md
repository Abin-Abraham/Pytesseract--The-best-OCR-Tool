# Pytesseract--The-best-OCR-Tool

Humans perceive text on an image as text and can read it. By using an OCR tool, we transfer the same intelligence to the computer. Pytesseract is such a helping tool in this field. Pytesseact or elaborately Python tesseract is an open source library developed by google for the sake of optical character recognition. The Library is so much user friendly and it can be used in variety of fields. In my small exploration, this is the best OCR tool that i worked with. 
Speaking about the process of installation, we could use the 'pip' installation process for this library.

$ pip install pytesseract

It can read all image types supported by the Pillow and Leptonica imaging libraries, including jpeg, png,gif, bmp, tiff, and others.Python is a prerequisite to work with pytesseract and installation process is mentioned above. The path of the tesseract does have an impact in the good running of the library. If tesseract is not in your PATH,you will have to change the "tesseract_cmd" accordingly.

The output of the tesseract can be in a number of types. These conversions could be termed as the functions of the good librariy and are mentioned below.

* get_tesseract_version - Returns the Tesseract version installed in the system.
* image_to_string - Returns the result of a Tesseract OCR run on the image to string
* image_to_boxes - Returns result containing recognized characters and their box boundaries
* image_to_data - Returns result containing box boundaries, confidences, and other information. Requires Tesseract 3.05+. For more information, please check the Tesseract TSV documentation
* image_to_osd - Returns result containing information about orientation and script detection.
* image_to_alto_xml - Returns result in the form of Tesseract’s ALTO XML format.
* run_and_get_output - Returns the raw output from Tesseract OCR. Gives a bit more control over the parameters that are sent to tesseract.


