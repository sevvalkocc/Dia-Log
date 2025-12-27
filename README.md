
1. Install dependencies:
   `npm install`
2. Set the `GEMINI_API_KEY` in [.env.local](.env.local) to your Gemini API key
3. Run the app:
   `npm run dev`


   # Dia-Log (Dialogv2)

Glucose prediction demo project with:
- **Frontend (React + Vite + TypeScript)** UI
- **Backend (FastAPI)** `/predict` endpoint

## Project Structure
- `api/` → FastAPI backend
- `components/`, `services/`, `context/`, `types.ts` → Frontend source

---

## Requirements
- Node.js (recommended: 18+)
- Python (recommended: 3.10+)

---

## Backend (FastAPI)
### 1) Create venv & install deps
```bash
cd api
python -m venv .venv
# Windows PowerShell:
# .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt

