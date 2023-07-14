# SPEECH-ENHANCEMENT-USING-NLP

**NLP:**

Natural language processing is an area of computer science and artificial intelligence that deals with computer-human language interaction.The study of mathematical and computer modelling of many aspects of language, as well as the development of a wide range of systems, 
is known as natural language processing. The spoken language systems, which combine speech and natural language, are among them.
Because many elements of computer science deal with linguistic aspects of computation, natural language processing plays a role.
Natural language processing (NLP) is a field of study and application that looks at how computers can interpret and modify natural language text or speech in order to 
perform useful tasks.

**FIELD OF USE:**

   The applications of Natural language processing includes fields of study, such as machine translation, natural language text processing and 
summarization, user interfaces, multilingual and cross language information retrieval (CLIR), speech recognition, artificial intelligence(AI) and expert systems.

**OBJECTIVE OF OUR PROJECT:**

We used NLP in education field  to improve the vocabulary skills of the students. By identifying the mistakes of students in their pronounciation and  we help them to rectify their mistakes by themselves.

**Libraries Used:**

•pyaudio 

•numpy

•Speech-recognition

•pyttsx3

•pipwin

•nlp

•transformers

•pytorch

•fasttext

•nltk-punkt

    
**WORK FLOW:**

• Installl all the above mentioned libaries into the python environment.

• Then feed the project first with the audio input and text input from the user/student.

• Then we process the audio file into into a standard .wav format and .pdf file into a text .txt file to get better result.

• Once after conversion of respective files, using speech_recogniser we convert the audio file into a txt file.

• Once the text data is stored we need check the similarity between converted text data with actual input text file given using NLP before that we need remove punctuations in the data.

• To remove punctuations we use regrex module and we remove all special chracters from the actual input given.

•Then the converted text data  is checked the actual text data using BertModel from NLP.

•BertModel it first tokenise the each word in the text file into tokens using "BertTokenizer" and after that it converts each tokens to vector representations known as "Wordembedddings".

•Once after that each converted vector representatuons are compared with respecteive representations and finallly percentage result 
