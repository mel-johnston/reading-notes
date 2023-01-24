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

## Class 12 Notes - Creating and Deleting Resources

### [Status Codes Based On REST Methods](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)

1. Describe what each group of status code represents:
    - 100’s =  informational status codes
    - 200’s = success codes
    - 300’s = redirection codes
    - 400’s = client error codes
    - 500’s = server error codes

2. What is a status code 202? Accepted
3. What is a status code 308?  Permanent Redirect
4. What code would you use if an update didn’t return data to a client? 204 No Content
5. What code would you use if a resource used to exist but no longer does? 204 No Content
6. What is the ‘Forbidden’ status code? 403 Forbidden

### Build A REST API With Node.js, Express, & MongoDB

1. Why do we need to pull our MongoDB database string out of our server and put it into our .env?
    - when you deploy you don't want others to have access to your database
2. What is middleware?
    -  middleware deals with the requests to the server before they reach the routes
3. What does app.use(express.json()) do?
  - this lets the server accept json as a body instead of get or post element
4. What does the /:id mean in a route?
  - for getting one route
5. What is the difference between PUT and PATCH?
  - patch is used for Update, so a user can update specific item/s
6. How do you make a default value in a schema?
  - default: whateverDefaultValueYouWant
7. What does a 500 error status code mean?
  - 500 - Internal Server Error
8. What is the difference between a status 200 and a status 201?
  - 200 - OK, 201 - Created
