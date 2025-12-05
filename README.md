🔧 Setup Instructions
1️⃣ Clone the repository
git clone <your-repo-url>
cd <your-project-folder>

2️⃣ Create a virtual environment (first time only)
python -m venv venv

3️⃣ Activate the virtual environment

macOS / Linux:

source venv/bin/activate


Windows (PowerShell):

venv\Scripts\activate

4️⃣ Install dependencies
pip install -r requirements.txt

🚀 Run the Flask App

Start the app:

flask run --debug


The app will run at:

Local machine:
http://127.0.0.1:5000

GitHub Codespaces:
(GitHub will open this automatically)

https://<your-codespace-URL>-5000.app.github.dev/
