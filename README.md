# Tokenization-of-Malayalam-Language-Using-Python-For-spaCy
spaCy is an open-source software library for advanced natural language processing, written in the programming languages Python and Cython. spaCy is a relatively new package for “Industrial strength NLP in Python” developed by Matt Honnibal at Explosion AI. Tokenisation is a foundational step in many NLP tasks. Tokenising text is the process of splitting a piece of text into words, symbols, punctuation, spaces and other elements, thereby creating “tokens”. In this project we tried to implement spaCy in Malayalam and perform the task of tokenization. We created datasets, necessary files, performed cythonization to achieve this.
Inorder to implement spacy in malayalam:
   - Created dataset for Malayalam like stopwords, lexical attributes(stopwords.py, lex_attrs.py).
   - Created a file _init_.py which contains Malayalam class definition and importing all the necessary files to implement nlp.
   - Created a file examples.py which contains set of Malayalam sentences.
   - Cythonized all the 4 files. After cythonization we get a copy of all files in .so format.
   - pycache contains copy of files like stopwords,lexical attributes, examples, _init_  in pyc format.
   -Executed examples.py.
   - Imported Malayalam language package in jupyter notebook to do tokenization.
