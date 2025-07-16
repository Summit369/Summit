# Summit Fintech MVP v1

This is the complete MVP setup for your fintech AI platform.

## Structure

- `web/`: React + Tailwind UI (Vercel deploy)
- `mobile/`: React Native + Expo app
- `backend/`: FastAPI server with /predict and /price APIs

## Web App (Deploy to Vercel)

1. Push `web/` to GitHub
2. Go to https://vercel.com → Import repo
3. Deploy instantly

## Mobile App (Expo)

```bash
cd mobile
npm install
expo start
```

Scan QR in Expo Go app to test.

## Backend (FastAPI)

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

Deploy to Render for cloud hosting.
