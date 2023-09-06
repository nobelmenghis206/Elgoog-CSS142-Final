
# Elgoog Search Engine (CSS 142 Final Project)

**Project Overview:**
Elgoog Search Engine is a project for my CSS 142 class at UW designed to manage and search through collections of documents that consist of lists of English words. It handles search queries composed of English word phrases, returning a sorted list of document IDs containing exact matches of the search phrase, including both words and order.


**Project Components:**

**The Website:**
The project includes a website component built with Spring Boot, utilizing an in-memory database for document storage and indexing. It serves as a user interface to interact with the search engine.

- Main Search Page: Accessible at [http://localhost:8081](http://localhost:8081), providing search functionality.
- Document Listing: View all documents at [http://localhost:8081/docs](http://localhost:8081/docs).
- Reindex Service: Replace documents with a new set using [http://localhost:8081/reindex](http://localhost:8081/reindex).

**Tasks:**
The primary tasks for this project involve building two key components:

1. **Indexer:** Process documents to create an efficient data structure named "index," optimizing search performance on the same data set.
2. **Searcher:** Implement the search functionality, allowing users to search for phrases using the index.

Indexing is a one-time operation, typically performed during the initial loading of documents (at startup or through the /reindex service). Searching is conducted against the same index for the same set of documents.

Upon completion, the project passed all tests but also demonstrate superior search performance compared to a naive search algorithm.

Explore this project to gain insights into document management and efficient search algorithms. Feel free to test it on your local machine and experience its search capabilities.





## Tech Stack
**Technologies Used:**
- Java
- Spring Boot 
- HTML, CSS, and JavaScript (for the website user interface)
- In-memory database (for document storage and indexing)

