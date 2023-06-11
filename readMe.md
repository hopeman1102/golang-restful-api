#  Build gRPC Server API & Client with Golang and MongoDB

## 1. API with Golang + MongoDB + Redis + Gin Gonic: Project Setup

In this article, you'll learn how to set up a Golang application with MongoDB-Go-driver, Gin Gonic, and Go Redis. Later, we'll access both the Redis and MongoDB databases directly in VS Code using a MySQL VS Code extension.

### Topics Covered

- Setup Golang with MongoDB and Redis
- Creating MongoDB and Redis Database with Docker-compose
- Setup Environment Variables
- How to Connect Golang App to Redis and MongoDB
- Test the Golang API
- How to Connect to MongoDB and Redis Servers in VS Code

## 2. Golang & MongoDB: JWT Authentication and Authorization

In this article, you'll learn how to implement RS256 JWT (JSON Web Token) Authentication and Authorization with Golang, Gin Gonic, MongoDB-Go-driver, and Docker-compose.

### Topics Covered

- Golang & MongoDB JWT Authentication Overview
- JWT Authentication Example with Golang and MongoDB
- How to Generate Public and Private Keys
- Update Environment Variables with Viper
- Creating the User models with structs
- Creating an Auth and User Interfaces
    - Authentication Interface
    - User Interface
- Create utility functions to hash and verify password
- Create services that interact with the database
    - Auth interface implementation
    - User interface implementation
- Create a utility function to sign and verify JWT tokens
    - Create Json Web Token
    - Verify JSON Web Token
- Create the authentication controllers
    - Signup user controller
    - Login user controller
    - Refresh access token controller
    - Logout user controller
- Authentication Middleware Guard
- Create the user controllers
- Create API Routes with Gin
    - Auth Routes
    - User Routes
- Add the Routes to the Gin Middleware Pipeline

## 3. API with Golang + MongoDB: Send HTML Emails with Gomail

In this article, you'll learn how to send HTML emails with Golang, Gomail, MongoDB-Go-Driver, Redis, and Docker-compose. Also, you'll learn how to generate HTML templates with the standard Golang html/template package.

### Topics Covered

- Send Emails with Golang, MongoDB, and Gomail Overview
- Creating the HTML Email Templates with Golang
- Create an SMTP Provider Account
- Load and Validate Environment Variables Viper
- Create a Utility Function to Send the Emails
- Update the SignUp Controller

## 4. API with Golang, Gin Gonic & MongoDB: Forget/Reset Password

In this article, you'll learn how to implement forget/reset password functionality with Golang, Gin Gonic, Gomail, MongoDB-Go-driver, Redis, and Docker-compose. 

### Topics Covered

- Forget/Reset Password with Golang, Gin, and MongoDB
- Create the MongoDB Model Structs
- Create the HTML Email Templates with Golang
- Define a Utility Function to Parse the HTML Templates
- Create a Function to Send the HTML Emails
- Add the Forgot Password Controller
- Add the Reset Password Controller
- Register the Gin API Routes

## 5. Build Golang gRPC Server and Client: SignUp User & Verify Email

In this article, you'll learn how to create a gRPC server to register a user and verify their email address using Golang, MongoDB-Go-driver, Gomail, and Docker-compose. 

### Topics Covered

- gRPC Project setup in Golang
- Create the gRPC Request and Response Messages
    - Define the gRPC User messages
    - Define the gRPC Request and Response Message to SignUp User
- Create the gRPC Service Methods
- Generate the gRPC client and server interfaces
- Start the gRPC Server
- Test the gRPC API Server with Golang Evans
- Create the gRPC API Controllers
    - Register User gRPC Controller
    - Verify User gRPC Controller
- Create the gRPC Client to Register a User

## 6. Build Golang gRPC Server and Client: Access & Refresh Tokens

In this article, you'll learn how to implement JWT access and refresh tokens with gRPC using Golang, MongoDB-Go-driver, Gomail, Docker, and Docker-compose.

### Topics Covered

- Create the gRPC Request and Response Messages
    - Create the gRPC User messages
    - Define the gRPC Request and Response Message to Login User
    - Update the Authentication gRPC Service
    - Create a gRPC User Service
- Create the gRPC Controllers
- Create the gRPC Servers
- Register the gRPC Servers
- Create the gRPC Clients in Golang
- Connect the gRPC Client to the gRPC Server

## 7. Build CRUD RESTful API Server with Golang, Gin, and MongoDB

In this article, you'll learn how to build a CRUD RESTful API server with Golang, Gin Gonic, MongoDB-Go-driver, Docker, and Docker-compose.

### Topics Covered

- Golang, Gin Gonic, MongoDB CRUD RESTful API Overview
- Create the Models with Structs
- Create the Service Interface
- Create Methods to Implement the Interface
    - Initialize the Service Struct
    - Define a Service to Create a Post
    - Define a Service to Update Post
    - Define a Service to Delete Post
    - Define a Service to Get Single Post
    - Define a Service to Get All Posts
- Create Controllers to Perform the CRUD Operations
    - Initialize the Controller Struct
    - Define a Controller to Create a Post
    - Define a Controller to Update a Post
    - Define a Controller to Delete a Post
    - Define a Controller to Get a Single Post
    - Define a Controller to Get All Posts
- Create the Routes for the Controllers
- Initialize the Constructors and Start the Gin Server


## 8. Build CRUD gRPC Server API & Client with Golang and MongoDB

In this article, you'll learn how to build a CRUD gRPC API server with Golang, MongoDB-Go-driver, and Docker-compose. You'll also build a gRPC client to interact with the gRPC API.

### Topics Covered

- Define the Models with Structs
- Create the ProtoBuf Messages
- Define the gRPC Service and RPC Methods
- Define a Custom Service Interface
- Create Methods to Implement the Service Interface
    - Create a Constructor to Implement the Service Interface
    - Create a new Post
    - Update a Post
    - Find a Post
    - Retrieve All Posts
    - Delete a Post
- Define the gRPC Controllers
- Register the gRPC Services and Start the gRPC Server
- Test the gRPC API Server with Evans CLI
- Create the gRPC API Handlers in Golang
    - CreatePost gRPC Handler
    - UpdatePost gRPC Service Handler
    - GetPost gRPC Service Handler 
    - DeletePost gRPC Service Handler
    - GetPosts gRPC Service Handler
- Testing the gRPC Services with Evans Cli
- Create the gRPC Clients
    - gRPC Client to Create a Post
    - gRPC Client to Update a Post
    - gRPC Client to Get a Single Post
    - gRPC Client to Get All Posts
    - gRPC Client to Delete a Post
- Register the gRPC Services
