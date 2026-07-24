# 📒 Personal Notes Web Application using AWS

## 📌 Project Overview

The **Personal Notes Web Application** is a cloud-based, serverless web application developed using AWS services. It enables users to securely create, view, update, and delete personal notes through an intuitive web interface. The project demonstrates the implementation of a scalable serverless architecture using AWS cloud services.

---

## 🚀 Features

* User authentication using Amazon Cognito
* Secure login and registration
* Create new notes
* View all saved notes
* Update existing notes
* Delete notes
* Responsive and user-friendly interface
* Serverless backend architecture
* Cloud-based data storage

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* AWS Lambda

### AWS Services

* Amazon S3
* Amazon Cognito
* Amazon API Gateway
* Amazon DynamoDB
* AWS IAM

---

## 🏗️ Architecture

```text
User
   │
   ▼
Amazon S3 (Frontend)
   │
   ▼
Amazon Cognito
(Authentication)
   │
   ▼
Amazon API Gateway
   │
   ▼
AWS Lambda
(Business Logic)
   │
   ▼
Amazon DynamoDB
(Data Storage)
```

---

## ⚙️ Workflow

1. The user opens the web application hosted on Amazon S3.
2. Users register or log in through Amazon Cognito.
3. After successful authentication, the frontend sends API requests.
4. Amazon API Gateway receives the requests.
5. API Gateway invokes the AWS Lambda function.
6. Lambda processes CRUD operations.
7. Amazon DynamoDB stores and retrieves note data.
8. The response is returned to the frontend and displayed to the user.

---

## 📂 Project Structure

```text
personal-notes-app/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── backend/
│   ├── lambda_function.py
│   └── requirements.txt
│
└── README.md
```

---

## 🔑 AWS Services Used

### Amazon S3

Hosts the frontend as a static website.

### Amazon Cognito

Provides secure user authentication and authorization.

### Amazon API Gateway

Creates REST APIs that connect the frontend with the backend.

### AWS Lambda

Executes backend business logic without managing servers.

### Amazon DynamoDB

Stores user notes in a highly scalable NoSQL database.

### AWS IAM

Manages permissions between AWS services securely.

---

## 📋 CRUD Operations

* **Create** – Add a new note.
* **Read** – View all notes.
* **Update** – Edit existing notes.
* **Delete** – Remove notes.

---

## ▶️ How to Run the Project

1. Create a DynamoDB table named **Notes**.
2. Create an IAM role with Lambda and DynamoDB permissions.
3. Deploy the Python backend to AWS Lambda.
4. Create REST endpoints using Amazon API Gateway.
5. Configure Amazon Cognito for user authentication.
6. Upload the frontend files to an Amazon S3 bucket.
7. Replace the API Gateway endpoint in `script.js`.
8. Open the S3 website endpoint and start using the application.

---

## 📈 Future Enhancements

* Search notes
* Categories and tags
* Dark mode
* File attachments
* Note sharing
* CloudFront integration
* Custom domain
* Improved security using JWT authorization
* Timestamps and note history

---

## 🎯 Learning Outcomes

Through this project, I gained hands-on experience with:

* Serverless application development
* AWS cloud services integration
* RESTful API development
* User authentication using Amazon Cognito
* NoSQL database design with DynamoDB
* Secure IAM role configuration
* Static website hosting on Amazon S3
* End-to-end cloud application deployment

---

## 👩‍💻 Author

**Kovvuri Jyothsna Harini**

B.Tech – Computer Science (Artificial Intelligence & Machine Learning)

Aditya College of Engineering and Technology

---

⭐ If you found this project useful, feel free to star the repository and share your feedback!
