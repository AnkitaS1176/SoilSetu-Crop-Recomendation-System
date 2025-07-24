# 1. Create workspace & go inside
mkdir SoilSetu; cd SoilSetu

# 2. Create venv
python -m venv .venv

# 3. Activate venv
.\.venv\Scripts\Activate

# 4. Unzip OR clone repo
# unzip project.zip 
# git clone <repo_url> .

# 5. Install deps
pip install --upgrade pip
pip install -r requirements.txt

# 6. Run the Flask app
python app.py
