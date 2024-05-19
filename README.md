# Travel AI Web Application

This project is a simple Node.js application that interacts with an AI language model to provide travel-related information. The application uses the OpenAI API to send prompts and receive responses, which will eventually help users get recommendations for travel destinations.

## Project Status

🚧 **Work in Progress** 🚧

## Features

- [x] Set up Node.js project and environment.
- [x] Integrate with OpenAI API to send prompts and receive responses.
- [ ] Add frontend to collect user inputs and display results.
- [ ] Enhance AI interactions with more specific models and fine-tuning.
- [ ] Integrate image search API to fetch relevant pictures for travel recommendations.

## Getting Started

### Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)
- OpenAI API key

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/travel-ai-webapp.git
   cd travel-ai-webapp
   ```

2. Install dependencies:

    ```bash
    npm install
    ```
    
3. Set up environment variables:

Create a .env file in the root directory and add your OpenAI API key:

  ```env
    OPENAI_API_KEY=your_openai_api_key_here
  ```

### Running the Application

Start the server:

  ```bash
    node index.js
  ```

  The server will run on http://localhost:3000.

Usage

  GET /: Simple endpoint to check if the server is running.
  POST /ask-ai: Endpoint to interact with the AI. Send a JSON body with a prompt field to receive a response from the AI.

Example POST request using curl:

```bash

curl -X POST http://localhost:3000/ask-ai -H "Content-Type: application/json" -d '{"prompt": "Tell me about beautiful places to visit in Bali."}'
```

Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

    Fork the repository.
    Create a new branch: git checkout -b feature-branch-name.
    Make your changes and commit them: git commit -m 'Add some feature'.
    Push to the branch: git push origin feature-branch-name.
    Open a pull request.

License

This project is licensed under the MIT License.
Contact

If you have any questions or suggestions, feel free to contact me at gabrielmasampaio@gmail.com.
