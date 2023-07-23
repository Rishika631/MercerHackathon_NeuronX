# MercerHackathon_NeuronX
This project is an AI-driven web app that simplifies virtual meeting content consumption and analysis.
By leveraging NLP and AI technologies, users can generate accurate transcripts from virtual meetings. The
platform offers features like meeting summarization, sentiment analysis, action insights, areas of
improvement for each participant in the meeting, fostering personal growth opportunities, and interactive
chatbot interactions. Integrated with Google Calendar, it enables efficient scheduling and task
management. Our project empowers individuals and professionals to optimize time, make informed
decisions, and enhance productivity through efficient virtual meeting content utilization, making it a
valuable tool in today's fast-paced digital landscape.

## Instructions to run this project

## Getting Started 
To run the project locally, follow these steps:

## Prerequisites
- Python: Ensure that you have Python installed on your computer. You can download the latest version of Python from the official Python website (https://www.python.org/).
- OpenAI API Key: You need an API key from OpenAI to use their services for transcript summarization and other NLP tasks. Sign up for an account on the OpenAI website (https://openai.com/) and get your API key.
- Google API Credentials: This project uses Google Calendar API for integration. You will need to create a project on the Google Cloud Platform (https://console.cloud.google.com/) and enable the Google Calendar API. Then, create credentials (OAuth 2.0 Client ID) to access the API.

## Installation
1. Clone the repository:

Open your terminal or command prompt and navigate to the directory where you want to clone the project. 
Then, run the following command to clone the repository:

  ```ruby
git clone https://github.com/Rishika631/MercerHackathon_NeuronX.git
```

```ruby
cd MercerHackathon_NeuronX
```

2. Install the required dependencies:
 
Install the required Python packages by running the following command in your terminal or command prompt:

pip install -r requirements.txt

3. Set up the secret key:
In the project directory, find the app.py file and open it with a code editor. Replace the placeholder API keys with your actual API keys:
openai.api_key = 'YOUR_OPENAI_API_KEY'

4. Set up the Google Calendar credentials:

Place the credentials.json file (which contains your Google Calendar API credentials) in the project root directory and also add the access token and refresh token in token.json

5. Run the project
Once you have all the prerequisites ready, you can run the project locally by executing the app.py file using the command:

streamlit run app.py

## Demo Link
https://teamneuronx.streamlit.app/

