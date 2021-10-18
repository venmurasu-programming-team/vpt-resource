# Project Ideas

Below are few of the potential Projects that the teams can take up. The underlying theme of the projects is Natural language processing and more specifically focusing on Indic languages.


## 1. Replicate Indic Language NLP model generation of AI4Bharat
Most of the existing open source libraries use prebuilt models or use sources that are either hard to reassemble. Also most of them focus on high resource languages (English, French, Spanish etc.,). 

AI4bharat provides documentation and link to the source from where the models are generated. Replicating the process to build the model will help validating the approach and potentially helps understanding the end-to-end process of data collection, pre-processing, parameters involved.


### Process
* Follow steps detailed in IndicTrans repository

### Validation
* Validate by comparing against the generated model with the Ai4Bharat model

### Links
* Ai4Bharat repositry https://github.com/AI4Bharat/indicTrans
* Corpus to build the model https://indicnlp.ai4bharat.org/samanantar


## 2. Finetune AI4Bharat model with domain specific corpus
The Indic language model is primarily built on data from news sites and from wikipedia. So while it's adequate for general translation requirement for any domain specific translation needs it falls short e.g., law, medical etc., The domain specifc terms might not have been modeled.

We could attempt to focus on the literary domain.

### Process
* Collate corpus from literary domain where parallel translation exist 
* Process text (sentence alignment, parameter tuning)

### Validation

* Compare with test or goldstandard data with or without fine tuned model

### Links 
* Steps to Finetune the model https://github.com/AI4Bharat/indicTrans#finetuning-the-model-on-your-input-dataset



## 3. Optical Character Recognition (OCR)
Most of the important texts are still locked in hard copies and out-of-print. While many of them are being digitized and made available as images they can't be searched and processed further. OCR is the way to create electonic copy of the texts. 

### Process
* Idenitfy text for OCR. 
* Create text specific model
* Process text
* Cleanup text

### Validation
* Compare against the manually created sample

### Links
* Abhidhana Chintanmani https://www.tamildigitallibrary.in/book-detail.php?id=jZY9lup2kZl6TuXGlZQdjZIdlJxy
* Tesseract OCR https://github.com/tesseract-ocr/tesseract
* Fine Tune Tesseract for the new font 

## 4. Tamil lexicon/Dictionary
Create an online version of Madras Lexicon

### Links
* Dictionary maker https://github.com/knadh/dictmaker
* Metaphone for tamil https://github.com/cmrajan/taphone
* Madras Lexicon

## 5. Search functionality using Bluge 
Implement a  full text search functionality using Bluge https://github.com/blugelabs/bluge. This can be used to add search functionality to any content site. 
An example for such functionality is implemented in venmurasu (https://venmurasu.in/search?q=). 
### Links
* Existing Venmurasu search https://github.com/venmurasu/venmurasu-search 
* Bluge https://github.com/blugelabs/bluge

## 6. Index generation for Venmurasu
Venmurasu (http://venmurasu.in) novel series has about 3.4 million words used. This project will create a index of the words and creates a reference.

### Links
* Venmurasu http://venmurasu.in

## 7. Automated audio book for Venmurasu novel series
Create audio book for the Venmurasu novel series using machine learning


