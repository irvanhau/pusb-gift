### **Front-End Web Developer Test**

#### **Instructions**:
- You are required to complete all the questions.
- You will build a simple application using JSON Server as a mock API to simulate user data,
posts, and products.
- The application will have basic authentication, and you will implement CRUD operations for the
product page.
- Use the tools and libraries you are most comfortable with, but be prepared to explain your
choices.
---

### **Section 1: Setup and Configuration (10 points)**
1. **JSON Server Setup**:
Install `json-server` and set up a local server using the provided example data structure.
- How would you install `json-server` and configure it to run with the following data:
```json
{
"users": [
{ "id": 1, "name": "John Doe", "email": "john@example.com" },
{ "id": 2, "name": "Jane Doe", "email": "jane@example.com" }
],
"posts": [
{ "id": 1, "title": "First Post", "author": "John Doe" },
{ "id": 2, "title": "Second Post", "author": "Jane Doe" }
],
"comments": [
{ "id": 1, "postId": 1, "body": "Great post!" },
{ "id": 2, "postId": 2, "body": "Very informative!" }
]
}
```
- **Question**: Provide the steps to set up the `json-server`, including how to start the server
and access the API endpoints.
  
2. **Package Installation**:
After setting up `json-server`, create a simple front-end project using a framework of your
choice (e.g., Vue.js, React, or Angular). Explain the steps you would take to initialize your
front-end project and install any necessary dependencies.
---

### **Section 2: Authentication (25 points)**
3. **Login Page**:
Create a simple login page where users can log in with their emai or username and
passwordl. You should verify the user credentials using the JSON Server API.

- **Question**: How would you implement authentication logic using JSON Server? Provide
the detailed steps to:
- Fetch user data from `json-server`.
- Validate the emai or usernamel entered on the login page against the user data.
- Store a simple session token or flag indicating the user is logged in (like boolean status)..

4. **Session Management**:
Implement basic session management. After logging in, the user should be redirected to the
dashboard page.

- **Question**: Describe how you would manage the user session, such as storing a token or
using localStorage to persist the session.
---

### **Section 3: Dashboard and Product Pages (30 points)**
5. **Dashboard Page**:
After login, create a dashboard page that displays the user's details (name, email) and a list of
recent posts fetched from the `json-server`.
- **Question**: How would you retrieve and display the user’s posts on the dashboard page?

6. **Product Page**:
Create a product page where users can view a list of products. Use JSON Server as the
backend for managing product data.
- **Question**: How would you fetch and display products on the product page using
`json-server` as the API? Include the steps for integrating the API with your front-end
framework.
---

### **Section 4: CRUD Operations for Products (35 points)**
7. **Create Product**:
Implement the functionality to add a new product using a form. This should send a POST
request to the JSON Server.
- **Question**: How would you create a new product in the JSON Server? Provide the
front-end logic and explain how the POST request will be handled.

8. **Update Product**:
Implement functionality to edit an existing product. This should send a PUT request to the
JSON Server.
- **Question**: How would you implement the update functionality for a product? Describe the
steps to send the PUT request and update the product data.

9. **Delete Product**:
Implement the functionality to delete a product. This should send a DELETE request to the
JSON Server.
- **Question**: How would you handle product deletion from both the front-end and JSON
Server? Include how you would confirm the deletion with the user.
---

### **Section 5: Bonus (Optional - 10 points)**
10. **Search and Filter Functionality**:
Implement search and filter functionality on the product page. Users should be able to filter
products by name or category.

- **Question**: How would you implement search and filter functionality in your product page?
Include details on querying the JSON Server and updating the product list dynamically.
---

### **Submission Requirements**:
- You are required to provide a GitHub repository link containing your project with a README
file explaining the steps to run the project.
- Ensure that your project is well-organized and follows best practices for code structure and
naming conventions.
---

This test is designed to evaluate your ability to:
- Set up and work with mock APIs.
- Implement basic authentication and session management.
- Perform CRUD operations.
- Use modern front-end frameworks effectively. *It's free what you use
