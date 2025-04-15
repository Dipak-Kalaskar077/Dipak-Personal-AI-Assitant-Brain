# Dipak's Personal AI Assistant - BrainAI

BrainAI is an advanced personal AI assistant created by **Dipak Kalaskar** that can interact with users via both text and voice responses. Built with cutting-edge technologies, it uses the Gemini API to provide contextual and personalized answers, making conversations feel more natural and interactive.

This repository contains the full source code to run your own BrainAI on your local machine.


## Features
- Text & Voice Responses: Get responses in both text and speech.
- Personalized Interactions: Learns and adjusts based on your preferences.
- Speech Recognition: Brain can listen to voice commands and respond appropriately.
- Multimodal Interface: Supports both text and voice-based interactions for a seamless experience.


## Getting Started

### Prerequisites
Before you start, make sure you have the following installed:
- Node.js (v16 or higher) – Download Node.js (https://nodejs.org/)
- NPM (Node Package Manager) – Usually comes with Node.js.
- Gemini API Key – You will need a valid Gemini API key for integrating AI-based responses.

### 1. Clone the Repository
First, clone the repository to your local machine: 
      git clone https://github.com/Dipak-Kalaskar077/Dipak-Personal-AI-Assitant-Brain.git
      cd Dipak-Personal-AI-Assitant-Brain


### 2. Install Dependencies
Once inside the project folder, install the necessary dependencies using npm:

    npm install


### 3. Set Up the Gemini API Key
To use the Gemini API for AI responses, you'll need to obtain an API key. If you don't already have one, sign up here (https://geminiapi.com) and get your API key.

Once you have the API key, create a `.env` file in the root of the project and add your API key as follows:

    GEMINI_API_KEY=your_api_key_here


### 4. Run the Development Server
Now that everything is set up, you can run the project locally. Start the development server using the following command:


    npm run dev


## Available Scripts
- `npm run dev`: Start the development server on localhost.
- `npm run build`: Build the production version of the app.
- `npm run start`: Start the app in production mode.


## Troubleshooting
- **API Key Issues:** Ensure your Gemini API key is correctly set in the `.env` file.
- **Dependencies Not Installing:** Make sure you have a stable internet connection and that you're using a compatible version of Node.js.
- **Server Not Starting:** Check the console for any error messages and ensure all dependencies are installed by running `npm install` again.



## License
This project is licensed under the MIT License - see the LICENSE file for details.



## Contact
For any questions or feedback, feel free to reach out to me at:
- **Email:** er.ddkalaskar@gmail.com
- **LinkedIn:** Dipak Kalaskar (https://linkedin.com/in/dipak-kalaskar)
- **Medium:** @kalaskardipak77 (https://medium.com/@kalaskardipak77)



**Created by:** Dipak Digambar Kalaskar  




The server will start running on **http://localhost:5000**. You can now interact with BrainAI by navigating to this URL in your browser or using voice commands if integrated.


