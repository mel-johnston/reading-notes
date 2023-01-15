# Code 301 Reading Notes

[Class 1](https://mel-johnston.github.io/reading-notes/301/class1) -
[Class 2](https://mel-johnston.github.io/reading-notes/301/class2) -
[Class 3](https://mel-johnston.github.io/reading-notes/301/class3) -
[Class 4](https://mel-johnston.github.io/reading-notes/301/class4) -
[Class 5](https://mel-johnston.github.io/reading-notes/301/class5) -
[Class 6](https://mel-johnston.github.io/reading-notes/301/class6) -
[Class 7](https://mel-johnston.github.io/reading-notes/301/class7) -
[Class 8](https://mel-johnston.github.io/reading-notes/301/class8) -
[Class 9](https://mel-johnston.github.io/reading-notes/301/class9) -
[Class 10](https://mel-johnston.github.io/reading-notes/301/class10) -
[Class 11](https://mel-johnston.github.io/reading-notes/301/class11) -
[Class 12](https://mel-johnston.github.io/reading-notes/301/class12) -
[Class 13](https://mel-johnston.github.io/reading-notes/301/class13) -
[Class 14](https://mel-johnston.github.io/reading-notes/301/class14) -
[Class 15](https://mel-johnston.github.io/reading-notes/301/class15)

---

## Class 8 Notes - APIs

### [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

1. What does REST stand for?
    - Representational State Transfer
2. REST APIs are designed around ____.
    - Resources, which are any kind of object, data, or service that can be accessed by the client.
3. What is an identifier of a resource? Give an example.
    - A URI that uniquely identifies that resource. For example, the URI for a particular customer order might be: https://adventure-works.com/orders/1
4. What are the most common HTTP verbs?
    - The most common operations are GET, POST, PUT, PATCH, and DELETE.
5. What should the URIs be based on?
    - URIs should be based on nouns (the resource) and not verbs (the operations on the resource).
6. Give an example of a good URI.
    - https://adventure-works.com/orders // Good
    - https://adventure-works.com/create-order // Bad
7. What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
    - API that expose a large number of small resources. It is a bad thing.
8. What status code does a successful GET request return?
    - A successful GET method typically returns HTTP status code 200 (OK).
9. What status code does an unsuccessful GET request return?
    - If the resource cannot be found, the method should return 404 (Not Found).
10. What status code does a successful POST request return?
    - If a POST method creates a new resource, it returns HTTP status code 201 (Created).
11. What status code does a successful DELETE request return?
    - If the delete operation is successful, the web server should respond with HTTP status code 204 (No Content).

### Bookmark and Review

- [RegExr](https://regexr.com/)
- [Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)
- [Regex 101](https://regex101.com/)