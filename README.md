# 🔐 AI Security Scanner for Python

An AI-powered CLI tool that uses Google's Gemini API to scan Python code for security vulnerabilities and displays color-coded severity ratings in the terminal.

## 🚀 Features

- **AI-Powered Analysis** – Uses Google Gemini API to detect security vulnerabilities in Python code
- **Vulnerability Detection** – Identifies common issues like:
  - SQL Injection
  - Hardcoded Secrets/Credentials
  - Weak Cryptography (e.g. MD5 hashing)
- **Severity Ratings** – Each vulnerability is rated by severity level
- **Color-Coded Output** – Uses `colorama` for easy-to-read, color-coded terminal output
- **File Scanning** – Scan real `.py` files directly from the command line

## 💡 Why I Built This

I built this project as a hands-on deep dive into modern Applied AI and API integration. While studying Machine Learning concepts, I wanted to move past theoretical tutorials and build a functional tool that interacts with a live Large Language Model (LLM).

This scanner was born out of a curiosity to see how well generative AI could understand code structures compared to traditional text-matching software. It served as my playground to master:
- **API Architecture:** Designing clean request payloads and managing rate limits/responses using the Google Gemini API.
- **Prompt Engineering for DevTools:** Structuring system prompts to force an LLM to reliably return objective, structured security analysis without hallucinations.
- **Cybersecurity Fundamentals:** Researching common source-code vulnerabilities to verify the accuracy of the model's outputs.
