# Zikhin_Project
This is a candle website.

<!-- create venv -->
python3 --version
python3 -m venv venv
source venv/bin/activate

<!-- install dependency -->
pip install fastapi uvicorn jinja2

<!-- run uvicorn server -->
uvicorn app_name:app --host 0.0.0.0 --port 8000 --reload

<!-- create requirements.txt file -->
pip freeze > requirements.txt