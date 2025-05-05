# Introduction to Server, Client, and APIs

This document provides a foundational understanding of how servers, clients, and APIs work, especially in the context of Flutter app development. It also introduces REST APIs and HTTP methods, and outlines the tools and technologies commonly used to build and test APIs.

---

## What is a Server?

A **server** is a powerful computer or system designed to provide services, resources, and data to other computers over a network. It stores, manages, and processes data, and is responsible for handling requests from multiple clients simultaneously.

Servers are always online and are typically hosted in secure data centers or cloud platforms (e.g: Google Cloud, AWS, Azure).

---

## What is a Client?

A **client** refers to a user or a device (such as a mobile phone, web browser, or desktop application) that interacts with the server to request and consume data or services.

Clients send requests to the server and wait for the appropriate responses.

---

## Real-World Examples

* **Google** – Your browser (client) fetches search results from Google’s servers.
* **FoodPanda** – You place orders via the app (client), which communicates with their server to process orders.
* **Facebook & WhatsApp** – Messages, images, and notifications are exchanged between your device and remote servers.

---

## What is an API?

**API** stands for **Application Programming Interface**.

An API acts as a bridge between the **client** and the **server**, enabling secure and structured communication. It defines how data should be requested, sent, and received.

APIs are essential for:

* Sharing data between applications
* Connecting frontend interfaces with backend services
* Accessing remote resources securely and efficiently

---

### Request-Response Cycle

1. **Request (Client to Server)**:

   * A web or mobile app (client) sends a request via the internet.
   * The request hits the server's API, which may retrieve or store data in the database.

2. **Response (Server to Client)**:

   * The server processes the request, performs the required action, and sends a structured response back to the client.

Request Structure from Client using API:
```plaintext
Client (Web/Mobile App) 
        ↓
     Internet
        ↓
       API
        ↓
     Server
        ↓
    Database
```

Response Structure from Server using API:
```plaintext
    Database
        ↓
     Server
        ↓
       API
        ↓
     Internet
        ↓
Client (Web/Mobile App)
```

---

## What are REST APIs?

**REST** (Representational State Transfer) is a widely used architecture for designing networked APIs. RESTful APIs use standard HTTP methods to perform operations and are stateless, meaning each request from the client contains all the necessary information.

### Key Features of REST:

* Stateless communication
* Resource-based (represented by URLs)
* Uses standard HTTP methods
* Supports multiple formats (commonly JSON or XML)

---

## HTTP Methods in RESTful APIs

| Method | Purpose                                 |
| ------ | --------------------------------------- |
| GET    | Retrieve data from the server           |
| POST   | Send new data to the server for storage |
| PUT    | Update existing data entirely           |data          |
| DELETE | Remove data from the server             |


---

## API Testing Tools

**Postman** is the most widely used software for testing APIs. It allows developers to send requests, inspect responses, and automate testing workflows.

---

## Technologies for Building APIs

Some popular backend technologies used for building APIs include:

* **Node.js** – JavaScript-based runtime environment
* **Laravel** – PHP framework for web applications
* **Django** – Python-based web framework

> In this course, we will **not** be using Node.js or Laravel. Instead, we will focus on building and understanding APIs using the **Dart language**, specifically tailored for Flutter mobile app development.

---

## Conclusion

Understanding the fundamentals of servers, clients, and APIs is crucial for modern app development. In the upcoming modules, we will explore how to consume and interact with RESTful APIs using Dart in Flutter apps, enabling seamless communication between the client (mobile app) and the server.

---
