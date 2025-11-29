🚀 Project Overview

This project automates AI-powered text editing using Nano Banana AI inside an n8n workflow.
It takes text or file input from a form, converts the file into Base64, sends the content to Nano Banana through an HTTP request, receives the edited text, and converts it back into a downloadable file.

This workflow demonstrates how to integrate LLM-powered text enhancement with no-code automation in n8n.

🧠 Features

🔹 Text editing using Nano Banana AI

🔹 Complete end-to-end automation inside n8n

🔹 Form-triggered workflow (text/file input)

🔹 Converts uploaded text files → Base64 → processed by AI

🔹 Converts AI output back into a file

🔹 Supports grammar correction, rewriting, formatting, summarization

🔹 Easy to extend for advanced NLP workflows

🛠️ Tech Stack

n8n (Workflow Automation)

Nano Banana AI (LLM for text editing)

OpenRouter API (LLM gateway)

HTTP Request Node

Edit Fields Node

File Conversion Nodes

🔁 Workflow Steps

On Form Submission

Captures input text or uploaded file.

Extract From File

Converts uploaded text file into Base64 string.

HTTP Request (Nano Banana API)

Sends Base64 text to Nano Banana

Receives edited/enhanced text response.

Edit Fields

Extracts the generated text from the response.

Convert to File

Converts AI output back into a text file (e.g., .txt).

Output / Download

Final edited text file is ready to download or forward.

📸 Workflow Screenshot

![Text Editing Workflow](./screenshots/text_edit.png)
