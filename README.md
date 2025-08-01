# Learn Agent Development Kit

Related documentation: https://google.github.io/adk-docs/

# How to run

1. Install the required packages

```bash
pip install -r requirements.txt
```

2. Adjust .env file

```bash
# Copy the .env.example to .env
cp .env.example .env

# Edit the .env file to set your API key
GOOGLE_GENAI_USE_VERTEXAI=FALSE
GOOGLE_API_KEY=PASTE_YOUR_ACTUAL_API_KEY_HERE
```

3. Run the agent

```bash
# Web
adk web

# CLI
adk run multi_tool_agent

# API
adk api_server
```
