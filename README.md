# LinkStash

A simple, private, self-hosted link manager. Save a link, give it a name,
a description and tags, then find it again later with fast search.

> Status: early development. Not ready for use yet.

## Features (planned)

- Save links with a name, description and tags
- Instant search across everything you saved
- Runs on your own computer. Your data never leaves it
- Single user, protected by a password
- Free and open source (MIT)

## Tech

- Backend: Python + FastAPI
- Database: SQLite (one file)
- Frontend: React + TypeScript

## Run the backend (development)

```bash
cd backend
python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Then open http://127.0.0.1:8000/docs in your browser.

## Contributing

See CONTRIBUTING.md.

## License

MIT. See LICENSE.
