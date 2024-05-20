# AI-Chat 

AI-Chat is an AI Chatbot application inspired by ChatGPT, developed using the MERN stack (MongoDB, Express.js, React, Node.js) and OpenAI. This customized chatbot stores each user message in the database, allowing for retrieval and deletion. The application is fully secured with JWT tokens, HTTP-only cookies, signed cookies, password encryption, and middleware chains.

## Features

- Interactive chat interface inspired by ChatGPT
- Stores user messages in the database for retrieval and deletion
- Secure authentication using JWT tokens and HTTP-only cookies
- Password encryption and middleware chains for enhanced security
- Modern design with Material-UI for a seamless user experience
- RESTful API for efficient communication between client and server

## Tech Stack

- JavaScript
- React
- Node.js
- Express.js
- MongoDB
- REST API
- Material-UI (MUI)
- HTML
- CSS
- Git

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ai-chat.git
   ```
2. Navigate to the project directory:
   ```bash
   cd ai-chat
   ```
3. Install the server-side dependencies:
   ```bash
   cd server
   npm install
   ```
4. Install the client-side dependencies:
   ```bash
   cd ../client
   npm install
   ```
5. Set up environment variables:
   - Create a `.env` file in the `server` directory and add the following:
     ```env
     MONGO_URI=your_mongodb_uri
     JWT_SECRET=your_jwt_secret
     OPENAI_API_KEY=your_openai_api_key
     ```
6. Start the server:
   ```bash
   cd server
   npm start
   ```
7. Start the client:
   ```bash
   cd ../client
   npm start
   ```
   
8. Open `http://localhost:3000` in your web browser to use the application.


## Contributing

Contributions are welcome! If you have any suggestions or improvements, please feel free to create an issue or submit a pull request.

## License

This project is open source and available under the MIT License.

---

Experience AI-driven conversations with AI-Chat and enhance your development skills with this comprehensive project!
