Natural Language Processing
================================================================

Lets use HuggingFace Library to perform various NLP tasks using open source models. These tasks are highly related to how humans interact and 
famous Transformer architecture is the heart of all the NLP models. We can take any pretrained models and finetune on our collected dataset.

NLP tasks
----------------

* **Text Feature Extraction :**
  get sentence (sequence of tokens) represented as sequence of numerical vectors which carry some information

* **Mask Filling :**
  missing word prediction, helps you get statistical understanding of the language

* **Question Answering / Chatbot :**
  answer retreival from a load of documents (knowledge base or context or open book), also generating generic answers without context (documents or closed book),
  Open-domain models are not restricted to a specific domain, while closed-domain models are restricted to a specific domain (e.g. legal, medical documents). 

* **Sentence Similarity :**
  Tells how close two texts are, input text is converted to a vector embedding which captures a semantic meaning. Used in information retreival (search)
  and clustering. Sentence-transformers library is popularly used for paragraph or document search followed by sentence level search

* **Summarization :**
  Produce compact version of given document/text, either we can extract extract text from given document or we can also generate a new summarized text.
  Used in summarizing research papers or news articles

* **Table Question Answering :**
  Given a dataset (JSON, CSV, SQL DB), convert to pandas dataframe and then either SQL executions or retreival of information from table

* **Text Classification :**
  Assigning labels to text, used in hate speech classification, disaster identification using tweets, assessing grammatical correctness,
  new product/movie sentiment classification using reviews, Assertion & Reasoning

* **Text Generation :**
  Given a small text, generate the next few tokens based on input text context. popular use case is story generation, machine code generation or 
  very popularly instruction models like ChatGPT, chatbots with role defined

* **Token Classification :**
  Assigning labels at the word level, used in Named entity recognition to get names places dates etc, Part of speech tagging to get verbs punctuations etc
  Popular application is Information Extraction from Invoices (invoice image first passed through OCR system)

* **Language Translation :**
  One language to another target language machine translation, multilingual models are available, common use case is to process chatbot inferences

* **Zero Shot Classification :**
  Directly working on our application without finetuning or training underlying model again

Coding Notebooks
--------------------

.. nbgallery::

  ../notebooks/2_NLP_CHATBOT.ipynb
  ../notebooks/2_NLP_QA.ipynb
  ../notebooks/2_NLP_TABLE_ANSWER.ipynb
  ../notebooks/2_NLP_TRANSLATION.ipynb