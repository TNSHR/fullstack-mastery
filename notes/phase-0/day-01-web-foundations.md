# Phase 0 — Day 1: Web Foundations

## 1. Learning Objectives

By the end of this lesson, I should be able to:

- Explain what web development means.
- Differentiate frontend, backend, and database.
- Explain client and server.
- Describe how a browser opens a website.
- Understand domain names, DNS, IP addresses, HTTP, and HTTPS.
- Explain the basic request-response cycle.

## 2. What Is Web Development?

Web development is the process of creating websites and web applications.

Examples:
- E-commerce websites
- Learning management systems
- Banking dashboards
- Social media platforms
- Online booking applications

A web application usually contains three main parts.

## 3. Frontend

The frontend is the part of an application that users see and interact with.

Examples:
- Buttons
- Forms
- Navigation menus
- Images
- Product listings
- Dashboards

Technologies we will learn:
- HTML: defines the page structure.
- CSS: controls appearance and layout.
- JavaScript: adds behavior and interactivity.
- React: helps build user interfaces using components.

## 4. Backend

The backend handles application logic and processes requests.

Examples:
- Registering a user
- Checking login credentials
- Processing an order
- Checking user permissions
- Retrieving course information

Technologies we will learn:
- Node.js
- Express.js
- JavaScript and TypeScript
- REST APIs

## 5. Database

A database stores and retrieves application data.

Examples:
- User accounts
- Courses and lessons
- Products and orders
- Student enrollments
- Ratings and reviews

Databases in this course:
- MongoDB: a document-oriented database.
- PostgreSQL: a relational database.

## 6. Client and Server

**Client:** The application that makes a request, such as a web browser.

**Server:** A computer or program that receives requests and provides responses.

The browser and server communicate over a network.

## 7. How Does a Website Work?

Example: A student opens an online learning platform.

1. The student enters the website address in the browser.
2. DNS helps the browser find the server's IP address.
3. The browser establishes a connection to the server.
4. The browser sends an HTTP request, normally over HTTPS for a secure website.
5. The server processes the request.
6. If necessary, the backend communicates with the database.
7. The server returns a response.
8. The browser renders the page or updates the user interface.

The database is normally accessed through the backend rather than directly by the browser. This helps protect credentials, enforce permissions, and apply business rules.

## 8. Important Web Terms

| Term | Meaning |
|---|---|
| Browser | Software used to access websites |
| Client | Software making a request |
| Server | Software or computer handling requests |
| Domain | Human-readable name of a website |
| DNS | Helps resolve a domain name to an IP address |
| IP address | Network address used to locate a destination |
| Port | Identifies a network service |
| HTTP | Protocol for web requests and responses |
| HTTPS | HTTP protected using TLS encryption |
| URL | Address identifying a resource |
| API | An interface through which software communicates |
| JSON | A common text format for exchanging data |

## 9. What Is a URL?

Example:

`https://example.com/courses?id=10`

- `https` — protocol
- `example.com` — domain
- `/courses` — path
- `?id=10` — query string

The query string supplies additional parameters. The backend may use those parameters to select which course information to return.

## 10. What Are HTTP Requests and Responses?

A request is sent by a client to ask for a resource or perform an operation.

A response is returned by the server with a status and possibly data.

Common HTTP methods:

- GET: retrieve information.
- POST: submit data or create a resource.
- PUT: replace a resource.
- PATCH: partially update a resource.
- DELETE: delete a resource.

Common status codes:

- 200: request succeeded.
- 201: resource created.
- 400: invalid request.
- 401: authentication is required or invalid.
- 403: access is forbidden.
- 404: resource not found.
- 500: server encountered an unexpected error.

## 11. Why Does the Backend Access the Database?

Suppose a student logs in.

The backend must validate the request, verify the password securely, check the account, and enforce permissions.

If a browser had unrestricted direct access to the application's database, sensitive information could be exposed or modified.

The backend provides a controlled boundary between users and stored data.

## 12. How This Connects to MERN + PostgreSQL

Our application architecture will eventually look like this:

Browser → React frontend → Express API running on Node.js → MongoDB or PostgreSQL

The backend can use Mongoose for MongoDB or a PostgreSQL driver/Prisma for relational database access.

We will learn each part separately before connecting them.

## 13. Key Takeaways

- Frontend is the user-facing part of the application.
- Backend handles application logic and requests.
- Databases store and retrieve data.
- DNS helps a browser locate a server.
- HTTP defines the communication protocol.
- HTTPS protects communication using TLS.
- APIs allow software components to communicate.
- The backend controls access to application data.

## 14. Interview Questions

1. What is web development?
2. What is the difference between frontend and backend?
3. What is a database?
4. What is the difference between a client and a server?
5. What is DNS?
6. What is the difference between a domain and an IP address?
7. What is HTTP, and why is HTTPS important?
8. What happens when a user opens a website?
9. Why should a browser not have unrestricted access to a database?
10. What is an API?

## 15. Self-Assessment

- [ ] I can explain frontend, backend, and database.
- [ ] I can describe the browser request-response cycle.
- [ ] I can explain DNS, domain names, and IP addresses.
- [ ] I understand the purpose of HTTP and HTTPS.
- [ ] I completed the terminal practice.
- [ ] I answered the interview questions in my own words.

**Status:** In progress