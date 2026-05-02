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
