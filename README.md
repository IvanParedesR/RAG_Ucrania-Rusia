# RAG Proyecto resumidor de artículos con AI de OpenAI

## Structure
The structure of the RAG is relatively simple:

* Installation of libraries and import of installed libraries.
  
* Loading OpenAI API keys. For security reasons, I am not including the OpenAI API key. To run it, you will need to generate an API key and insert it.

* Load a database with text without embeddings; the CSV database includes: 10 papers about of the Ukranian - Russia War.

* Generate embeddings with the text. Embeddings are numerical representations that capture the similarities and relationships between concepts.

* Define specific functions to perform the search, define the response message, and respond.

* Perform the search.

## Background
This script is the fourth iteration of the RAG. Each of the previous RAGs had unacceptable errors. T-1.

## Future Adjustments
There are three main improvements I need to make:

* Generate a graphical interface, probably using Flask.
* Expand the database.
* Modify the model to respond using other AIs.

## Usage Instructions
* Load the database included here and then run the attached script. IT IS IMPORTANT TO INCLUDE YOUR OPENAI API KEY; OTHERWISE, IT WILL NOT WORK.
