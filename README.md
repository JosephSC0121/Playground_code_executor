# Code Execution API

## ⚡ A Lightweight Code Execution API for JS, Go, and Python

This API, built with **Go**, serves as the backend for the Playground project, enabling secure execution of JavaScript, Go, and Python code snippets in isolated environments.

---

## 🔧 Features
- **Multi-language Support**: Execute JavaScript, Go, and Python.
- **Secure Execution**: Runs in isolated sandboxes.
- **Fast and Lightweight**: Optimized for performance with Go.
- **REST API Interface**: Simple and easy-to-use HTTP endpoints.

---

## 📜 API Endpoints

### ▶️ Run Code
**POST** `/execute`

#### Request Body (JSON)
```json
{
  "language": "python",
  "code": "print('Hello, World!')"
}
```

#### Response (JSON)
```json
{
  "output": "Hello, World!",
  "error": null
}
```

---

## 🚀 Tech Stack
- **Go**: High-performance backend.
- **Docker**: Secure execution environments.
- **Gin**: Fast and minimalist web framework.

---

## 🏗️ Setup & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourrepo/code-execution-api.git
   cd code-execution-api
   ```
2. Build and run the service:
   ```bash
   go build -o executor .
   ./executor
   ```
3. Use the API with any HTTP client (Postman, Curl, etc.).

---

## 🔗 Related Projects
- [Playground]([#](https://github.com/JosephSC0121/Playgroud-app)) - Interactive learning platform using this API.

This API powers real-time code execution in the Playground project, enabling users to run code snippets effortlessly!

