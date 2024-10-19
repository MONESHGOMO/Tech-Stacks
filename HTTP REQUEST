# HTTP Methods

HTTP methods are used to indicate the desired action to be performed on the identified resource. These methods correspond to CRUD (Create, Read, Update, Delete) operations. Here are the common HTTP methods:

## 1. **GET**
   - **Purpose**: Retrieve data from a server at the specified resource.
   - **Usage**: It is a safe method, meaning it only retrieves data and does not modify it.
   - **Example**: 
     ```
     GET /users/123
     ```
     This request retrieves the information about the user with ID 123.

## 2. **POST**
   - **Purpose**: Send data to the server to create a new resource.
   - **Usage**: Commonly used when submitting form data or uploading a file.
   - **Example**:
     ```
     POST /users
     {
       "name": "John",
       "email": "john@example.com"
     }
     ```
     This request creates a new user with the name "John."

## 3. **PUT**
   - **Purpose**: Update an existing resource or create it if it does not exist.
   - **Usage**: Replaces all current representations of the target resource with the request payload.
   - **Example**:
     ```
     PUT /users/123
     {
       "name": "John Updated",
       "email": "john.updated@example.com"
     }
     ```
     This request updates the user with ID 123.

## 4. **PATCH**
   - **Purpose**: Apply partial modifications to a resource.
   - **Usage**: Only the fields that need to be updated are included in the request.
   - **Example**:
     ```
     PATCH /users/123
     {
       "email": "new.email@example.com"
     }
     ```
     This request updates only the email of the user with ID 123.

## 5. **DELETE**
   - **Purpose**: Remove a resource from the server.
   - **Usage**: Used to delete data from the server.
   - **Example**:
     ```
     DELETE /users/123
     ```
     This request deletes the user with ID 123.

## 6. **HEAD**
   - **Purpose**: Retrieve the headers of a resource without the response body.
   - **Usage**: Useful for checking what a GET request will return before actually retrieving the resource.
   - **Example**:
     ```
     HEAD /users/123
     ```
     This request retrieves the headers of the user with ID 123.

## 7. **OPTIONS**
   - **Purpose**: Describe the communication options for the target resource.
   - **Usage**: Used to determine the allowed methods on a resource.
   - **Example**:
     ```
     OPTIONS /users/123
     ```
     This request checks which HTTP methods are allowed for the user with ID 123.

## 8. **CONNECT**
   - **Purpose**: Establish a tunnel to the server.
   - **Usage**: Typically used for SSL (HTTPS) connections through a proxy.
   - **Example**:
     ```
     CONNECT www.example.com:443
     ```
     This request establishes a tunnel to the server over HTTPS.

## 9. **TRACE**
   - **Purpose**: Perform a message loop-back test along the path to the target resource.
   - **Usage**: Used to see how a request is altered on its way to the server.
   - **Example**:
     ```
     TRACE /users/123
     ```
     This request traces the path to the user with ID 123.

---

These HTTP methods form the basis for communication between clients and servers over the web.
