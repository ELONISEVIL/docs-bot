
```markdown
## Improved Search Engine

#### Description:
The following code snippet is a simple example of a search engine implemented in Python. It can be used as a starting point to build a more advanced and efficient search engine for various applications.

```python
# Import the necessary library
import re

# Create a list of documents to be searched
documents = [
 "This is the first document. It talks about technology.",
 "The second document discusses artificial intelligence and machine learning.",
 "Document three focuses on data science and analytics."
]

# Function to perform the search
def search_documents(query, documents):
    results = []
    for i, doc in enumerate(documents):
        if re.search(query, doc, re.IGNORECASE):
            results.append(i)
    return results

# Example usage
query = input("Enter your search query: ")
print("Search Results:", search_documents(query, documents))
```
