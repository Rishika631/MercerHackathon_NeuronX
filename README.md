# MercerHackathon_NeuronX
Our AI-driven web app simplifies virtual meeting content analysis. Generate accurate transcripts, summarize meetings, analyze sentiments, gain action insights, and interact with a chatbot. Integrated with Google Calendar for efficient scheduling and task management. Optimize time and boost productivity!
## Instructions to run this project

1.Clone the repository:

git clone https://github.com/Rishika631/MercerHackathon_NeuronX.git

cd MercerHackathon_NeuronX

2.Install the required dependencies:

pip install -r requirements.txt

3.Set up the secret key:
Replace <your-api-key> in app.py with your own openAI api key

4.Set up the Google Calendar credentials:

Place the credentials.json file (which contains your Google Calendar API credentials) in the project root directory and also add the access token and refresh token in token.json

5.Run the project

streamlit run app.py
