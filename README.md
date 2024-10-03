API Testing Project for ** API- Postman Library **

The scope of this project is to use all API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: API- Postman Library

Tools used: Postman

Collection link: Marius C- Postman Library API v2

Tests performed

HTTP methods supported by this API are GET, POST, PUT, PATCH, and DELETE. In this section, you can explore and perform tests on various types of operations supported by Postman Library API. Some examples include:
GET Requests: Retrieve information about books, by genres, by ID, etc. POST Requests: Add new books, etc. PUT and PATCH Requests: Update existing books, checking books, etc. DELETE Requests: Remove books, etc.
1.	**GET BOOKS**
HTTP method for request: GET
Request description: GET FICTION BOOKS
Test types / techniques used: Functional testing, performance testing, positive testing
Response status code: Result 200 OK

Below you can find a picture of the API request from Postman:
![image](https://github.com/user-attachments/assets/1760a34a-d931-4f2a-9748-670b27fc1fdb)

JavaScript Tests:
![image](https://github.com/user-attachments/assets/bd59a1d3-0a03-471b-b468-4d56bcf9d743)
![image](https://github.com/user-attachments/assets/f969aaea-5e71-48c8-98fa-b0b5298004c7)
![image](https://github.com/user-attachments/assets/a0033100-6988-4c52-ad1c-1703086b815d)
![image](https://github.com/user-attachments/assets/af1ae6a8-6331-401f-acfc-f92379961a83)
![image](https://github.com/user-attachments/assets/a9a6a19b-60d1-420b-90c1-047939fbf14f)

2.	**ADD BOOK**
HTTP method for request: POST
Request description: Add book To kill a mocking bird
Test types / techniques used: Functional testing, performance testing, positive testing
Response status code: Result 201 Created
Below you can find a picture of the API request from Postman:
![image](https://github.com/user-attachments/assets/42012fcd-6b84-4f3f-9d16-9b87da1d91ef)
JavaScript Tests:
![image](https://github.com/user-attachments/assets/1fbec163-8438-4eb5-a854-c316a73891cb)
![image](https://github.com/user-attachments/assets/c77cc7f5-957f-45d8-bac3-3b75186c8d0d)
![image](https://github.com/user-attachments/assets/05dd9fca-b870-4fd3-89fe-cce2a3d5248d)
![image](https://github.com/user-attachments/assets/788e6fd1-e353-45b6-baec-7984bf5637aa)
![image](https://github.com/user-attachments/assets/b7f6dd96-a4aa-45ac-bfdf-0bde1bd16eee)

3.	**CHECK OUT A BOOK**
HTTP method for request: PATCH
Request description: CHECK OUT A BOOK
Test types / techniques used: Functional testing, performance testing, positive testing
Response status code: Result 200 OK
Below you can find a picture of the API request from Postman:
![image](https://github.com/user-attachments/assets/275f2d0a-bda0-40cd-8725-3d7e1d3da0d8)
JavaScript Tests:
![image](https://github.com/user-attachments/assets/6a7ed42b-534a-46df-b6c3-9b17fbb23219)
![image](https://github.com/user-attachments/assets/6424ce1f-558d-4e2a-a971-eb5fce7eb5b4)
![image](https://github.com/user-attachments/assets/a0b44567-9a3c-434e-9f1b-6f54274d538b)
![image](https://github.com/user-attachments/assets/0600f40c-581c-4d7b-a2f3-d64849d6fb8b)
![check out a book test result](https://github.com/user-attachments/assets/09903329-54db-4b7e-ac4b-a3cb60887f68)


4.	**DELETE A BOOK**
HTTP method for request: DELETE
Request description: Delete a non-existing book from the library
Test types / techniques used: Functional testing, performance testing, negative testing
Response status code: Result 404 Not Found
Below you can find a picture of the API request from Postman:
![image](https://github.com/user-attachments/assets/6646f567-7d09-489a-8fec-c81e811463c0)
JavaScript Tests:
![image](https://github.com/user-attachments/assets/e85fcbe1-09a0-4c09-b470-ff350c5076ba)
![check out a book test result](https://github.com/user-attachments/assets/dd9f7fe7-2b98-4347-a835-ca316601fd56)


Functional Execution report for the created API collection
Below you can find the execution report that was generated through the Postman collection runner.
![image](https://github.com/user-attachments/assets/1f3f371d-aec4-4e84-8c2c-bcace9f8e715)
![image](https://github.com/user-attachments/assets/a1eb4719-02d0-496f-a40a-0d88104c6cd5)
![image](https://github.com/user-attachments/assets/cbf03c58-920d-45e5-a0ae-03310a72cee6)
![check out a book test result](https://github.com/user-attachments/assets/b69ef78d-f2f3-4db3-a727-4ccf3f00a842)


Defects found
No issues were identified while running the postman tests.

Conclusions

**Test Coverage: A comprehensive set of 15 API tests was created, covering diverse functionalities in the Postman Library API. Tests included various HTTP methods (GET, POST, PATCH, DELETE) for thorough coverage.

Test Execution: Successful execution of the entire collection using Postman's runner. Detailed execution reports were generated, providing insights into each test case's performance and status.

Functionalities Covered: Extensive testing of library books, item management, books adding and retrieval, and checking out books. A variety of scenarios, including positive, negative, and performance testing, were explored.

Issues Identified: No defects were discovered. Addressing eventual issues is crucial before considering a production release to ensure a stable and reliable API.

Lessons Learned: Documentation Impact: Clear documentation on creating access tokens was valuable for establishing a robust testing environment. Collaboration Significance: Continuous collaboration with the development team is vital to align testing efforts with ongoing API changes, ensuring the testing process remains effective and relevant.**

