# Tamil-Chatbot
Multi language understandable Chatbot, and replies in Tamil  

This Project is a Tamil Bank Chatbot. In this project, the user can interact with the chatbot in any language
they like and this chatbot answers both personal questions and Bank loan related question in tamil. The Tamil translation
is done through the googletrans package.Through this pipleline i detect the language in the text and translate it to english and
use NLTK libraries to filter the stop words or any unnecessary words.

This filtered english content is then feeded to Deep learning Algorithm and output is presented in tamil lanuage.
Also this chatbot can extract the required loan details from the index and navigating to the required page. This process helps us to decrease 
time complexity from O(page nos) to O(Index contents).

I am using a ANVIL user interface to display the message generated from chatbot. This chatbot reads these Loan details from the given pdf file using PyPdf4. the sample loan dicument is uploaded here in this repo

Output are uploaded as .png files in this repo.
