# Create a virtual environment
python -m venv venv

# Activate 
# windows
venv\Scripts\activate

# Mac/Linux 
source venv\bin\activate

# Install packages
pip install -r requirements.txt

# Add your API Key 
Copy .env.example to .env and insert your own key

# To scan your file inter this command
python scanner.py <vulnerable_file.py>
