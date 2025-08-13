서버 세팅 방법

winget install Python.Python.3.12
winget install OpenJS.NodeJS.LTS

cd C;\path\to\server
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt

uvicorn app:app --host 0.0.0.0 --port 8000
