# DATA 606 - Capstone Project

**Ujjwal**

**Data Science Department**

**University of Maryland, Baltimore County**

> ***UMBC Global Ambassador***

> ***Grduate Grader (Data Science)***

## About me
I am a passionate and a motivated professional with sheer interest in Data Science and Machine learning. Proficient in data cleaning and transformation, I am adept at conducting statistical analysis to derive data-driven insights and develop machine learning models. I am eagerly looking to join an organization where I can add value and make notable impact through my competent problem solving skills.

## Capstone Project Title
**Document Classification using OCR (Optical Character Recognition) and NLP (Natural Language Processing) - A Multimodal Approach**

## Project Draft Proposal
**1. What is your issue of interest (provide sufficient background)?**
   - My issue of interest is Document Classification and I want to work on developing a state of art application that can classify a Document using Computer Vision, Optical Character Recognition (OCR) and NLP (Natural Language Processing).
   - "Document classification is a process of assigning categories or classes to documents to make them easier to manage, search, filter, or analyze. A document in this case is an item of information that has content related to some specific category. Product photos, commentaries, invoices, document scans, and emails all can be considered documents." [1]
   - Document Classification task can also be perceived as a collaborative task dealing with text classification and visual classification because a document has an associated visual structure and texts related to its domain.
   - "Text classification concerns defining the type, genre, or theme of the text based on its content. Depending on the task, complex techniques like NLP can be used to analyze words and phrases in context and understand their semantics (meaning)."[1]
   - "Visual classification focuses on a visual structure of documents, employing computer vision and image recognition technologies."[1]
![alt text](https://github.com/ujjwalbb30/Ujjwal_DATA606/blob/main/1.PNG)

**2. Why is this issue important to you and/or to others?**
   - Document Classification has become crucial for various kinds of organizations, whether business or government, as "it not only helps us in saving information but also helps us find these documents whenever required."[2]
   - It is becoming an increasingly effective way for collection and storage of data that can become a rich source of business analytics. For example, "A customer services team might use document classification to ensure incoming support tickets go to the right individual. An accounting firm might use invoice classification to assign expenses to the correct department."[2]
   - But with the vast amounts of data being added to the digital storage space, it is becoming more and more difficult to classify them manually. Hence, an automated approach is required to address this issue.
   - With the rise of automation especially in industries, this field seems really promising to me. It is fast, efficient and it frees up human resources for better brainstorming works in any organization.
   - I have already worked on image processing and natural language processing and I feel that working on a data science and machine learning problem that entails the use of both of these aspect, will equip me for future multimodal AI tasks. 

**3. What questions do you have in mind and would like to answer?**
   - I want to find how the manual document classification compares to automated document classification.
   - I want to understand how automated document classification can impact an organization.
   - I want to explore whether a Multimodal approach of combining Computer Vision, OCR and NLP will give better results in document classification, than using each of these aspects individually.

**4. Where do you get the data to analyze and help answer your questions (credibility of source, quality of data, size of data, attributest of data etc.)?**
   - A number of researchers have worked on this problem previously leading to wonderful datasets available for promoting research in this field.
   - I have found the following datasets useful for my problem statement:
   - https://www.kaggle.com/patrickaudriaz/tobacco3482jpg : 2GB dataset with 3492 files, consisting of 10 kinds of documents. categories - (ADVE, Email, Form, Letter, Memo, News, Note, Report, Resume, Scientific). This dataset is introduced in "Jayant Kumar, Peng Ye and David Doermann. "Structural Similarity for Document Image Classification and Retrieval." Pattern Recognition Letters, November 2013".
   - https://www.kaggle.com/shaz13/real-world-documents-collections : 475 MB dataset with 5000 files, consisting of 16 kinds of documents. categories - (Specification, Email, Advertisement, Handwritten, Scientific Report, Budget, Scientific Publication, Presentation, File Folder, Memo, Resume, Invoice, Letter, Questionnaire, Form, News Article). 
   - 

**5. What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect?**
   - Unit of analysis will be various kinds of documents e.g. Email, Form, Letter, Memo, Scientific Report, etc.
   - The combined dataset is around 2.5 GB consisting of 8492 documents in total.

**6. What variable/measures do you plan to use in your analysis (variables should be tied to the question in #3)?**
   - To compare manual document classification with automated document classification, I can try to find the error rates in both the approach.
   - Automated Document Classification can be considered a type of automation. I can try to measure that by automation's impact on productivity of an organization.
   - For modeling purpose, I can initially try to classify the documents using just one approach i.e. either NLP or Computer Vision. Then I can try to use the features from both approach to make a Multimodal system. Finally, I can observe which one performs better.

**7. What kind of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?**
   - I plan to use NLP, OCR, Computer Vision and Deep Learning Neural Networks for modeling purposes.
   - I can use OCR to extract the text of the document, preprocess the retrieved text and vectorize it to build features.
   - I can use CNN to retrieve the visual attributes of the documents.
![alt text](https://github.com/ujjwalbb30/Ujjwal_DATA606/blob/main/2.PNG)

**8. How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?**
   - Since, it is a classification problem, I can use the one of the following performance metrics to evaluate my models:
   - Accuracy
   - Precision 
   - Recall (or Sensitivity)
   - F1-score
   - Specificity

**9. What outcomes do you intend to achieve (better understanding of the problems, tools to help solve problems, predictive analytics with practicle applications, etc.)?**
   - I intend to develop a state of the art multimodal document classifier which can leverage both types of data i.e. visual and text for making the final prediction.


# References
[1] https://www.altexsoft.com/blog/document-classification/

[2] https://nanonets.com/blog/document-classification/

[3] https://medium.com/@MohammedS/performance-metrics-for-classification-problems-in-machine-learning-part-i-b085d432082b
