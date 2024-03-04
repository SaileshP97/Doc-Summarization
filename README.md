# Doc-Summarization

○ The initial motive of this project was to create a mobile app that will scan a
document and provide relevant summary for faster and better
understanding of the document.

○ I used Google's open-source tesseract-ocr package for scanning text from
the image of the document.

○ And after scanning the text I passed it through the HuggingFace
summarization pipeline.

○ I used the facebook/bart-large-cnn model for a summarization task.
