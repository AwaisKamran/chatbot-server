# About
This project has several API's for processing data in various formats (text, audio stream etc.). We generate responses using openAI based on the user's query. As for the API's response we send readable audio stream of the response generated by openAI which can played at the Frontend.


# Getting Started

## Setting Up API Keys
We will need a couple of keys for this app's configuration. So you'll need to add the key/value pairs as enviroment variables.

### OPENAI Key
Add your openAI key as OPENAI_API_KEY="Your-Api-Key" (Don't forgot to throw some $ into your account)

### AWS Keys
You will need to configure AWS by adding three keys as enviroment variables. 
    1. AWS_ACCESS_KEY_ID="Your-Key"
    2. AWS_SECRET_ACCESS_KEY="Your-Key"
    3. REGION_NAME="Your-Region"

## Installing Dependencies

### Use "pip install" for installing dependencies

## Running the Application
uvicorn server:app --host=127.0.0.1 --port=${PORT:-PortNumber} --reload (--reload is optional for hot reload)



# Happy Coding!