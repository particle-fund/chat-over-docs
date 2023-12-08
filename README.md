# 💬 📚 Chat Over Docs

This prototype allows users to chat over their documentns.

## Table of Contents
- [Project Overview](#project-overview)
- [Quick Start](#quick-start)

## Project Overview

This project allows users to:

📋 Upload a directory of PDF files

💬 Chat with their directory of PDF files

💡 Have the document for responses cited

🧠 Maintain memory of the conversation

## Quick Start

1. Build your container image:

```docker build -t chat_over_docs .```

2. Run your container using your image:

```docker run -it --name chat_over_docs chat_over_docs /bin/bash```

3. Open the executable file to add your OpenAI key

```vi chat_over_docs.py```

4. Add your OpenAI key

5. Copy your directory of documents into the container

```docker cp /path/to/local/directory chat_over_docs:/app```

6. Start the chat app

```python chat_over_docs.py```

7. Enter the path of your documents directory.

8. Start chatting!