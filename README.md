# Chatbot App

The Chatbot App is a simple web application that uses OpenAI's GPT-3 model to provide chatbot functionality. It allows users to have interactive conversations with the chatbot by entering prompts and receiving responses.

## Prerequisites

Before running the application, make sure you have the following prerequisites installed:

- Node.js

## Getting Started

To get started with the Chatbot App, follow these steps:

### Backend

1. Clone the repository:

   ```bash
   git clone https://github.com/Arunangshu-Das/Ai-bot.git
   ```

2. Navigate to the backend directory:

   ```bash
   cd chatbot-app/backend
   ```

3. Install the dependencies:

   ```bash
   npm install
   ```

4. Create a `.env` file in the `backend` directory and add the following environment variables:

   ```
   OPENAI_API_KEY=<your-openai-api-key>
   ```

5. Start the backend server:

   ```bash
   npm start
   ```

   The server will start running on `http://localhost:8000`.

### Frontend

1. In a new terminal, navigate to the frontend directory:

   ```bash
   cd chatbot-app/frontend
   ```

2. Install the dependencies:

   ```bash
   npm install
   ```

3. Start the frontend development server:

   ```bash
   npm start
   ```

   The React development server will start running on `http://localhost:3000`, and the application will open in your default browser.

4. You can now use the Chatbot App to have interactive conversations with the chatbot.

## Usage

- Enter a prompt in the input field and press Enter or click the Submit button.
- The prompt will be sent to the backend server, which will make a request to the OpenAI API to get the chatbot's response.
- The chatbot's response will be displayed in the chat area.
- You can continue the conversation by entering additional prompts.

## Project Structure

The project is structured as follows:

- `backend`: Contains the Node.js backend code.
  - `routes`: Contains the route handlers for the API endpoints.
- `frontend`: Contains the React frontend code.
  - `assets`: Contains static assets such as images.

## Demo
```bash
   https://arunangshu-bot.arunangshu.in/
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
