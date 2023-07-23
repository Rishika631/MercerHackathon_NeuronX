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
