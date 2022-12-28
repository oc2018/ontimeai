# Ontime AI server

Ontime AI is a project that uses OpenAI's API to create a completion for a given prompt. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

### Prerequisites

You will need to have Node.js installed on your machine. 
You will also need an OpenAI API key, which can be obtained [here](https://openai.com/). 


### Installing 
Clone the repository to your local machine: 
```bash 
git clone https://github.com/username/ontime-ai.git 
``` 

 Install the dependencies:  
 ```bash 
 npm install 
 ```

 Create a .env file in the root directory and add your OpenAI API key:  

 ```bash 
 OPENAI_API_KEY=YOUR_API_KEY_HERE  

 ```

 Start the server:  

 ```bash  
 npm start  

 ```

 The server should now be running on http://localhost:5000/. You can test it by sending a POST request with a prompt as the body to http://localhost:5000/. The response should be the completion created by OpenAI's API.  

 ## Built With  

 * [Express](https://expressjs.com/) - Web framework used  

 * [OpenAI](https://openai.com/) - Used to generate completions
 
 
 
# ontime Ai Client

This is a simple chatbot application that allows users to interact with a bot. It uses an API to fetch responses from the server and display them in the chat window.

## Features
- User can type in their message and submit it to the bot. 
- Bot will respond with an appropriate response. 
- Responses are fetched from an API. 
- A loading animation is displayed while the response is being fetched from the server. 
- Responses are displayed using a typewriter effect. 

## Technologies Used 
- HTML5 
- CSS3 
- JavaScript (ES6) 
- SVG images for profile pictures  

 ## Installation Instructions 

 1. Clone this repository: `git clone https://github.com/username/chatbot`  
 2. Install dependencies: `npm install`  
 3. Start the development server: `npm start`  

 ## Usage Instructions

 1. Open `index.html` in your browser of choice  
 2. Type your message into the input field and press enter or click submit  

 ## Contributing

 Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.
