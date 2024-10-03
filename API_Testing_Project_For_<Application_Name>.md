<h1>API Testing Project for ** API- Postman Library **</h1>

The scope of this project is to use all  API knowledge gained throught the Software Testing course and apply them in practice, using a live application.

Application under test: **API- Postman Library**

Tools used: Postman

Collection link: **Marius C- Postman Library API v2**

<h2>Tests performed</h2>
HTTP methods supported by this API are GET, POST, PUT, PATCH, and DELETE. In this section, you can explore and perform tests on various types of operations supported by Postman Library API. Some examples include:

GET Requests: Retrieve information about books, by genres, by ID, etc.
POST Requests: Add new books, etc.
PUT and PATCH Requests: Update existing books, checking books, etc.
DELETE Requests: Remove books, etc.
<ol>
<li>**GET BOOKS**</li>

HTTP method for request: **GET**<br>
Request description: **GET FICTION BOOKS**<br>
Test types / techniques used: **Functional testing, performance testing, positive testing**<br>
Response status code: **Result 200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![check out a book test](https://github.com/user-attachments/assets/01b32ab1-8d65-4bbf-b339-454ca02fe58e)**<br>

JavaScript Tests:

**![get fiction books js 1](https://github.com/user-attachments/assets/e05dd290-7118-4630-b64c-297917ade482)
![get fiction books js 2](https://github.com/user-attachments/assets/9b05e62c-7aa3-43b4-bdd0-db6f294c1b30)
![get fiction books js 3](https://github.com/user-attachments/assets/afd1e6ed-fd6c-46e5-a121-b170e540326d)
![get fiction books js 4](https://github.com/user-attachments/assets/806f65d9-644c-4735-9888-a1daf3dd61f4)
![get fiction books results](https://github.com/user-attachments/assets/9c82bbe9-5b72-4e41-b388-23e6b3dd2528)**<br>

<li>**ADD BOOK**</li>

HTTP method for request: **POST**<br>
Request description: **Add book To kill a mocking bird**<br>
Test types / techniques used: **Functional testing, performance testing, positive testing**<br>
Response status code: **Result 201 Created**<br>

Below you can find a picture of the API request from Postman:<br>

**![add a book test](https://github.com/user-attachments/assets/f32a75be-3fed-4622-8cf4-b3a5b439e20a)**<br>

JavaScript Tests:

**![add a book js1](https://github.com/user-attachments/assets/4ebd6c8a-4183-43f0-be2b-f6e1e062037c)
![add a book js2](https://github.com/user-attachments/assets/c5822bb6-e920-437d-b7d1-882254fd59df)
![add a book js3](https://github.com/user-attachments/assets/9bd9d460-2303-48f9-b823-5826f9da1137)
![add a book js4](https://github.com/user-attachments/assets/774ed048-851b-487a-82a8-9eb02368989b)
![add a book test result](https://github.com/user-attachments/assets/04a7998e-1176-4316-89f5-6920880bf161)**<br>

<li>**CHECK OUT A BOOK**</li>

HTTP method for request: **PATCH**<br>
Request description: **CHECK OUT A BOOK**<br>
Test types / techniques used: **Functional testing, performance testing, positive testing**<br>
Response status code: **Result 200 OK**<br>

Below you can find a picture of the API request from Postman:<br>

**![check out a book test](https://github.com/user-attachments/assets/8dcb0194-47ab-4c33-89b6-7a3e1aeb8d9f)**<br>

JavaScript Tests:

**![check out a book 1](https://github.com/user-attachments/assets/51763c6f-4da6-466d-8db5-3f4ca423f11e)
![check out a book 2](https://github.com/user-attachments/assets/f3e3fab7-f0ea-4471-8aac-04e478f99307)
![check out a book 3](https://github.com/user-attachments/assets/96873a01-fcc6-4a42-b657-6228548f4362)
![check out a book 4](https://github.com/user-attachments/assets/0bb96c57-85c2-4da4-b219-942c831ffe4b)
![check out a book test result](https://github.com/user-attachments/assets/7f000ddd-414c-4427-8e01-7f7ad023f683)
**<br>

<li>**DELETE A BOOK**</li>

HTTP method for request: **DELETE**<br>
Request description: **Delete a non-existing book from the library**<br>
Test types / techniques used: **Functional testing, performance testing, negative testing**<br>
Response status code: **Result 404 Not Found**<br>

Below you can find a picture of the API request from Postman:<br>

**![delete a book](https://github.com/user-attachments/assets/f765cbb9-5038-46ec-b62d-2094919c1897)**<br>

JavaScript Tests:

**![delete a book test js](https://github.com/user-attachments/assets/05893aa4-842c-4155-81dd-b4713e60da0f)
![check out a book test result](https://github.com/user-attachments/assets/5c975313-55a8-41b7-abd1-3a0da11ba58e)
**<br>


</ol>

<h2>Functional Execution report for the created API collection </h2>

Below you can find the execution report that was generated through the Postman collection runner. <br>

**![Collection Runner](https://github.com/user-attachments/assets/16273949-139b-4dea-98d6-9dbc3eb4e351)
![get fiction books results](https://github.com/user-attachments/assets/84db6ad7-4f29-4599-8287-ec5cef7fae89)
![add a book test result](https://github.com/user-attachments/assets/077fa512-eb79-4c03-8854-6d811935d70b)
![check out a book test result](https://github.com/user-attachments/assets/2305b533-8051-408c-a591-c1978d45dfb8)
![check out a book test result](https://github.com/user-attachments/assets/5fdc801a-b1b6-409e-9891-e6832989358c)
**<br>

<h2>Defects found</h2>

No issues were identified while running the postman tests.<br>

<h2>Conclusions</h2>

**Test Coverage: A comprehensive set of 15 API tests was created, covering diverse functionalities in the Postman Library API. Tests included various HTTP methods (GET, POST, PATCH, DELETE) for thorough coverage.

Test Execution: Successful execution of the entire collection using Postman's runner. Detailed execution reports were generated, providing insights into each test case's performance and status.

Functionalities Covered: Extensive testing of library books, item management, books adding and retrieval, and checking out books. A variety of scenarios, including positive, negative, and performance testing, were explored.

Issues Identified: No defects were discovered. Addressing eventual issues is crucial before considering a production release to ensure a stable and reliable API.

Lessons Learned: Documentation Impact: Clear documentation on creating access tokens was valuable for establishing a robust testing environment. Collaboration Significance: Continuous collaboration with the development team is vital to align testing efforts with ongoing API changes, ensuring the testing process remains effective and relevant.**

