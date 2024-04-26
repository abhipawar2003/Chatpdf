About</br>
Our project leverages the powerful LangChain framework to develop a system tailored for efficient information retrieval within textual data. At the heart of our solution lies a vector database designed to make both storage and querying processes easier.
In our system, we make words into a special code called vectors, which helps us store and find information really fast. This method, made possible by using text embeddings, makes it easy for our system to handle lots of text quickly and accurately.
One of the features of our system is its question-answering functionality. Users can ask questions, and our system, powered by language processing algorithms, identifies and retrieves the most relevant answers from stored PDFs. This capability not only simplifies the search process but also significantly boosts productivity, enabling users to access vital information swiftly and accurately.
In essence, our project represents a shift in text-based information retrieval. We empower users to navigate through complex textual data effortlessly. Whether it's querying for specific information or extracting answers from textbooks, our solution sets a new standard for efficiency and effectiveness in information retrieval.
</br>

Working </br>
Import Libraries: The code begins by importing necessary libraries for text processing, including those for handling PDF files, text splitting, TF-IDF vectorization, and similarity calculations.
Load PDF and Split Text: The PDF file containing a short story is loaded, and its text content is split into chunks using a character-based text splitter to maintain token size.
Vectorization: The text chunks are converted into TF-IDF vectors, representing the importance of each word in the chunks. These vectors are then stored in a file for future use.
Question Similarity: A sample question related to the story is provided, and its TF-IDF vector is calculated. Cosine similarity is computed between this question vector and the TF-IDF vectors of text chunks to find the most similar chunk, providing an answer to the question.
Top Similar Chunks: Additionally, the code identifies the top four chunks with the highest similarity scores to the question, displaying their scores and content.


</br>
The langchain pdf contains  api keys. theis is also one  method to find the answer but i suggest not to use api keys because they costs too much and every time you need to generate a new api keys .
