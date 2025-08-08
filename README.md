AI Career-Counsellor
Welcome to AI Career-Counsellor, a web-based application that provides personalized career guidance based on your education level, interests, and personal responses. This project leverages OpenAI's language models to simulate a conversation with a career counsellor, offering tailored career advice in real-time.

Features
Interactive chatbot to help students clarify their career doubts.
Personalized career advice based on user input.
Keeps track of conversation history.
Provides suggestions for career options based on personality traits and preferences.
Deployed using Streamlit for easy accessibility.
Demo
You can try the AI Career-Counsellor app here: Streamlit Deployment URL (replace with your Streamlit app URL)

Project Setup
Prerequisites
Python 3.8+
A Streamlit account
An OpenAI API key
Installation
Clone the repository:

git clone https://github.com/yourusername/ai-career-counsellor.git
cd ai-career-counsellor
Install the required dependencies:

pip install -r requirements.txt
Create a secrets.toml file in the .streamlit/ directory to store your API key:

# .streamlit/secrets.toml
[secrets]
key = "your_openai_api_key"
Run the application locally:

streamlit run app.py
Deployment
To deploy the app on Streamlit Cloud:

Push the repository to GitHub or your preferred version control platform.
Sign in to Streamlit Cloud.
Connect your GitHub repository and deploy the app.
Usage
Once the app is running, follow these steps to interact with the AI Career-Counsellor:

Enter your name.
Select your current education level (e.g., High-School Junior, College, Professional).
Describe any career-related problem or doubt you are facing.
Enter your favorite hobby when prompted.
Answer the generated questions.
The AI will analyze your responses and suggest personalized career options.
File Structure
https://ai-career-counsellor.streamlit.app/ 
