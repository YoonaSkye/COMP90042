# Question Answering Project

This project aims to build a predominantly **retrieval based QA system** which can find the answer to a question in the corresponding text span given a question and a document. In this project, **information retrieval, information extraction, and machine learning technologies** are implemented to develop and enhance the QA system.

Initially, a basic QA system was built based on sentence retrieval (**Okapi BM25**), question processing (**Stanford 7 classes Named Entity Recognizer**)and answer extraction (**BIO tags and NLTK trees**). Then enhancements were made to develop a final IR-based QA system based on error analysis. The final QA system performs well on questions which answers are named entities. But for more complex questions, the performance is unsatisfied.

For further improvements, building a pattern-based approach for answer extraction may be helpful. Beside, semantic information could also be utilised to improve answer type detection classifier, such as ‘what’ question. Moreover, neural networks can be a much more effective method for QA.

For further details, pls check the document named 'Final Report'.  
  
  

**University of Melbourne**  
**COMP90042 Semester 1 2018**
