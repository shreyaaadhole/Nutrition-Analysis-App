⚙️ Installation & Setup

1) Clone the repository:
git clone https://github.com/YogeshRaje/Healthapp_GoogleGeminiLLM.git
cd Healthapp_GoogleGeminiLLM

2) Create and activate a virtual environment:
python -m venv venv
venv\Scripts\activate      # Windows
source venv/bin/activate

3) Install dependencies:
pip install -r requirements.txt

4) Generate an API key from Google MakerSuite:
Create a .env file in the root folder:
GOOGLE_API_KEY="your_api_key_here"

5) Run the app:
streamlit run health.py
