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
1. What is your issue of interest (provide sufficient background)?
   - My issue of interest is Document Classification and I want to work on developing a state of art application that can classify a Document using Computer Vision, Optical Character Recognition (OCR) and NLP (Natural Language Processing).
   - "Document classification is a process of assigning categories or classes to documents to make them easier to manage, search, filter, or analyze. A document in this case is an item of information that has content related to some specific category. Product photos, commentaries, invoices, document scans, and emails all can be considered documents." [1]
   - Document Classification task can also be perceived as a collaborative task dealing with text classification and visual classification because a document has an associated visual structure and texts related to its domain.
   - "Text classification concerns defining the type, genre, or theme of the text based on its content. Depending on the task, complex techniques like NLP can be used to analyze words and phrases in context and understand their semantics (meaning)."[1]
   - "Visual classification focuses on a visual structure of documents, employing computer vision and image recognition technologies."[1]

2. Why is this issue important to you and/or to others?
   - Document Classification has become crucial for various kinds of organizations, whether business or government, as "it not only helps us in saving information but also helps us find these documents whenever required."[2]
   - It is becoming an increasingly effective way for collection and storage of data that can become a rich source of business analytics. For example, "A customer services team might use document classification to ensure incoming support tickets go to the right individual. An accounting firm might use invoice classification to assign expenses to the correct department."[2]
   - But with the vast amounts of data being added to the digital storage space, it is becoming more and more difficult to classify them manually. Hence, an automated approach is required to address this issue.
   - With the rise of automation especially in industries, this field seems really promising to me. It is fast, efficient and it frees up human resources for better brainstorming works in any organization.
   - I have already worked on image processing and natural language processing and I feel that working on a data science and machine learning problem that entails the use of both of these aspect, will equip me for future multimodal AI tasks. 

3. What questions do you have in mind and would like to answer?
   - I want to find how the manual document classification compares to automated document classification.
   - I want to understand how automated document classification can impact an organization.
   - I want to explore whether a Multimodal approach of combining Computer Vision, OCR and NLP will give better results in document classification, than using each of these aspects individually.

4. Where do you get the data to analyze and help answer your questions (credibility of source, quality of data, size of data, attributest of data etc.)?
   - A number of researchers have worked on this problem previously leading to wonderful datasets available for promoting research in this field.
   - I have found the following datasets useful for my problem statement:
   - https://www.kaggle.com/patrickaudriaz/tobacco3482jpg : 2GB dataset with 3492 files, consisting of 10 kinds of documents. categories - (ADVE, Email, Form, Letter, Memo, News, Note, Report, Resume, Scientific)
   - https://www.kaggle.com/shaz13/real-world-documents-collections : 475 MB dataset with 5000 files, consisting of 16 kinds of documents. categories - (Specification, Email, Advertisement, Handwritten, Scientific Report, Budget, Scientific Publication, Presentation, File Folder, Memo, Resume, Invoice, Letter, Questionnaire, Form, News Article)

5. What will be your unit of analysis (for example, patient, organization, or country)? Roughly how many units (observations) do you expect?
   - Unit of analysis will be various kinds of documents e.g. 
   - I have come across datasets varying from 500 MBs to 70 GBs. I am trying to narrow down the part of my analysis to avoid any unnecessary compute intensive tasks.

6. What variable/measures do you plan to use in your analysis (variables should be tied to the question in #3)?
   - For initial analysis purposes I want to observe the difference in the waveform of audios based on gender, dialect, accent, etc.
   - For modeling purpose, I want to observe how current models perform for each individual class. For example, are the current ML models more confident in predicting male voices then female voices, or which dialect is easily recognized and which isn't, etc.

7. What kind of techniques/models do you plan to use (for example, clustering, NLP, ARIMA, etc.)?
   - I plan to use NLP and Deep Learning models for classification and prediction purposes.

8. How do you plan to develop/apply ML and how you evaluate/compare the performance of the models?
   - Initially I aim to compare them on the basis of accuracy score.

9. What outcomes do you intend to achieve (better understanding of the problems, tools to help solve problems, predictive analytics with practicle applications, etc.)?
   - I intend to develop a state of the art multimodal emotion detector or sentiment detector which can leverage all 3 types of data i.e. audio, visual and text.


# References
[1] https://www.altexsoft.com/blog/document-classification/
[2] https://nanonets.com/blog/document-classification/
[3] 
