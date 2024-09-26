### **Back-End Web Developer Test**

**Table: article_categories**
| Field    | Data Type |
| -------- | --------  |
| id       | bigint    |
| name     | string    |
| slug     | string    |

**Table: articles**
| Field    | Data Type |
| -------- | --------  |
| category_id | bigint |
| title    | string    |
| content  | text      |
| thumbnail | string   |
| status   | boolean   |
| slug     | string    |

### **To Do List**
1. Create REST API for CRUD Article and Article Category
2. Create REST API for Get list of Article, sort by latest first, with optional query parameters:
    - Keyword: to search keyword in the article posting title
    - Filter by article category

### **What you need to consider**:
1. What if there are thousands of articles in the database?
2. What if many users are accessing your API at same time?
3. What if users perform stored xss and how to prevent it?

### **Requirement**:
1. Write the solution using Golang
2. You can use any tech stack for database, caching, 
3. API Documentation using Postman, Swagger API, etc

### **Submission Requirements**:
- You are required to provide a GitHub repository link containing your project with a README
file explaining the steps to run the project and answer the question.
- Ensure that your project is well-organized and follows best practices for code structure and
naming conventions.
---
