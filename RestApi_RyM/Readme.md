
# 🌌 RestApi

[![Node.js](https://img.shields.io/badge/Node.js-v18.x-green)](https://nodejs.org/)

A RESTful API built with **Node.js** and **Express**, designed to provide efficient and scalable backend services for various applications.

## 🌟 Features

- Full implementation of a RESTful API.
- Scalable architecture to handle multiple endpoints.
- Support for JSON as the data format.
- Easy to extend and customize.

## 📋 Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (version 18 or higher)
- [npm](https://www.npmjs.com/) (included with Node.js)

## 🚀 Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Jonablo/RestApi.git
   cd RestApi
   ```

2. Install the project dependencies:

   ```bash
   npm install
   ```

3. Start the API server:

   ```bash
   npm start
   ```

4. Open the API in your browser or API client at:

   ```
   http://localhost:3000
   ```

## 🛠️ Technologies Used

- **Node.js**: Backend platform for building scalable applications.
- **Express**: Web framework for Node.js to build APIs.
---


## 🛠️ Configuration Files

### .dockerignore
Lists files and directories to exclude when building a Docker image.

### .gitignore
Lists files and directories to exclude from version control.

### Dockerfile
Defines instructions for creating a Docker image of the application.

---

## 📦 Dependencies

### Production Dependencies

- **express**: Fast, unopinionated, minimalist web framework for Node.js.
- **ejs**: Embedded JavaScript templates.
- **morgan**: HTTP request logger middleware for Node.js.

### Development Dependencies

- **nodemon**: Monitors for changes in your source code and automatically restarts your server.

---

## 📄 Scripts

### Start the Application

```bash
npm start
```

### Development Mode

```bash
npm run dev
```

---

## 🛠️ Setup and Installation

1. **Clone the Repository**:

   ```bash
   git clone <repository-url>
   cd RestApi_RyM
   ```

2. **Install Dependencies**:

   ```bash
   npm install
   ```

3. **Run the Application**:

   ```bash
   npm start
   ```

   The application will run on `http://localhost:3000` by default.

---

## 📂 Project Structure

```plaintext
RestApi/
├── src/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── server.js
├── package.json
├── README.md
└── LICENSE
```

## 🐳 Docker Support

Build and run the application using Docker:

1. **Build the Docker Image**:

   ```bash
   docker build -t restapi_rym .
   ```

2. **Run the Docker Container**:

   ```bash
   docker run -p 3000:3000 restapi_rym
   ```

---

## 🤝 Contributions

Contributions are welcome! If you'd like to improve this project, please follow these steps:

1. Fork the repository.
2. Create a branch for your changes (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.

---

## 🌟 Future Improvements

- Add integration with the Rick and Morty API for fetching and displaying characters.
- Include more robust error handling.
- Implement additional endpoints for extended functionality.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and distribute it according to the terms.
