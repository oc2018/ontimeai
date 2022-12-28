# Ontime AI

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
