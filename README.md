# OCR-Using-EAST

OCR Text Detection and Text Recognition Using EAST
This repo Includes 3 main processes performed 

 1) Text Detection
 2) Text Recognition
 3) Text Summarization/Summation
 
Text Detection is the process where textual context of the Input Images are detected using EAST (Efficient and Accurate Scene Text detector) Pre-Trained model, the text detected image is obtained.
This Process helps in extraction of region of interest (roi) using basic image cropping / numpy array slicing.
Text Recognition is performed on the input image to recognize the text that is detected and it is done using Tesseract-OCR Library (pytesseract library)The Output Image is Obtained.Textual Content detected and recognized in images can also be summarized as in the case of text obtained from a bill/receipt and total amount to be paid can also be obtained.

# INSTALLATIONS - Libraries/Models Used

Opencv - helps in processing of images and is used to develop real time computer vision apps.
Tesseract - open source text recognition engine under Apache 2.0 license, used to extract text from images.
Pytesseract is a wrapper for Tesseract-OCR Engine
EAST - The EAST pipeline is capable of predicting words and lines of text at arbitrary orientations on 720p images, and furthermore, can run at 13 FPS.
