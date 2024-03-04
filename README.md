# Doc-Summarization

The initial motive of this project was to create a mobile app that will scan a document and provite relevant summary for faster and better understand of the document.
I used Google's open-source tesseract-ocr package for scanning text from the image of the document. And after scanning the the text I passes it through HuggingFace summarization pipeline. I used facebook/bart-large-cnn model for summarization task.
