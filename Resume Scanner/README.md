# Resume-Scanner

### What is CountVectorizer?
- CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors (for using in further text analysis).
### What is Dox2Text?
- docx2txt is a perl based command line utility to convert Microsoft Office(Tm) Docx documents to equivalent Text documents. Capitalisation of text blocks. Center and right justification of text fitting in a line of (configurable) 80 columns.
### About the project :

- A resume scanner that predicts how match a resume matches the job description using Dox2Text to convert dox file into a text and CountVectorizer from Sickit Learn to convert that text into vectors and finally calculate the similarity between the CV and the job Description using cosine similarity.
