# Career-Guide-Agent
Many students are unsure about which career path to choose and what skills they need to achieve their goals. This project helps students by providing personalized career guidance based on their interests, education, and career goals.
# Career Guide Agent

This is my project for the Microsoft Agent League Hackathon.

## What it does

This AI agent helps students like me figure out:
- Which careers fit my skills and interests
- What skills I'm missing for that career
- A simple 3-month plan to learn those skills

## How it works

It uses Claude AI in 3 steps:
1. Suggests 3 career options based on my profile
2. Finds the skill gaps for the career I choose
3. Creates a 3-month learning roadmap

## How to run it

1. Install requirements:

pip install -r requirements.txt


2. Add your Anthropic API key:

export ANTHROPIC_API_KEY="your-key-here"


3. Run:

python agent.py


## Tech used

- Python
- Anthropic Claude API

## Note

You can change the student profile (skills, interests, education) inside agent.py to test with your own details.

## Made by

Likit Sai Reddy
