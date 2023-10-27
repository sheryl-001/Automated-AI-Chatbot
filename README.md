# Automated-AI-Chatbot
Artificial Intelligence Project

PROBLEM STATEMENT
The task is to develop a chatbot application for ABC Engineering College to assist students and parents during the admission process. The chatbot should be designed to provide information, answer frequently asked questions, and guide prospective students and parents through the college's admission procedures. The primary goal of the project is to enhance the admission experience by providing accurate and timely responses to inquiries related to eligibility criteria, admission procedures, required documents, fees, scholarships, admission timelines, hostel facilities, credit transfers, and other admission-related queries.

PROJECT REQUIREMENTS
1.	Create a user-friendly and accessible chatbot interface that allows users to interact with the chatbot seamlessly.
2.	Implement natural language processing (NLP) techniques to understand and interpret user queries, ensuring that the chatbot can respond effectively to a wide range of questions.
3.	Develop an intent recognition system that can categorize user queries into predefined categories such as eligibility, admission process, documents required, tuition fees, scholarships, admission timeline, hostel facilities, credit transfer, and more.
4.	Populate the chatbot with a knowledge base of frequently asked questions and their corresponding responses, covering topics like eligibility criteria, admission procedures, required documents, tuition fees, scholarships, admission timelines, hostel facilities, and credit transfer.
5.	Ensure that the chatbot can provide detailed information about the eligibility criteria for admission, including academic requirements and entrance exam scores.
6.	Guide users through the admission process, explaining the steps involved in submitting applications and required documents.
7.	Inform users about the documents needed for admission, including 12th-grade transcripts, certificates, domicile certificates, and entrance exam scorecards.
8.	Provide information about tuition fees, including variations based on aided, SS, or management quota, and direct users to the account’s office for further inquiries.
9.	Explain the availability of scholarships and financial aid, and provide a contact number for further scholarship-related queries.
10.	Communicate the expected timeline for receiving admission decisions to manage user expectations.
11.	Describe the availability of on-campus housing facilities and guide users on where to inquire about hostel accommodation.
12.	Address inquiries about credit transfers from other colleges or universities, providing contact information for detailed inquiries.
13.	Include a fallback intent to handle queries that the chatbot cannot address, and encourage users to ask alternative questions.

DETAILED ANALYSIS OF TOOLS AND LIBRARIES
1.	Natural Language Toolkit (nltk):
•	Usage: The code begins by importing the nltk library, which is a powerful tool for working with human language data. It provides functions for tokenization, stemming, lemmatization, and more.
•	Functions: The code uses nltk functions like word_tokenize for tokenizing sentences and WordNetLemmatizer for lemmatization.
2.	JSON (json) Library:
•	Usage: The code imports the JSON library to work with JSON data. In this chatbot, JSON is used to store intents and responses, making it easy to manage conversation patterns.
•	Functions: It loads the intents from a JSON file and extracts information from it.
3.	Pickle (pickle) Library:
•	Usage: Pickle is used for serializing and deserializing Python objects. In the code, it's used to save and load vocabulary and class labels (words and classes) to/from binary files.
•	Functions: The code uses pickle to store vocabulary and class information in binary files for easy retrieval.
4.	TensorFlow (tensorflow) and Keras (from keras):
•	Usage: These libraries are employed to create, train, and save a deep learning model for intent classification. Keras is a high-level neural networks API running on top of TensorFlow.
•	Functions: The chatbot model is built using Keras, and TensorFlow is used as the backend. The model is compiled and trained using the Sequential API, and the trained model is saved for later use.
5.	NumPy (numpy):
•	Usage: NumPy is a fundamental package for scientific computing with Python. It's used for efficient numerical operations.
•	Functions: The code utilizes NumPy to manipulate and process data efficiently, particularly when creating the training data.


6.	Tkinter (tkinter):
•	Usage: Tkinter is the standard GUI (Graphical User Interface) library for Python. It's used to create the graphical user interface for the chatbot.
•	Functions: Tkinter is responsible for creating and managing the chat window, input box, send button, and chat log. It enables the chatbot to have a user-friendly interface.
7.	Random (random):
•	Usage: The random library is used for generating random responses from the list of responses associated with a specific intent.
•	Functions: Random selection of responses is used to make the chatbot's interactions more dynamic and human-like.
8.	Other Libraries:
•	WordNet (nltk.stem.WordNetLemmatizer): WordNet is used for lemmatization to obtain the base form of words. It is especially helpful in reducing words to their essential form for processing.
•	Scrollbars and Text Widgets: These are part of the Tkinter library and are used to create the chat window with a scrollbar for smooth scrolling.
Overall, this code utilizes a combination of natural language processing (NLP) libraries, deep learning frameworks, and GUI libraries to create an interactive chatbot that can effectively understand and respond to user queries. The chatbot's underlying model is trained using machine learning techniques to classify intents and generate appropriate responses, making it a valuable tool for providing information and assistance.

OUTCOME
The Automated AI Chatbot serves as a valuable resource for prospective students and parents seeking information and assistance with the admission process at ABC Engineering College. The chatbot is capable of providing accurate, timely, and informative responses to a wide range of admission-related queries, ultimately improving the overall admission experience for all users. Hence, the project has been completed successfully and the output is verified and documented. 

