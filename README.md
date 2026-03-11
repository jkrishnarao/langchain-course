https://github.com/emarco177/langchain-course

Setup Instructions
Clone the repository

git clone https://github.com/emarco177/langchain-course
cd langchain-course
Choose your learning path

For branch-based projects:

# Start with Hello World
git checkout project/hello-world
uv sync
uv run python main.py

# Progress to Code Interpreter
git checkout project/code-interpreter
uv sync
uv run python main.py

For external repository projects:

# Clone specific project repositories
git clone https://github.com/emarco177/ice_breaker
cd ice_breaker
# Follow project-specific setup instructions
=============================
git rm -rf *
uv init
uv add langchain
uv add langchain-openai
uv add langchain-ollama
uv add python-dotenv  --> to add env 
uv add black isort  --> for formatting

create openai api key : https://platform.openai.com/api-keys and put it under .env file
