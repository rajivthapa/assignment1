# Web Development Core Concepts

## HTTP Methods & HTTP Status Codes

### HTTP Methods
HTTP methods are actions that can be performed on resources (like data) on a web server. Common methods include:

- **GET**: Requests data from a server. For example, visiting a web page or fetching a list of users.
  - Example: `GET /users`
- **POST**: Sends data to the server to create a new resource.
  - Example: `POST /users` with JSON data like `{ "name": "John" }`
- **PUT**: Updates an existing resource by replacing it entirely.
  - Example: `PUT /users/1` to update user with ID 1.
- **DELETE**: Deletes a specified resource from the server.
  - Example: `DELETE /users/1`

### HTTP Status Codes
These codes let the client know how the server responded to a request:

- **200 OK**: The request was successful.
- **201 Created**: The request was successful and a new resource was created.
- **400 Bad Request**: The server could not understand the request, often due to invalid syntax.
- **404 Not Found**: The requested resource does not exist on the server.
- **500 Internal Server Error**: The server encountered an unexpected condition that prevented it from fulfilling the request.

---

## CSS Selectors

CSS selectors are used to target HTML elements and apply styles to them.

1. **Element Selector**
   - Targets all elements of a specific type.
   - Example: `p { color: red; }` targets all `<p>` tags.

2. **Class Selector**
   - Targets all elements with a specific class.
   - Syntax: `.classname`
   - Example: `.highlight { background-color: yellow; }`

3. **ID Selector**
   - Targets a single element with a specific ID.
   - Syntax: `#idname`
   - Example: `#header { font-size: 24px; }`

4. **Descendant Selector**
   - Targets elements that are inside a specific parent element.
   - Example: `nav a { color: blue; }` targets all `<a>` tags inside a `<nav>`.

---

## GIT Basics

Git is a version control system that tracks changes in your code.

- **`git init`**: Initializes a new Git repository in the current directory.
- **`git add`**: Stages files for the next commit.
  - Example: `git add .` adds all modified files.
- **`git commit`**: Records the staged changes.
  - Example: `git commit -m "Initial commit"`
- **`git push`**: Sends commits to a remote repository like GitHub.
  - Example: `git push origin main`
- **`git pull`**: Fetches and merges changes from a remote repository.
- **`git clone`**: Makes a local copy of a remote repository.
  - Example: `git clone https://github.com/user/repo.git`
- **`git branch`**: Lists all branches or creates a new one.
  - Example: `git branch new-feature` creates a branch called `new-feature`.

---

## Callback & Higher-Order Function

- **Callback Function**: A function passed into another function as an argument and executed later (e.g., in event handlers or async tasks).
- **Higher-Order Function**: A function that takes another function as an argument or returns a function.

## Array Methods

- `filter()`: Creates a new array with elements that pass a test.
- `map()`: Transforms each element in the array and returns a new array.
- `forEach()`: Executes a function on each element (does not return a new array).
- `push()`: Adds an element to the end of the array.
- `pop()`: Removes the last element from the array.