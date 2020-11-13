# Highlight Digitizer
Scan or Photograph a physical document highlighted with marker and transfer those highlights to the digital document.

Two main challenges:

## Image recognition
* determine what images to support
** png, jpg etc. can be used in opencv
** pdf (needs to be converted a bunch??)
* open image in python
** opencv for non pdf format
** maybe PyPDF2
** or PyMuPDF
* isolate the highlighted parts
** opencv
* read the highlighted text for matching
** pytesseract worked in test

## PDF manilpulation
* open PDF
* match recognized text to digital text
** PyMuPDF
* add a digital pdf highlight
** PyMuPDF seems to have awesome features
